# Do it yourself

[🎥](https://youtu.be/Tq3iMY05yEE): https://youtu.be/Tq3iMY05yEE

``` gdscript
class_name MicroBitMatrixLeds5x5
extends Node3D

#region DOC ARRAY STRUCTURE
# 1D Array in a 2D view
###################
## LEFT->RIGHT TOP->DOWN
## X0 X1 X2 X3 X4 
##  0  1  2  3  4 Y0
##  5  6  7  8  9 Y1   
## 10 11 12 13 14 Y2
## 15 16 17 18 19 Y3
## 20 21 22 23 24 Y4
#endregion

#region CONSTANT
# constant
const MAX_LED_COUNT :int = 25
const MAX_LINE_COUNT :int = 5
const MAX_COLUMN_COUNT :int = 5
# Array start from 0 and not 1
const MAX_LED_INDEX :int = 24
const MAX_LINE_INDEX :int = 4
const MAX_COLUMN_INDEX :int = 4

const IMAGE_EMPTY :="""
		00000
		00000
		00000
		00000
		00000
		"""
const IMAGE_FULL :="""
		99999
		99999
		99999
		99999
		99999
		"""

const IMAGE_BORDER:="""
		99999
		90000
		90009
		00009
		99999
		"""
#endregion

#region EXPORT VARIABLE
## Represent 25 scripts that can be change to red intensity with 0-9 percent
@export var array_of_leds:Array[MicroBitChangeLedColorWithSignal]

## Must be over 0. Under it remove the feature.
@export var second_between_debug_refresh:float =1

@export_group("Debug")
@export_multiline var for_the_demo_image:String
@export var for_the_demo_percent:Array[float]
@export var for_the_demo_int:Array[int]
#endregion


func _ready() -> void:
    # TODO

### TRY TO CREATE CODE AND USE 
# display_clear()
# while true:
# await  get_tree().create_timer(0.5).timeout
# display_turn_all_leds_on()
# display_turn_all_leds_off()
# var array_float:Array[float] = [0.1,0.2,0.3,0.4,0.5,1,1,1,1,1]
# var array_int:Array[int] = [1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9,1,2,3,4,5,6,7,8,9]
# var array_text:Array[String] = ["1","2","3","4","5","6","7","8","9"]
# display_set_all_leds_with_array_of_float(array_float)
# display_set_all_leds_with_array_of_0_9_int(array_int)
# display_set_all_leds_with_array_of_0_9_string(array_text)
# var array_text_split:Array[String] =[]
# array_text_split.assign('0030003630369630363000300'.split("",false))
# display_set_all_leds_with_array_of_0_9_string(array_text_split)
# display_set_1d_led_to_percent(i,1)
# display_set_1d_led_to_percent(i,0)
# display_set_all_leds_as_random()
# display_inverse_all_leds_state_leds(0.5)
# display_set_on_off_led_1d(0,true)
# display_set_on_off_led_2d(2,2,true)
# display_set_on_off_led_2d(4,4,true)
# display_set_2d_led_to_0_9_char(1,1,"5")
# display_set_2d_led_to_0_9_int(1,2,7)
# display_set_2d_led_to_percent(3,3,0.65)
		
func display_clear():
    # TODO
	
func display_turn_all_leds_on():
    # TODO
		
func display_turn_all_leds_off():
    # TODO

func display_set_all_leds_with_array_of_float(given_array:Array[float]):
    # TODO
	
func display_set_all_leds_with_array_of_0_9_int(given_array:Array[int]):
    # TODO

func display_set_all_leds_with_array_of_0_9_string(given_array:Array[String]):
    # TODO
		
func remove_all_space_of_text(text:String)-> String:
    # TODO

func remove_any_that_is_not_0_to_9(text:String):
    # TODO

func display_set_all_leds_with_text_image(text:String):
    # TODO

func display_set_all_leds_to_percent(percent:float):
    # TODO
		
func display_set_all_leds_to_0_9_int(value_0_9:int):
    # TODO
		
func display_set_all_leds_to_0_9_char(value_0_9:String):
    # TODO

func is_valide_1d_index(index_0_24:int)->bool:
    # TODO
	
func display_set_1d_led_to_percent(index:int,percent:float):
    # TODO
		
func display_set_1d_led_to_0_9_int(index:int,value_0_9:int) :
    # TODO
		
func display_set_1d_led_to_0_9_char(index:int,value_0_9:String) :
    # TODO
		
func display_set_all_leds_as_random():
    # TODO
		
func display_inverse_all_leds_state_leds(threshold:float=0.5):
    # TODO
		
func display_inverse_on_off_state_led_1d(index_0_24:int,threshold:float=0.5):
    # TODO

func display_get_array_1d_state_as_percent()-> Array[float]:
    # TODO
		
func display_get_array_1d_state_as_int_0_9()-> Array[int]:
    # TODO
	
func display_get_array_1d_state_as_string_of_0_9(with_return_line:bool =true)-> String:
    # TODO

func refresh_debug_arrray_state():
	for_the_demo_image = display_get_array_1d_state_as_string_of_0_9()
	for_the_demo_percent =  display_get_array_1d_state_as_percent()
	for_the_demo_int = display_get_array_1d_state_as_int_0_9()

func display_get_1d_led_as_percent(index_0_24:int)->float:
    # TODO

func display_get_1d_led_as_0_9_int(index_0_24:int)->int:
    # TODO

func display_get_1d_led_as_0_9_char(index_0_24:int)->String:
    # TODO

func is_valide_index_2d(x_left_right_0_4:int,y_top_down_0_4:int)->bool:
    # TODO

func convert_1d_to_2d_left_right_top_down_xy(index_0_24:int)-> Vector2i:
    # TODO

func convert_2d_left_right_top_down_xy_to_1d(x_left_right_0_4:int,y_top_down_0_4:int)-> int:
    # TODO

    ## LEFT->RIGHT TOP->DOWN
    ## X0 X1 X2 X3 X4 
    ##  0  1  2  3  4 Y0 
    ##  5  6  7  8  9 Y1   
    ## 10 11 12 13 14 Y2
    ## 15 16 17 18 19 Y3
    ## 20 21 22 23 24 Y4
	
func display_inverse_on_off_state_led_2d(x_left_right_0_4:int,y_top_down_0_4:int,threshold:float=0.5):
    # TODO

func display_set_on_off_led_1d(index_0_24:int, value:bool)->void:
    # TODO
		
func display_set_on_off_led_2d(x_left_right_0_4:int,y_top_down_0_4:int, value:bool)->void:
    # TODO
		
		

func display_set_2d_led_to_percent(x_left_right_0_4:int,y_top_down_0_4:int,percent:float) :
    # TODO
		
func display_set_2d_led_to_0_9_int(x_left_right_0_4:int,y_top_down_0_4:int,value_0_9:int) :
    # TODO
		
func display_set_2d_led_to_0_9_char(x_left_right_0_4:int,y_top_down_0_4:int,value_0_9:String) :
    # TODO
		

func display_get_2d_led_as_percent(x_left_right_0_4:int,y_top_down_0_4:int)->float:
    # TODO
	
func display_get_2d_led_as_0_9_int(x_left_right_0_4:int,y_top_down_0_4:int)->int:
    # TODO

func display_get_2d_led_as_0_9_char(x_left_right_0_4:int,y_top_down_0_4:int)->String:
    # TODO


func display_get_2d_led_as_on_off(x_left_right_0_4:int,y_top_down_0_4:int,threshold_percent:float=0.5)->bool:
    # TODO
	
func display_get_1d_led_as_on_off(index_0_24:int,threshold_percent:float=0.5)->bool:
    # TODO

```
