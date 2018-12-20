# xmas-tree
DIY desktop sized christmas tree from stacked ws2812 RGB LED rings driven by a Digispark.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=AHWQvgLXzgE
" target="_blank"><img src="http://img.youtube.com/vi/AHWQvgLXzgE/0.jpg" 
alt="DIY XMAS TREE" width="560" height="315" border="10" /></a>

## Items Needed:
1. WS2812 RGB LED Rings, 1 - 8 - 12 - 16 - 24 - 32 LED´s per ring, total of 93 WS2812 Led´s.
2. Digispark ATtiny85 USB Development Board
3. Enameled magnet wire, I used 0,71mm / AWG21

## HowTo:

1. Solder WS2812 led rings power and ground with magnet wire, tree shaped.
2. Solder every output with the input from the next ring.
3. Programm Digistump using Arduino IDE.
4. Connect power and ground to Digispark.
5. Connect the first input to Digispark pin 1.
6. Connect Digispark to powersource.
7. Enjoy!


If you build this tree, i would like to hear from it! Also code-updates are welcome! New Tree-Patterns are always good :-)

This Christmas decoration is simple to build, great for Arduino and DIY beginners, but also more experienced people can have lots of fun with hacking the code!

It can be considered OSHW, i mean, how can you not recreate this easily?

## Updated
This fork is updated to use 6 rings - 93 LEDs.
