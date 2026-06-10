# ultra-sonic-sensor-basketball

#The Idea
Hello, for this project I was inspired by the basketball shooting games at arcades. So with that I took upon myself the challenge to build it and create a 3D model to play with.

#Tools Used:
- Arduino IDE
- ESP32
- Breadboards
- M-M jumper wires
- 4 Digit & segment display 4 pin verison
- Ultra Sonic sensor
- Bambu Labs Studio
- Blender
- PLA Filament
- Bambu Labs P1S

#The Process:
I realized after understanding the basics of how this game worked on the inside that I could build it the parts lying in my box of things. Firstly, I grabbed a breadboard because I did not feel like soldering at all and my soldering kinda sucks. I grabbed all the nescarry components which are listed in tools used. I then looked for a schematic of the display and sensor I was using. 
##The Issue
The breadboard I was using was a large one and conviently the esp32 has 30 pins and an even amount of spacing between the right and left side of those pins which means it would not fit on the breadboard for my to have a row sticking out for the jumper wires to go onto. After expeirmenting with different ways to use only one side and learning that basically any of the GPIO pins can be used an CLK which is clock and DIO which is data I used D26 and D27 and respectively wiring power to 5V and GND. Then I wired the display to another wacky combination of pins. 
insert image of it 
So in the end that didn't work, BUT I did not let that stop me. I found these mini breadboards I had bought from a future project I'm planning and put them together so I can now fit the ESP32 and the other components on the board. I also resoldered the pins on the display to be more neater. 
insert image of new design
