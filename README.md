# Rockman-Clock
A simple clock using an LED matrix and an Arduino with WiFi

This was made on a NODEMCU using the ESP8266.  This is not as ideal as the ES32 because the ES32 has 2 cores.  Using the 2nd core of the ES32 is useful in performing WiFi functions.  There are visual artifacts on the LEDs every time CPU processing is used to perform WiFi operations.  Unfortunately, I can't get rid of this with the ESP8266.  I will update this code for the ES32 after I order one and use it.  

Also, the code is not very well documented.  The point of this project was for self-learning, and not for distribution.  However, a savvy programmer can learn a lot from the different techniques I used here.  

I hope to create an animation class that can perform the exhaustive coding behind animating arrays of colors.  I did figure out how to handle trasnparency (by ignoring pixels that match a certain color), and you can find that in the code.  

I hope that others can take this further!
