#  Door Lock System Using Arduino UNO (Proteus Simulation)

##  Project Description
This project simulates an automated door lock system using an Arduino UNO and relay module in Proteus 8 Professional. The DC motor simulates the lock actuator.

##  Components Used
- Arduino UNO
- Relay (12V)
- DC Motor
- Serial Terminal (for status messages)
- Proteus 8 Professional

##  Working Principle
- The Arduino controls a relay that powers a DC motor.
- The motor represents a locking/unlocking mechanism.
- When the correct logic is triggered (e.g., HIGH signal from a pin), the relay activates and powers the motor.
- You can monitor/control the setup via the virtual serial terminal.


##  How to Run
1. Open the `.pdsprj` file in Proteus.
2. Load the `door_lock.ino` code into Arduino IDE and compile to generate the `.hex` file (if not already present).
3. Load the `.hex` file into the Arduino component in Proteus.
4. Run the simulation.


##  Credits
Created by Adithya M Bharadwaj using Proteus & Arduino UNO.


