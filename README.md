# BB8
2/3 scale BB8 robot as seen in Star Wars: The Force Awakens. 

<img src = "images/BB8_screenshot.jpg" width = 650>

_Note: This project is still in progress._

There are two major parts:
1) The hamster ball with an Arduiono controlled buggy inside
2) The head with a Raspberry Pi control unit. The Raspberry Pi control is optional if you don't want an autonomous/smart bot.

Planned features for final BB8:
* Choice between joystick control or semi-autonomous motion
* Raspberry Pi with pi camera will detect human shapes and instruct bot to follow first one it sees
* Raspberry Pi will access a home assistant API and give real answers to questions. API output will be translated to morse code with pitch and frequency modulations to make it really sound like BB8.

## Parts List

### Parts for Base

* 13" Hamster Ball
<img src = "images/hamster_ball.jpg" width = 200>

* Arduino Uno
<img src = "images/DFRduino_uno.jpg" width = 200>

* 4 wheels and 2 DC motors
<img src = "images/wheel_and_motor.jpg" width = 200>

* L298N Motor driver board or similar
<img src = "images/L298N_board.jpg" width = 200>

* 9V Battery pack for 6 AA batteries
<img src = "images/battery_pack.jpg" width = 200>

* At least four small neodymium magnets
<img src = "images/magnets.jpg" width = 200>

### Parts for Head

* Raspberry Pi 3B+
<img src = "images/raspberry_pi_3Bplus.jpg" width = 200>

## Build steps

### Physical Build Steps

### Electronics Build Steps
I followed the intructions here: https://www.teachmemicro.com/use-l298n-motor-driver/

### Programming Steps
