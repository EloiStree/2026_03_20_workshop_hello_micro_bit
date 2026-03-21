# Do it yourself

``` gdscript
class_name MicroBitChangeLedColorWithSignal
extends Node3D

signal on_color_led_changed(new_color:Color)

@export_range(0.0,1.0,0.001)
var last_received_state_as_percent_0_1 :float = 0.0

@export var emit_state_at_start :bool =true

func _ready():
  # TODO

func get_led_state_as_percent_0_to_1()->float:
  # TODO
func get_led_state_as_0_to_9_int()->int:
  # TODO
func get_led_state_as_0_to_9_char()->String:
  # TODO
	
func turn_on():
  # TODO
	
func turn_off():
  # TODO
	
func turn_on_off(value:bool):
  # TODO
	
func set_random_color():
  # TODO
	
func set_cube_color(color:Color):
  # TODO

func set_color_red_with_percent(percent:float):
  # TODO
	
func set_color_red_with_0_to_9_float(value_0_9:float):
  # TODO
 
func set_color_red_with_0_to_9_int(value_0_9:int):
  # TODO

func set_color_red_with_0_to_9_char(text_with_a_0_9:String):
  # TODO
		
	```



``` gdscript
class_name MicroBitSetMeshInstanceColor3D
extends Node

@export var to_affect: MeshInstance3D = null
@export var duplicate_material_at_ready: bool = true

func _ready() -> void:
	if to_affect == null:
  		# TODO
	
	if duplicate_material_at_ready:
  		# TODO

func set_color_of_the_mesh_material(new_color: Color):
  	# TODO
```
	
	
