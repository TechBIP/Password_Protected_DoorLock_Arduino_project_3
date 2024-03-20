# Password_Protected_DoorLock
This project Repository is all about creating a password protected door lock using Arduino Uno.

# Circuit Components Required:- 
4X4 Keypad, Breadboard, Piezo, Leds, Arduino UNO.

# Software Required:-
NOTE****** This experiment can be performed both by using hardware as well as by using Software.
For Hardware:- make sure that you have all the required circuit components and ARDUINO IDE Installed.
For software:- Open an Tinkercad account you can design and simulate your designs online. 

# Circuit connections:- 
Take reference from the circuit diagram design done and attached to this repository. 
1. The 4x4 keypad has 8 built in switches, among which the R1 is connected to Digital pin D9.
2. The R2 pin is connected to D8
3. The R3 pin is connected to D7
4. The R4 pin is connected to D6
5. The R5 pin is connected to D5
6. The R6 pin is connected to D4
7. The R7 pin is connected to D3
8. The R8 pin is connected to D2
9. Power is given to 5V of Arduino via breadboard.
10. D10 is connected to Red led (indicating wrong password).
11. D11 is connected to Green led (indicating correct password).
12. Piezo +ve is connected to D12.
13. Piezo -ve is  connected to GND.

# Result:
On Running and simulating the circuit, We can view the output on the serial monitor window. On serial monitor it first asks for enter password. 
For that we need to type out the password on the 4x4 keypad on the circuit connections. If the entered password is correct as set in the code then the piezo will buzz, along with the green led blinking, It will show a message on the serial monitor saying that "ENTER". Again it will ask for password suppose if we enter a wrong password, then the piezo will buzz for a longer time and the red led will blink and the serial monitor will print a message saying "WRONG PASSWORD" and automatically the door will remain close and you cant enter at that time.
This is how a password protected door lock system works.
# Contributions:
Contributions are welcome. If you have any sujjestions, ideas related to this project feel free to contribute.
