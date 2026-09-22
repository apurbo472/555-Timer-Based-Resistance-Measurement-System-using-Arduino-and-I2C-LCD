# 555-Timer-Based-Resistance-Measurement-System-using-Arduino-and-I2C-LCD

555 Timer Based Resistance Measurement System

The project measures an unknown resistance using the time-period of a 555 timer astable multivibrator. The measured signal is processed by an Arduino, and the calculated resistance is displayed on an I2C LCD.

Principle:

$$ T = 0.693(R_1+2R_x)C $$

Therefore,

$$ R_x=\frac{\frac{T}{0.693C}-R_1}{2} $$
Main components
NE555 Timer IC
Arduino
I2C 16×2 LCD
Unknown resistance \(R_x\)
Timing capacitor
Resistors
Proteus simulation
Features
Measures unknown resistance from the 555 timer's oscillation period
Arduino-based period measurement
Resistance calculation using the 555 astable equation
LCD display of measured resistance
Proteus simulation
