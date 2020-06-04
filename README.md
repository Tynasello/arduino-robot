# arduino-robot
bluetooth controlled and obstacle avoiding

The purpose of this project was to create a fully functional robot using an arduino microcontroller that could be controlled by a mobile device via bluetooth. The robot performs certain maneuvers based on bluetooth input from a bluetooth terminal application. 

The robot has an optional "autonomous mode" which can be activated by typing the character 'a' through a bluetooth terminal app on a cellular device. When autonomous mode is activated the robot will drive forward until the ultrasonic sensor on the front of the robot detects a object that is within 10 cm of the front of the chassis. The robot will then redirect its route and continue driving forward as long as no objects are closely in front.

-Ty Nasello
