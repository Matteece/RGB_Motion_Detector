# RGB_Motion_Detector
This program utilizes an MSP430FR6989 and an HC-SR04 ultrasonic range finder to detect motion.  If motion is detected, the board will cycle an RGB LED through its color spectrum
for as long as it detects motion, then the board will hold the LED at its current color until motion is detected again.

Upon powering up the device, the range finder will sit there taking measurements.  If the range finder detects a change in distance of more or less than 5 centimeters, the board
will interpret that as motion, and start cycling the RGB LED.
