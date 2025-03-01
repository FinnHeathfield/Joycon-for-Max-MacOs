# Joycon for Max
*for MacOs*

This Max patch provides 3 Sub-patchers which will route output data from a gamepad object when 2 joycon controllers are connected to a MacOs device via bluetooth as game controllers. The patch also has a UI to test data input from each device.

The provided patchers will handle either both controllers, or each individually. These can be copy and pasted into any other patch. 


## Message Mapping
*below are the messages given by the gamepad object and their corresponding input buttons*

|Message        |Button                  |
|---------------|------------------------|
|axis_left_x (f)|Left Joystick X position|
|axis_right_x (f)|Right Joystick X position|

