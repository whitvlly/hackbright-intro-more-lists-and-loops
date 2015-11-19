#Loops Exercises Part 1: Exploring Range
*Do the following exercises in the Python interpreter.*

## Explore `range`
*You do not need to type up answers to these.*

1. Type `range(5)` and press enter. What happens? 
2. Type `range(3.14)` and press enter. What happens? 
3. Type `range(-8)` and press enter. What happens? 
4. Type `range(0)` and press enter. What happens?
5. Type `range(1)` and press enter. What happens? 
6. Type `range(1,5)` and press enter. What happens?
  1. How is this different than `range(5)`?
7. Type ``range(5,1)`` and press enter. What happens?
8. Now type `range(5,1,-1)` and press enter. What happens?
  1. How is this different than `range(5,1)`?
9. Type `range(0,-5)` and press enter. What happens?
10. Type `range(-5,0)` and press enter. What happens?
  1. How is this different than `range(0,-5)`?
  2. How would you get the numbers from 0 down to -4? (Hint: look at #8)
11. Type `range(10)` and press enter. What happens?
12. Type `range(0,10)` and press enter. What happens?
13. Type `range(0,10,1)` and press enter. What happens?
14. Type `range(0,10,2)` and press enter. What happens?
15. Type `range(0,10,1+1)` and press enter. What happens?

## Describe how `range` works
*Please record your answers to these questions by using the edit button on GitHub.  
Make sure you have pushed your lists exercises before making any commits on GitHub, otherwise you will have to make a merge commit later.*

1. What does `range` do with a single argument?
  * returns all numbers, from 0 up to number. Ex: range(3) is 0,1,2
2. What do the arguments mean if there are 2?
  * one of arguments is the beginning number, and second - is the ending number, Ex: range(1,4) - start from 1, end with 3
3. What does the third argument mean?
  * the 3rd argument does the steps for that specific element Ex: (1,10,2) is 1,3,5,7,9
