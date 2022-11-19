# ESP32Encoder
ALPS encoder works in one pulse
There is a problem
I'll start with the module, this is Lolin32 Lite (esp32)
The bottom line is that a gaming device (joystick, gamepad, etc.) is assembled on this module.
(Main library for BLEGamepad buttons, library for encoders ESP32Encoder)
Buttons and encoders are connected, everything is fine with the buttons, but the encoders do not work as they should
Japanese encoder ALPS (type 1/2) for 9 pulses 18 bits, the signal passes through one click
I did not find lines in the sketch that could somehow affect the situation
Ps I made similar devices on arduino pro micro, there was the same problem with the encoder, but there was a line #define Half step (I don’t remember exactly)
If you uncomment this line, then everything works as it should.
Maybe someone faced a similar problem on esp32, I will be very grateful for help in solving this problem, I hope I didn’t miss anything
