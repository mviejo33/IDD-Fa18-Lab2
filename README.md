# Make a Digital Timer!
 
## Overview
For this assignment, you are going to 

A) [Solder your LCD panel](#part-a-solder-your-lcd-panel)

B) [Write text to an LCD Panel](#part-b-writing-to-the-lcd) 

c) [Using a time-based digital sensor!](#part-c-using-a-time-based-digital-sensor)

D) [Make your Arduino sing!](#part-d-make-your-arduino-sing)

E) [Make your own timer](#part-e-make-your-own-timer) 
 

## Part A. Solder your LCD panel

**Take a picture of your soldered panel and add it here!**

![Image of breadboard](https://github.com/mviejo33/IDD-Fa18-Lab2/blob/master/IMG_20180911_020013.jpg)

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?**

5V

**b. What voltage level do you need to power the display backlight?**

3.3V
   
**c. What was one mistake you made when wiring up the display? How did you fix it?**

I didn't connect the potentiometer pins correctly, I solved it by asking Oluseyi for help and making sure I understand how it works.

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?**
 
This one: lcd.print("hello, world!");
 
**e. Include a copy of your Lowly Multimeter code in your lab write-up.**

[Link to multimeter](//github.com/mviejo33/IDD-Fa18-Lab2/blob/master/multimeter.ino)

## Part C. Using a time-based digital sensor

**Upload a video of your working rotary encoder here.**

https://www.youtube.com/watch?v=CKnvD9ydb8g

## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**

Multiplying the values of the noteDurations by 2
int noteDurations[] = {
  4, 8, 8, 4, 4, 4, 4, 4
};
 
**b. What song is playing?**

Star Wars

## Part E. Make your own timer

**a. Make a short video showing how your timer works, and what happens when time is up!**

I did a game in which the player has to listen and see carefully, when they listen the beep sound, they have to look at the current number in the LCD screen and write it down, at the end the screen shows the correct numbers and the player can check if he/she got them right. It is started by spinning the encoder.

https://www.youtube.com/watch?v=0gggR6JxPaY

**b. Post a link to the completed lab report your class hub GitHub repo.**

![Link to lab hub](https://github.com/mviejo33/Interactive-Lab-Hub)
