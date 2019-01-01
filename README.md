# joystickTest

This sketch provides a simple check of the operation of the custom joystick shield used with the WCRS [carbot](https://github.com/WCRSyyc/carbot).  Exercising the joystick and integrated switch sends readings to the Serial Monitor.  This allows verification that the wiring is correct.  It reports actual measurements, allowing some calibration to be done if needed.

It was written as a utility to use during the construction of a custom joystick shield.  Recent versions of that shield may also include the interface to an nRF24L01 radio module.  This does not test anything related to that.  Other sketches will exercise that functionality.
