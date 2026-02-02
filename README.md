# Hand-Gesture-Controlled-LED-s
(using Python , open cv, Arduino Uno)
Software Setup:-
Download Python
Download Arduino Uno
Download Open Cv (pip install opencv.python) using Command Prompt
Download mediapipe (pip install mediapipe) using Command Prompt
we will use visual studio code and arduino uno ide for writing codes.
# Code Setup:-
import opencv in main.py
import mediapipe in main .py
full code ( main.py )
import pyfirmata to connect to ardiuno in controller.py
select comport using device manager to connect ardiuno board
full code( controller.py )
import controller in main.py
open ardiuno ide
select files,examples,firmata,standard firmata
select ardiuno board with comport written with it
upload the code
# Hardware Setup:-
Take ardiuno Board and connect male to male jumper wires from gnd,pin 13,12,11,10,9
Now connect gnd wire to negative terminal of bread board
Connect all 5 pins connection to positive side of bread board
Connect all 5 led’s positve end wit alongside positive wire and negative side in negative terminal end
Now you are done,
