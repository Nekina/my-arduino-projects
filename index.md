# Specialized 2-Digit Counter

This 2-digit counter uses the blinking effect, a technique on LED displays to turn the LEDs ON and OFF  
at a rate fast enough that the naked eye can only recognize the ON state. This technique allows the  
Arduino microcontroller to execute commands in between the "delays" which enables it to detect the  
user's button input almost instantaneously.

## Main Features

- [x] Can show numbers from 00 to 99
- [x] Stops count-up at 23, and stops count-down at 64 (based on the last 4 digits of my ID number - 2364)
- [x] Can change counting mode (up or down) ay any time by toggling the buttons
- [x] Counting speed is approximately 2x

## Simulation

I used Tinkercad to simulate my project first before assembling it. You can also check out the project's  
schematic diagram, materials used, and Arduino script on the simulation below.

<iframe width="1000" height="600" src="https://www.tinkercad.com/embed/1wnJTy0ySJD?editbtn=1" frameborder="20" marginwidth="0" marginheight="0" scrolling="no"></iframe>
