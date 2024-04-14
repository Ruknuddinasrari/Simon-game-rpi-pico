# Simon-game-rpi-pico

Description: This project entails the development of a Simon game on the Raspberry Pi Pico using C language. The game challenges players to remember and replicate a sequence of LED patterns, with the difficulty increasing as the game progresses.

Technical Details:
•	Edge Detection: Utilized gpio callback functions for signal state changes, essential for button press recognition.
•	Debouncing: Implemented a debounce function to ensure stable, bounce-free button inputs.
•	Multicore Processing: Employed the Pico’s multicore functionality with pico_multicore library for efficient task management and parallel processing.

Hardware Components:
•	Raspberry Pi Pico
•	Breadboard
•	LEDs (Red, Green, Yellow, Blue)
•	330 Ω Resistors
•	Push Buttons (x5)
•	Jumper Wires (Male-to-Male)
Software Tools:
•	GNU Arm Embedded Toolchain
•	Mingw-w64
•	CMake
•	Visual Studio Code
•	Git for Windows
•	PuTTY

Gameplay Mechanics: Players interact with the game using push buttons to replicate the LED patterns. The game monitors the player’s input accuracy, with the score increasing for each correct pattern replicated. The game continues until a mistake is made, after which it requires a reset to start anew.

Code Structure: The codebase comprises functions for GPIO initialization, button state management, pattern generation, and game logic. The main function initializes the GPIOs, sets interrupts with callback functions, and calls multicore functions to handle game progression1.
Conclusion: This project provided a valuable learning experience in embedded system programming, particularly in utilizing the Raspberry Pi Pico’s features and developing interactive software with user input handling.

![1](https://github.com/Ruknuddinasrari/Simon-game-rpi-pico/assets/49069833/37c9e1af-d4e7-41d5-b755-05ca2efc177c)


