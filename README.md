# Sequential-Lighting-System
//This is a project I made using VHDL and the ___________ software that aims to recreate the 
sequential lighting system in cars made famous by the Ford Thunderbird and used in cars
like the Ford Mustang today. Essentially this program is for the taillight of a car,
with breaks, hazard, and turn signals. If the turn signal is engaged, it will show either the
left or right lights lighting in sequence from left to right for the right signal or 
right to left for the left signal. If the hazard signal turns on, it will show the lights
turning off and on in quick succession. The break signal makes the tailights shine for
as long as the signal is engaged. The program also determines that the break signal takes
precedence over all of the other light signals, meaning that the break signal will take over
the taillights if it is engaged regardless of if the other signals are on or not. This program 
was tested on a Cyclone II microprocessor which has led lights to simulate the taillights on a car.
I needed to program which leds on the processor were to be the lights on the car as well as which buttons were
the diffrent light signals.
