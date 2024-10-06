# IR Sensor Using 8051 Micorcontroller
This IR sensor circuit uses an 8051 microcontroller to process input from a TSOP1738 IR receiver, detecting modulated IR signals and controlling LEDs as indicators. It can be used for applications like remote control systems, obstacle detection, and proximity sensors.
## Circuit Overview:
An 8051 microcontroller is used to process the input from an IR sensor (TSOP1738) and control LED indicators.
The TSOP1738 detects modulated IR signals (typically 38 kHz) and sends an output signal to the microcontroller.
The microcontroller processes the signal and triggers LEDs to indicate detection.
## Components and Functions:
* TSOP1738 (IR Receiver):
Detects IR signals.
Sends output to the microcontroller.
* 8051 Microcontroller:
Processes IR sensor output.
Controls LEDs and other peripherals.
* Crystal Oscillator (Y1):
Provides clock signal for the microcontroller.
* Push Button (SW1):
Used for manual input to trigger/reset functions.
* Resistor Network (RN1):
Limits current to protect microcontroller and LEDs.
LEDs (D1, D2, D3):
Visual indicators showing the detection of IR signals.
* Decoupling Capacitors (C1, C2, C3):
Filter noise from the power supply.
## Working:
* The IR sensor detects an IR signal and outputs a signal to the microcontroller.
* The 8051 microcontroller processes the input and turns on the corresponding LEDs.
* The Push Button allows manual triggering of the circuit.
## Applications:
* IR remote control systems.
* Obstacle detection and proximity sensors.
