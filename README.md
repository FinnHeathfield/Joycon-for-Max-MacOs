# Joycon for Max
*for MacOs*

This Max patch provides 3 Sub-patchers which will route output data from a gamepad object when 2 joycon controllers are connected to a MacOs device via bluetooth as game controllers. The patch also has a UI to test data input from each device.

The provided patchers will handle either both controllers, or each individually. These can be copy and pasted into any other patch. 


## Message Mapping
Below are the messages given by the gamepad object and their corresponding input buttons
Data types are indicated after the message.
(f) = Float
(1/0) = 1/0 for on/off messages
(f f f) = List output. number of letter indicates size of list and data type of each element.

|Message|Button |
|--|-----------|
|axis_left_x (f)|Left Joystick X position|
|axis_right_x (f)|Right Joystick X position|
|axis_left_y (f)|Left Joystick Y position|
|axis_right_y (f)|Right Joystick Y position|
|---|---|
|button_left_stick (1/0)|Left Stick Button|
|button_right_stick (1/0)|Right Stick Button|
|---|---|
|sensor_gyro(f f f)|Gyroscope (Roll, Pitch, Yaw)|
|sensor_accel (f f f)|Accelerometer|
|---|---|
|button_a (1/0)|A Button|
|button_b (1/0)|B Button|
|button_x (1/0)|X Button|
|button_y (1/0)|Y Button|
|---|---|
|button_dpad_up (1/0)|Up Button|
|button_dpad_down (1/0)|Down Button|
|button_dpad_left (1/0)|Left Button|
|button_dpad_Right (1/0)|Right Button|
|---|---|
|axis_left_trigger (1/0)|ZL Button|
|axis_right_trigger (1/0)|ZR Button|
|---|---|
|button_left_shoulder (1/0)|L Button|
|button_right_shoulder (1/0)|R Button|
|---|---|
|button_start (1/0)|+ Button|
|button_back (1/0)|- Button|
|button_guide (1/0)|Home Button|
|button_misc1 (1/0)|Screenshot Button|
|---|---|
|button_paddle2 (1/0)|(L) SL Button|
|button_paddle4 (1/0)|(L) SR Button|
|button_paddle3 (1/0)|(R) SL Button|
|button_paddle1 (1/0)|(R) SR Button|
|---|---|


