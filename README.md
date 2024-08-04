<h1><p align="center">DARKSTAR BADGE</p></h1>

<p align="center">
~A User Guide~
</p>

-----
<p align="center">
A Lockheed Martin Aeronautics Cyber Range (ACR) project.<br>
Join us on <a href="https://discord.gg/sgUe73dNS8">discord</a><br><br>
<img src="images/badgeSpoiler.gif" width="350" height="200" border="10"/>
</p>

> Disclaimer
>> [!NOTE]
>> Everything about this badge was made using open-source and public information.
>>
>> The protocols were invented specifically for this badge, despite concepts being based on real protocols.
>>
>> This badge is for fun and educational purposes :smile:
-----
<h2><p align="center">Overall Badge Purpose</p></h2>

<h4><p align="center"> ENGAGE in Next Gen Badge Dominace and take-out the opposition using the latest in BLE and IR smart weapons!</p></h4>


<h3>
<p align="center">
Checkout the Global Scoreboard at <a href="http://airplanes.lol">airplanes.lol</a>
</p>
</h3>

-----
## Basics
> Guides are boring, just go use the badge!

##### Updating
- To update badge, simply reset, or from main screen press left and right at same time.<br>
Youll need to be connected to 'DefCon-Open' wifi.

### Buttons
- There are 4 (four) buttons on the top. <br>
These act like a d-pad, and the bar under the arrow indicates 'UP'<br>

- From the main menu, the Up, Down, and Right buttons are used to enter different sub-menus:<br>
Up button: Settings<br>
Right button: PHM<br>
Down button: Lethal Interrogate<br><br>

- On most screens:<br>
Up and Down will scroll through options.<br>
Right will select or run an action.<br>
Left is backspace/back.
### LEDS
The RGB LEDs are arranged in 2 sections:<br>

| LED    | State | Description |
| :----------: | :----------: | :----------: |
| Front | Green | Targetting another badge, can shoot   |
| Front  | Red  | Lethal State, can be shot    |
| Main   | RGB   | Change Passive setting in Settings     |
| Main    | RED Breathe    | Happens while Dead      |


The LEDs next to the power switch have two functions:<br>
- Blue LED: Indicates that the badge is charging <br>
- Red LED: Indicates the badge is powered on<br>
### Display
- 1.47" IPS 320x172 8 pin SPI
### IR RX
> Don't cover these! That's no fun.

- There are 2 (two) IR recievers. They receive IR :smile:
IR is used to shoot nearby badges that you are targetting.
### IR TX
- There is 1 (one) IR LED at the front of the badge which is used to shoot other badges.
### BATTERY
- The badge is powered by a 3.7v lithium 1000 mah 503450 with a 1.25mm JST connector. Charging is done via the USB-C port on the side of the badge. When charging is complete, the blue LED next to the power switch will turn off.
### BUZZER
- Yep its a buzzer, it makes sound.
### LIVERY
<table>
<tr>
<td width="33%">
Lockheed logo<br>
</td>
<td width="33%">
ACR Team logo<br>
</td>
<td width="33%">
The unofficial team logo<br>
</td>
</tr>

<tr>
<td>
<p align="center">
<img src="images/LM_logo_white.png" border="10"/>
</p>
</td>


<td>
<p align="center">
<img src="images/ACR_Logo_Full.png" border="10"/>
</p>
</td>
<td>
<p align="center">
<img src="images/Derpy_Remastered.png" border="10"/>
</p>
</td>
</tr>

<tr>
<td width="33%">
Skunkworks Skunk<br>
</td>
<td width="33%">
Defcon32 Theme slogan<br>
</td>
<td width="33%">
Darkstar Inspired Details<br>
</td>
</tr>

<td>
<p align="center">
<img src="images/skunk.jpg" border="10"/>
</p>
</td>
<td>
<p align="center">
<img src="images/dc32-logo.webp"border="10"/>
</p>
</td>

<td>
<p align="center">
<img src="images/darkstar_orig.webp" border="10"/>
</p>
</td>
</tr>
</table>

-----
## ESP32
- The microcontroller of the badge is an ESP32-S3-Wroom-1 containing 16MB of Flash, 8MB of RAM, and a built-in PCB antenna. The microcontroller can communicate with other badges using BLE and talks to the battle space manager over Wi-Fi.

### GPIO Layout

:smirk:

<img src="images/meter.jpeg" width="200" height="200" border="10"/>

-----
## Advanced stuff

| Feature    | :white_check_mark: / :x: | 
| :---------: | :----------: |
| OTA Updates | :white_check_mark: |
| Encryption    | :white_check_mark: | 

-----
## Beyond Defcon32
- Need to do some configuring,<br>
Then flash whatever you want :)<br>
- Write some new functionality, and share it on Socials! <br>

Keep an eye out for next years badge!


## Suggestions?
This is our first badge.<br> There will be bugs.<br> Please be kind and help us make the experience amazing for everyone by reaching out on [discord](https://discord.gg/sgUe73dNS8)
