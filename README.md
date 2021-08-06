#Project 

System for Face-Mask and body temperature detection.

Portable system for detecting facemask and body temperature. It can be used in large gatherings where only people allowed who are wearing masks

Equipments needed:
Raspberry pi (any model 3)
9MLX9061 temperature sensor.
Screen for displaying message.
Buzzer
LEDs (green, red)
Servo Motor for door.

On system(we were using Laptop)
Run the facemask_train python file to train the model. // need to train once.
Run detection python file to detect the face mask.
Run datasend python file to send the data collected to Raspberry. (You need to change the ip accordingly) 

On Raspberry pi
Run temperature.py.
