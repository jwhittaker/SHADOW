Introducing S.H.A.D.O.W. (Small Handheld Arduino Droid Operating Wand) MSE Edition
A MSE droid control system based on DanF's Padawan, and Darren Blum's S.H.A.D.O.W. that uses a PS3 Move Navigation Controller

This is a fork of Darren Blum's S.H.A.D.O.W. system. It is specifically modified to support MSE (RC Car) Based Droids.

It is a slimmed down version of the original code base to only support what is used on these types of droids and makes
opinionated decisions (like only supporting the Sparkfun MP3 Trigger). If you are already familiar with S.H.A.D.O.W.
then this fork will feel very familiar.

This sketch works on an Arduino MEGA or Arduino MEGA ADK only.

Pin Assignment:
Steering Servo: 44
ESC: 45
MP3 Trigger: 18

Sound Mapping:
D-pad Up - Sound 001
D-pad Right - Sound 002
D-pad Down - Sound 003
D-pad Left - Random Sound 001-015
L2 + D-pad Up - Sound 004
L2 + D-pad Right - Sound 005
L2 + D-pad Down - Sound 006
L2 + D-pad Left - Sound 015
L1 + D-pad Up - Volume Up
L1 + D-pad Right - Sound 019
L1 + D-pad Down - Volume Down
L1 + D-pad Left - Sound 018

Additional information for the original S.H.A.D.O.W. Sketch can be found in this thread on Asromech.net:
http://astromech.net/forums/showthread.php?19298-S-H-A-D-O-W-Padawan-based-mini-PS3-Controller

Thank you to:
-Darren Blum - aka KnightShade
-MSE Droid Builders Facebook page
