<style>
img {
  max-width: 100%;
  max-height:100%; }
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
    margin-top: 10px;
    font-size: 10px; 
    margin-right: 30px;}
</style>

<div class="chibi-img">
    <div class="image">
        <img src="Chibi Photo No BG.png" height="280px">
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

I used Tinkercad to simulate my project first before assembling it. You 
can also check out the project's schematic diagram, materials used, and 
Arduino script on the simulation below.  
*Note: Use **LEFT** button for count-down and **RIGHT** button for count-
up.*
<!--
<iframe width="1000" height="600" src="https://www.tinkercad.com/embed/1wnJTy0ySJD?editbtn=1" frameborder="20" marginwidth="0" marginheight="0" scrolling="no"></iframe>  
-->
<br>
<br>

# 16x2 LCD Display with Scroll-Up/Down
