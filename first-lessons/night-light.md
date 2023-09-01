# Night light 

## @showdialog 
In this project, you’ll turn your micro:bit into a night light that switches on automatically when it gets dark. 

## 
You don't need the ``||basic: on start||`` block, so drop it back into the toolbox (the middle section). 

## 
Look in the Logic category and find the ``||logic: if true then else||`` block. 

Drop it inside the ``||basic: forever||`` block. 

## 
Find the ``||logic: 0 < 0||`` comparison block (in the Logic category). 

Put this on top of the word ``||logic: true||`` in the ``||logic: if true then else||`` block. 

## 
Find the ``||input: light level||`` block (in the Input category) and drop it on top of the first 0. 

## 
Change the second 0 to 100. 

You may need to change this number later depending on the light levels in your room. 

## 
Find ``||basic: show leds||`` (in Basic category) and put it under ``||logic: if... then||``. 

Click on every square in the ``||basic: show leds||`` block to light every LED when the light level is below 100. 

## 
Now, find ``||basic: clear screen||`` (in the Basic category) and put it under ``||logic: else||``. 

## 
Test your code in the micro:bit on-screen simulator. Drag the yellow line up and down in the circle at the top left. 

You should see the lights switch on when the light level is below 100 and switch off when it's above 100. 

## 
Now download your code onto your micro:bit. Press the download button and follow the instructions. 

## 
Test your night light by covering your micro:bit to see if the LED lights switch on. 

If not, you may need to adjust the light level number in your code and test again. 
## @showdialog 
Congratulations - you have made a micro:bit night light! 
