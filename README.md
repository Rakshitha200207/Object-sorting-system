# Object-sorting-system
Here objects are sorted using machine learning model
At the first ,the project involves the following components
1)ESP32 for capturing the images.
2)Servo motor to place the objects.
3)conveyor belt for movement of objects from camera module to the servo motor.
# hardware description
At the first pre-processed images will be captured were 200 images are taken for each set of object and this will be trained around 40000 stepin google colab platform.Then ESP32 camera module will be placed in the starting end of the conveyor belt,as described it will be capturing the image of an object,this captured images will be compared with the trained images .Like this the objects are sorted.
Step1:Initializing the ESP32 camera module,conveyor belt,servo motor.
step2:ESP32 camera captures the images placed on the coneyor belt.
step3:Machine learing model runs inside the system and returns the signal with objects name and at what angle should servo turns.
step4:after comparing conveyor moves towards the servo motor by this the serv motor will move to the respective angles and the objects will be succesfull detected and sorted in the respective partion.
