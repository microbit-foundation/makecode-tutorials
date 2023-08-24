# Step counter

## @showdialog

In this project, you turn your micro:bit into a step counter.

## 
You don't need ``||basic: forever||`` so let's drop it back into the toolbox (the middle section).

## 
First we need to make a variable.  A variable is container for storing data to use at a later time.

In the Variables category, click on ``||variables: make a variable||`` and call it "steps".

## 
Some new blocks appear.  Find  ``||variables: set steps to 0||`` block and put it inside ``||basic: on start||``. 

This sets the number stored in the ‘steps’ variable to 0 when our program starts.  

## 
Next find the ``||input: onShake||`` block (in the Input category) and drag it into the code window.

## 
Next find the ``||variables: change steps by 1||`` block (in the Variables category) and put it inside ``||input: onShake||``. 

This will increase the number stored in the ‘steps’ variable by 1 every time you shake or move the micro:bit. 

## 
Now let's show the number of steps taken.  

So, find ``||basic: show number||`` (in Basic) and put it underneath ``||variables: change steps by 1||``. 

## 
We need to show the number inside our ‘steps’ variable.  

So, find the ``||variables: steps||`` variable (in Variables) and drop it onto of the 0 in ``||basic: show number||``.

## 
Let’s test your code in the micro:bit on-screen simulator.  The simulator now has a shake button for testing. 

Press the shake button and the number shown on your micro:bit should increase. 

## 
Now download your code onto your micro:bit.  Press the download button and follow the instructions.

When you shake your micro:bit, the number shown on the micro:bit should increase.

## @showdialog

Congratulations - you have made a micro:bit step counter!
