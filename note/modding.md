extends Node
@export var button_a:bool = false
@export var button_b:bool = false
@export var leds_percent_5x5:Array[float] =[]



# IMPLEMENT IF YOU NEED	
# func mod_in_set_leds_array_changed(is_pressing:Array[float]):
# func mod_in_set_button_a_changed(is_pressing:bool):
# func mod_in_set_button_b_changed(is_pressing:bool):
# func mod_in_on_a_value_changed()

func _ready()->void:
	# print("Hello World")
	pass

func _process(delta:float)->void:
	# print("DELTA:",delta)
	pass












extends Node

signal mod_out_set_leds_array(array:Array[float])
signal mod_out_set_1d_led_to_percent(index_0_24:int, percent:float)
signal mod_out_set_1d_led_to_char_0_9(index_0_24:int,char_value:String)
signal mod_out_set_1d_led_to_percent(x_left_right:int,y_top_down:int, percent:float)
signal mod_out_set_1d_led_to_char_0_9(x_left_right:int,y_top_down:int, char_value:String)

@export var button_a:bool = false
@export var button_b:bool = false
@export var leds_percent_5x5:Array[float] =[]

# Implementable:
## Any value of the device was changed or updated.
# func mod_in_a_value_changed()
## Received update value of the array (changed or not)
# func mod_in_leds_array_updated(is_pressing:Array[float]):

## Button A changed of state
# func mod_in_button_a_changed(is_pressing:bool):

## Button A changed of state
# func mod_in_button_b_changed(is_pressing:bool):



#####
micro_bit_modding_interface_to_node.gd
class_name MicroBitModdingInterfaceToNode
extends Node

@export var node_to_affect:Node

@export_group("Variable")
@export var name_of_var_leds_percent_array ="leds_percent_5x5"
@export var name_of_var_button_a ="button_a"
@export var name_of_var_button_b ="button_b"
@export_group("Function in")
@export var name_of_call_leds_changed ="mod_in_set_leds_array_changed"
@export var name_of_call_set_button_a ="mod_in_set_button_a_changed"
@export var name_of_call_set_button_b ="mod_in_set_button_b_changed"
@export var name_of_call_a_value_changed ="mod_in_on_a_value_changed"

func set_node_to_affect(node:Node):
	node_to_affect = node
	

func set_variable_to(variable_name:String, set_method_name:String, value):
	if node_to_affect!=null and node_to_affect.has_method(set_method_name):
		node_to_affect.call(set_method_name,value)
	if node_to_affect and variable_name in node_to_affect:
		node_to_affect.set(variable_name,value)
	notify_a_value_changed()
	
	
func call_methode_without_params(methode_name:String):
	if node_to_affect and node_to_affect.has_method(methode_name):
		node_to_affect.call(methode_name)	
			

func notify_a_value_changed():
	call_methode_without_params(name_of_call_a_value_changed)	
	
	
func set_leds_percent_with_random_5x5():
	var random_5x5:Array[float]= []
	for i in range(25):
		random_5x5.append(randf())
	set_leds_percent_array(random_5x5)
	
func set_leds_percent_array(array:Array[float]):
	set_variable_to(name_of_var_leds_percent_array, name_of_call_leds_changed, array)
	

func set_button_a_state(is_pressing:bool):
	set_variable_to(name_of_var_button_a, name_of_call_set_button_a, is_pressing)
		
func set_button_b_state(is_pressing:bool):
	set_variable_to(name_of_var_button_b, name_of_call_set_button_b, is_pressing)
		



# if node and node.has_signal("some_signal"):
#    node.some_signal.connect(_on_some_signal)



"""
