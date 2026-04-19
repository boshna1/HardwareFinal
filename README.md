# HardwareFinal

Joshua Dinata
100921955

All files and supporting screenshots can be found in the files organized

Part 1 is not in the Controller files folder
Part 2 controller files and screenshots are in the Controller Files folder

Part 1:
2. 150 ohm resistor

Part 2:
Game: Ice Climbers

I designed a controller that looks like a miniature mallet. It usess a 1 axis potentiometer for left and right movement like a typical joystick. a push button for jump, start and select. A tilt axis sensor to detect aboce a certain acceleration threshold to detect a "hit". Turning the controller like how the hammer does in the game can be immersive, intuitive, and also user friendly. A speaker to indicate when a hit in game hits a block. A green LED to also light up when the player hits a block or collects a vegetable. 3 Red LED's which light up according to how many lives the player has left. The handle at the bottom is completely visual but ensures the controller is percieved to look like a mallet.

Electronics:
Demo Link: https://youtu.be/q60MVkpeXmg

The Electronics prototype has a piezo, tilt axis, 3 buttons 4 leds and a potentiometer. The potentiometer is meant to symbolize the 1 axis joystick used to move left and right. The two center buttons are for start and select. The right most button is for jumping and the tilt axis is for hitting. any action will light the green left LED to signify any sort of input and output to the game. The 3 red LEDS are meant to symbolize lives left and will turn off when losing one. The piezo goes off only when hitting, meant to play a hitting sound when successful. The demo does not fully encapsulate what I wanted functionally but the wiring and the code does outline what I would want it to be.

Controller:

I designed the controller to be shaped like a hammer to correlate the in game tool and the controller, increasing immersion and also intuitiveness and fun within the player. The intuitiveness comes from the idea of using a tilt axis sensor to complete a hit in the game, mirroring the action in the game with the action in real life, making it easier for the player to remember and learn how hitting works. This reduces the cognitive load it may take to find the right button to hit and instead use the automatic correlation between controller and game. The jump button is the only functional button within the game other than start and select, which should be cognizant choices to make because they are menu buttons and aren't always used in gameplay. So naturally the singled out button on the side where the thumb would usually be reseted would be where the player presses reactively to jump, it also makes it less physically demanding as no reaching needs to be done. The LED's at the top are for feedback. The green to signify hitting or successful input makes sure the player knows what they're inputting is going through. This adds to the usage of the hit control, because since there is an acceleration threshold, they will know whether or not their swing of the controller was enough. The 3 red LEDs for lives are another feedback and convenient feedback for players. Instead of having to locate the small icon on the screen indicating lives, they instead can just look down at 3 simple lights to see if they are on and which. The last piece of feedback is the speaker/piezo. It would make sounds for when the player attempts to hit, gets a successful hit, collects vegetable or gets hit. It adds to the feedback and ensuring the player knows whats happening to them but also their impact on the game world. The controller is meant to be held like typical controllers with a clawed grip without any extension or reaching (aside from start and select), so it has fillets on the edges to ease on the physical strain it may have on the player's hands, especially when doing relatively large physical motions. The controller is bisected into 2 parts, top and bottom half. The bottom would house the arduino controller as a hub where it would recieve and send jumper wires, as well as fastener continuation. The top half has solts for a joystick, 3 buttons and a lot of fastener hole entries. The top side of the controller has openings for the LEDS but also for the arduino's cable. The placement of the LEDS and cable at the top removes the blocking that would happen if it were anywhere else.
