# Simon-game-rpi-pico

Introduction 
The purpose of this experiment was to understand how to use Pico C/C++ SDK to write a C program to let a user play the Simon game using 4 LED’s and 5 push buttons, hence I implemented the software using libraries such as pico_multicore for debounce, pico_stdlib I also learned how to implement the hardware. 

![1](https://github.com/Ruknuddinasrari/Simon-game-rpi-pico/assets/49069833/37c9e1af-d4e7-41d5-b755-05ca2efc177c)

Procedure 
For this project I have used a Pico h, a breadboard; a red, green, yellow and blue LED; 4 330 Ω resistors; a selection of male-to-male (M2M) jumper wires, and 5 push buttons. The software used are -GNU Arm Embedded toolchain, Mingw-w64 for Windows native build Cmake, Visual Studio Code, Git for Windows, and Putty. 
• I have implemented the Simon game in c language and generated a uf2 file to run it on a Pico h board, So the game begins with a single randomly generated pattern of one LED, 
• The user should press the corresponding button’s, If the user has some doubts he can see the command line on putty to cheat, If the user correctly repeats the pattern, Then the score is incremented by one and it is displayed before the next pattern is incremneted by one and displayed, 
• And this continues untill the user inputs the wrong pattern. 
• Then it waits for the user to press the reset button to start over 
• I have used random number generator to generate different orders of pattern of led’s
