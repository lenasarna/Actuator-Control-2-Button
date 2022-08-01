# Actuator-Control-2-Button
Control the direction of a stepper motor using two buttons. Uses the tic-arduino library. 
For a gantry arm, testing of two actuated arms had to be done. It consists of a horizontal and vertical actuator.
Using two buttons, the code is able to control the direction that a stepper motor is able to rotate depending on which button is pressed.
The stepper motors tested used a tic 36v4 and the code uses the tic library. If a different tic is used, that must be changed in the code.

The actuator speeds depend on which actuator is being tested. 
- The horizontal speed: 10000000. 
- Vertical speed: 50000000. 

Not quite sure if the current limit changes when the motors are at rest or activated, this aspect has not been tested yet. 

A tic-arduino library was used to create this code. 
- https://github.com/pololu/tic-arduino
