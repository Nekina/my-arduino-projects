<style>
.chibi-img {
    display: flex;
    justify-content: center;
    align-items: center }
.text1 {
    margin-left: 5px;
    margin-top: 0;
    font-size: 25px; }
.small-icon {
    display: flex;
    justify-content: left;
    align-items: center }
.text2 {
    margin-left: 5px;
    margin-top: 0px;
    font-size: 10px; 
    margin-right: 30px;}
</style>

<div class="chibi-img">
    <div class="image">
        <img src="Chibi Photo No BG.png" width="600">
    </div>
    <div class="text1">
        <p>Hi! I'm <strong>Joshua Aniken Acusta</strong>, an 
Electronics Engineer and programming enthusiast, and I just made this 
simple site to display my Arduino projects🙂 You can also reach me on my 
socials below for any questions, suggestions, or just something to talk 
about. Hope you enjoy!😁</p>
    </div>
</div>
<br>
<div class="small-icon">
    <div class="image">
        <img src="FB Logo No BG.png" height="20px">
    </div>
    <div class="text2">
        <p> <a href="https://www.facebook.com/joshuacusta/">Facebook</a></p>
    </div>
    <div class="image">
        <img src="LinkedIN Logo No BG.png" height="20px">
    </div>
    <div class="text2">
        <p> <a href="https://www.linkedin.com/in/joshua-aniken-acusta-225854167/">LinkedIn</a></p>
    </div>
    <div class="image">
        <img src="Tinkercad Logo.png" height="20px">
    </div>
    <div class="text2">
        <p> <a href="https://www.tinkercad.com/users/5gdFlX2YV2B-joshua-aniken-acusta">Tinkercad</a></p>
    </div>
</div>
<br><br>

# Specialized 2-Digit Counter

This 2-digit counter uses the blinking effect, a technique on LED displays 
to turn the LEDs ON and OFF at a rate fast enough that the naked eye can 
only recognize the ON state. This technique allows the Arduino 
microcontroller to execute commands in between the "delays" which enables 
it to detect the user's button input almost instantaneously.

### Main Features

- Can show numbers from 00 to 99
- Stops count-up at 23, and stops count-down at 64 (based on the last 4 
digits of my ID number - 2364)
- Can change counting mode (up or down) ay any time by toggling the
buttons
- Counting speed is approximately 2x

### Simulation

I used <a href="https://www.tinkercad.com/">Tinkercad</a> to simulate each of my projects first before assembling 
it. You can also check out each project's schematic diagram, materials 
used, and Arduino script on the embedded simulation below.  

<iframe width="1000" height="600" src="https://www.tinkercad.com/embed/1wnJTy0ySJD?editbtn=1" frameborder="20" marginwidth="0" marginheight="0" scrolling="no"></iframe>  

*Note: Use **LEFT** button for count-down and **RIGHT** button for count-
up.*
<br><br>

# 16x2 LCD Display with Scroll-Up/Down

This is a simple application of LCD Displays using Arduino to generate a 
physics word problem with some controls.

### Main Features

- Has Scroll up/down buttons
- Can Replay (move back to top) once bottom is reached and scroll-down 
button is pressed

### Simulation

<iframe width="1000" height="600" src="https://www.tinkercad.com/embed/1spXzD81hc9?editbtn=1" frameborder="20" marginwidth="0" marginheight="0" scrolling="no"></iframe>

*Note: Use **LEFT** button for scroll-down and **RIGHT** button for 
scroll-up.*
<br><br>

# Running Lights using AVR Programming

In this project, the patterns are programmed via AVR programming (i.e. 
by directly controlling the registers of the ATmega328p microcontroller 
chip) and timer overflow interrupts. A kind-of non-conventional way to 
do it but definitely worth for practice!

### Main Features

- Repeats each pattern 3 times, then loops back to the first pattern
- Only 10 digital pins and 2 analog pins (for GND) are used to control 
each of the 20 LEDs separately and without the blinking effect
- More memory-efficient than traditional Arduino programming (i.e. such 
as using `digitalRead()` and `digitalWrite()` functions)

### Simulation

Just sit back and watch!😁

<iframe width="1000" height="600" src="https://www.tinkercad.com/embed/hnWyz2fGR3u?editbtn=1" frameborder="20" marginwidth="0" marginheight="0" scrolling="no"></iframe>

*Note: If you're planning to make this project in real life, ensure that 
the resistors have high enough resistance values to prevent overcurrent 
on the digital/analog pins (at most 20mA as specified)*
<br><br>

# Reverse Light Intensity Scale

This may look like a scale in the simulation but I actually put the LEDs 
on a small hand-made cotton tree. Basically, the darker the environment 
gets, the more LEDs are turned ON, as shown in the video below.

<video height="500" width="500" controls>
    <source src="LED Tree.mp4">
</video>

### Simulation

<iframe width="1000" height="600" src="https://www.tinkercad.com/embed/38S0IrgjxhJ?editbtn=1" frameborder="20" marginwidth="0" marginheight="0" scrolling="no"></iframe>

*Note: To change the light intensity, click the LDR, then a horizontal 
scale will appear. Move the knob along the scale to adjust brightness.*
<br><br>

* * *

##### More to come soon...