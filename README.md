# BMS
BMS - Battery Management System

Jon Freeman 
7th Feb 2025

Bristol SMEE asked about possible battery management systems for use in a five inch gauge battery loco, which had needed battery replacements sooner than expected.
At least a 'BMS' would monitor battery voltage and provide visual (LED) and audible warnings.

The loco drive control system uses a simple 'pot' (hand held rotary potentiometer) delivering a variable input voltage to the motor controller.
The BMS is inserted in this control line - giving the BMS the ability to reduce the 'speed demand' voltage delivered to the motor controller. By these means, the BMS is to have the ability to limit, suppress or reduce driver demand fed forward to anywhere from 0% and 100%. This is to prevent battery damage caused by over-discharge.

The spec suggests using a small microcontroller. To save time and cost, an existing module was 'repurposed' (this was a prototype petrol engine control system), modified for prototype BMS use.
