# Introduction
For this task, you will create a functional calculator that should operate as instructed below:

## Part One

### On your script declare these 4 variables:
``` javascript
var term1 = null;
var term2 = null;
var operation = null;
var decimal = -1;
```
* Display value in screen1 and screen2 after an operation
* Take the value on screen2 and put it to term1
* If the operation button is pressed it should take the value in screen2 and place it in term2, do the math and put the answer on term1
* Adding the operation passed with spaces to screen2, clear the screen for the next number. clear term2, save the current operation

## Part Two
### After doing the math - 
* If the operation (+) is pressed, the calc should add term1 and term2
* If the operation (-) is pressed, the calc should minus term1 and term2
* If the operation (*) is pressed, the calc should multiply term1 and term2
* If the operation (/) is pressed, the calc should divide term1 and term2 rounding the answer to 0 decimal places or rounding the answer to 2 decimal place. return the answer to whatever called the function.
* if CE is pressed it should clear everything on screen2, term1 should be = 0 (ready for the next number) should be blank

## Part Three
* Declare a var = 'whatever is on screen1'
* Convert the display text into an array, the temp to split after each space. remove the last item of the array, join the array back into a string. set the display text and clear whatever is on screen2
* Should be able to change the color theme of the calculator
* All these functinalities are for a standard calculator, now create a scientific calculator.
* After creating a scientific calculator convert the Javascript functionalities of the calculator to Python functionalities.
