1. <br> 3, because it returns the value of i where the for loop ended.
2. <br> 150, because it will return the last value of the 'prices' variable and its applied discount, so the person would get -$150 off the oringal purchase.
3. <br> 150, because it will return the final price of the last value of 'prices' so 300-150 = 150.
4. <br> [ 50, 100, 150 ],This will return an array of all items in 'prices' with the discount provided applied to them.
5. <br>  You would get an erorr because all the variables were intialized with let and the memory is not carried over outside of its use, so since the print statement is outside of the for loop it does not have access to the value stored in i.
6. <br>  An error would would occur in the same way as the last question, line 13 would throw an error since dicountedPrice was intialized with let and it was inside of a for loop where line 13 does not have access to.
7. <br>  150, This happens because finalPrice was intialized outside of the for loop so the memory was able to be saved and can be refrenced to all throughout the program.
8. <br>  [ 50, 100, 150 ], This is returned because it is the array of all items with their discounted prices and the way it works is by having values being pushed to an array that can be refrenced to throughout the whole function.
9. <br>  This would throw an error because the variable i was intialized within the for loop and the memory cannot be accessed outside of the loop.
10. <br>  3, this happens because the length variable was instialized at the begining of the function and can be refrenced throughout the function.
11. <br> [ 50, 100, 150 ], this happens because all discounted prices were pushed to the discountedPrices array and although it is a const, as long as the data types are the same we are free to add or remove more numbers.
12. <br> 
  a) student.name <br> 
  b) student['Grad Year'] <br> 
  c) student.greeting() <br> 
  d) student['Favorite Teacher'].name <br> 
  e) student.courseLoad[0] <br> 
13. <br> 
  a) <br>  '32', This happens because the '+' symbol assumes we are trying to add 2 to ur string so it absorbs the number into the string <br>
  b)  <br> 1, This happens because the '-' symbol converts 3 to number so then it performs the operation 3-2.<br> 
  c)  <br>  3, This happens because null is essentially treated as 0 so its 3 + 0<br> 
  d)  <br> '3null', This happens because the '+' symbol is like concate so it converts null into a string and therefore adds it to the end of 3. <br> 
  e)  <br> 4, This happens because true has the value of 1 and when it is added together with integer 1 it comes out to 4<br> 
  f)  <br> 0, False and null are both treated as 0s when being refered to integer numbers so 0 + 0 is 0<br> 
  g)  <br> '3undefined', This happens because undefined is turned into a string because of '+' converting it as it trying to attach it to the '3' string.<br> 
  h)  <br> NaN, any arthemtic operations with the symbol "-" will make undefined change to NaN and with NaN in any of these operations will always result to NaN.<br> 
<br> 14. <br> 
  a)  <br> true, When comparing strings and numbers together the string is turned into a number and therefore this expression was able to become true as 2 > 1. <br> 
  b)  <br> false, js goes in lexiographical order so since it sees that the first number in '12' is 1 it determines that it is lower than 2 and should come before '2'. <br> 
  c)  <br> true, This is true because alike a when doing comaprsions between strings and numbers, the strings turn into numbers and 2 = 2 is true <br> 
  d) <br>  false, This is false because since it is utilizing the "===" which means that it has to be strictly the same so, since one is an integer and the other is a string they are not the same although their contents are the same and that. <br> 
  e) <br>  false, This is because a boolean is converted to a number and true has the integer 1 assigned to it so 1 == 2 is false. <br> 
  f) <br>  true, This is true because since were utlizing the '===' here when they are being compared to one another they are looking at the specific type here so since they are both booleans it equates to true. <br> 
<br> 15. <br> For '==' symbol this can allow many different things for example if given '2' == 2 it would equate to true because when using this operand it changes the string to an integer and allows these two values to be compared to one another. When utilzing '===' this operand is more strict since it makes sure that to two data types are of the same datatype from there can be compared to one another to equate to the proper boolean evaulation.  <br>

<br> 17. <br> The function returns [2,4,6]. I got this because when tracing through the code. Lines 2-3 are first lines to be execeuted after the function call of *modifyArray*. Once that occurs when getting to line 4 this line utilizes "callback" which allows for a function be called within another function. So when callback(array[i]) gets executed it calls the doSomething(num) function intialized in line 9 to be called with the parameter being the array provided to the modifyArray function. Once the doSomething function returns a value it is then pushed to the newArr array. This process occurs up until the for loops stops iterating.  <br>

<br> 19. <br> 1 4 3 2 (in their respective own lines). <br>
