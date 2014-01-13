Project 1 : Breakout
CMPUT 274

Submitted by:- 

(a) Aaron Plamondon
    Student ID:- 1367121
    Section:- LEC EA1 / LBL ED01
    
(b) Udey Chander Rishi
    Student ID:- n/a
    Section:- LEC EA1 / LBL ED01

Submitted using Aaron Plamondon's eClass
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
Game Instructions:
Play the game by moving the paddle at the bottom of the screen and trying to break al of the blocks. The game is controlled by the joystick moving it left and right and pushing it in to elect a mode or pause the game.

Pin setup:-
Do not connect anything to pin A7 or the game will not properly generate random bricks.

LCD Screen:

1 GND to BB GND bus
2 VCC to BB positive bus
3 RESET to Pin 8
4 D/C (Data/Command) to Pin 7
5 CARD_CS (Card Chip Select) to Pin 5
6 TFT_CS (TFT/screen Chip Select) to Pin 6
7 MOSI (Master Out Slave In) to Pin 51
8 SCK (Clock) to Pin 52
9 MISO (Master In Slave Out) to 50
10 LITE (Backlite) to BB positive bus 

Joystick:

1 VCC to BB positive bus
2 VERT to Pin A0
3 HOR to Pin A1
4 SEL to Pin 9
5 GND to BB GND bus 

Speaker:

1 VCC to BB positive bus
2 Speaker Output to Pin 2

Tips:
Have Something to help anchor down the joystick so it does not move around.
