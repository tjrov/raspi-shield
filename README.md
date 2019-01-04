EAGLE files for a board that sits on top of a Raspberry Pi 3 in the ROV and provides additional functionality:
- PCA9685 (16 PWM signal outputs to control ESCs for thrusters and manipulators)
- MS5803-14BA (pressure/depth sensor)
- BNO055 (orientation in all three rotation axes)
- Status LED
All of the above (except the LED) are accessed over the I2C bus (taken from the GPI/O header).
We can use the tether as an ethernet cable and connect it to the RPi network jack.
We can connect a camera (USB or GPI/O, or both) to the RPi and stream that up the tether. This will make CV easier if we want to do that.
We will still have two analog video lines left on the tether.
