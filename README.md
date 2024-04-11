# EEE3088F_Group12 Mircomouse project

#Overview of project:

Desginging a maze solving robots power and sensor modules 

#Power: 



#Sensor:

This module will be responsible for detecting/sensing objects. You will
need to design and manufacture this module to fit the requirements
detailed in this document. The basic idea is:
▪ It needs to detect objects.
▪ It will need to fit onto the pin headers on the motherboard.
▪ It will need to be an appropriate size for the robot.

The sensor PCB is effectively the “eyes” of your robot. Your subsystem will provide information to
the processor to determine whether there is an obstruction in the way of your MM. Your submodule
needs to:
• Detect whether there is an obstacle in front of the robot (probably on the sides too).
• Have switching means to save power when not in operation.
Additionally, you need to:
• Design for reliability such that you can prove your system works.
• Consider how much power and current your sensing board is using/drawing so that you do
not drain the battery before the maze is solved.
• Write some code to interface your sensor with the rest of the system and prove it senses the
wall.
