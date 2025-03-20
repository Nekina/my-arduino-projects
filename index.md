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
    align-items: left }
.text2 {
    margin-left: 5px;
    margin-top: 5;
    font-size: 15px; }
</style>

<br>
<div class="chibi-img">
  <img src="Chibi Photo No BG.png" height="280px">
  <p class="text1">Hi! I'm <strong>Joshua Aniken Acusta</strong>, an 
Electronics Engineer and programming enthusiast, and I just made this 
simple site to display my Arduino projects🙂 You can also reach me on my 
socials below for any questions, suggestions, or just something to talk 
about. Hope you enjoy!😁</p>
</div>
<br>
<div class="small-icon">
    <img src="FB Logo No BG.png" height="20px">
    <p class="text2"> <a href="https://www.facebook.com/joshuacusta/">joshuacusta</a></p>
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
