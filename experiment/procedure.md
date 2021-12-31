<u>**Aim of the experiment :Circuit Breaker Status Indication from field input**</u>

Yokogawa CS 1000 (DCS) is having Digital Input Module with 16 input ports. These ports will get inputs from field devices such as circuit breakers and these statuses of the circuit breaker will be displayed on Human-Machine Interface of workstation. When the circuit breaker is ON corresponding Input ports of Digital Input module will be shorted. When circuit breaker is OFF corresponding Input parts of Digital Input module will be open.

This process is simulated as below:  
The Input from various Circuit breakers in the field is simulated using Array of switches, connected to parts of DI module.

1. Close switch connected to Digital Input1 (DI1) indicates CB1 is closed,Green color is displayed for CB1.
2. Open switch connected to Digital Input2 (DI2) indicates CB2 is open, Red color is displayed for CB2.

This process is followed for all circuit breakers in the field.
