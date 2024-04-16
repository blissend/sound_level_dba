# sound_level_dba

Using m5stickc plus2 to record environmental noise and record that data to a pushgateway endpoint.

##

This uses FFT to help calculate decibels and filters through a preset range of A-Weighted (what human ear can hear). Use the buttons to filter/calibrate the live capture to your decibel meter. Note the long press doesn't work so pressing the m5 button has to be one quick press and pause sadly.

## Requirements

Please see https://docs.m5stack.com/en/arduino/arduino_ide to setup your IDE. Install...

* Arduino IDE
** Add m5stack m5stickcplus2
** Select the USB attached port
** Manage libraries and search for m5stickcplus2, arduinoFFT