# Scada_Assignment
Blinkstick Scada Assignment

Coursework 2 is a file of written code for using a blinkstick to interpret 
the personalised data received from a Data Acquisition system from the Scada.py 
library

It takes the voltage readings from the DAQ over a given time, converts them into 
"real" voltage readings, shifts them so that it outputs voltage values between 5V 
and -5V, filters out the noise and directs the blinkstick to act accordingly

The blinkstick will act as a warning light; showing red when the voltage values 
go below -2.56V and showing green when the voltage values go above 4.27V. 
The code can also be easily programmed using the warning_light_alarm function to 
sound an audible alarm when these thresholds are breached and halt the process 
until the operator has acknowledged the alarm state

The code will print out the times at which the warning lights on the blinkstick 
turn on and off as well as producing a real time graph of the voltage against
time so the operator can monitor the voltage status

At the end of the given time period, the blinkstick will turn itself off
