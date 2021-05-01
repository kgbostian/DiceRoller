# DiceRoller
Modified Bee's Dice Roller (https://andylawton.com/home/bee-dice-roller)

Uses standard dice notation: 1d4, 2d6, etc.


Integrated URL customization
--  dicehex - hexcode - sets the dice’s body colour. 

--  labelhex - hexcode - set’s the number’s colour. 

--  transparency - number 0-1 - set’s an opacity on the dice.

--  chromahex - hexcode - sets background colour

--  shadows - 0 or 1 - turns off dice shadows. 

--  noresult - no input- turns off the results text

--  roll- no input- immediately rolls on page load.

--  d - dice notation (see below) - set’s the starting dice
  
 Added URL customization:
--  scale - integer - scales the size of the dice
  
 example link: http://URL/?dicehex=4E1E78&labelchex=CC9EEC&chromahex=FBFF00&d=2d20&roll
 
  
  Running the dice roller:
  copy index.html, dice.css, dice.js, main.css, main.js, teal.js and /libs to your web server
  -- NOTE: /libs contains two files: cannon.min.js and three.min.js
  
