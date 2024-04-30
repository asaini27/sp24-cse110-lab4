1. Line no 12 will print 3, this is because the value of 'i' will get incremented from the for loop. Since the for loop runs uptil the length of price we get 'i' as 3.
    
2. This would print 150, this is because of the last iteration of the fpr loop which gives us 150 and then we find that value.
   
3. This will also give us the value 150. Again from the for loop we see the final value assigned to 'finalPrice' from the final iteration is 150. 
   
4. The given function will return an array with the values, [50,100,150]. This is because for the given call the function first reduced the original price by 50% and rounding does not the values we get therefore the array [50,100,150] will be returned. 
   
5. ReferenceError: i is not defined. This is because of using 'let' after which the 'i' is no longer accessible after the for loop. 
   
6. ReferenceError: discountedPrice is not defined. This is again because of defing the variable using let. In line 13 we are trying to access it outside its block scope therefore we get an error.
   
7. This prints 150. This is because the variable is defined not in the for loop and has a scope for the full function. 
   
8. The given function will return an array with the values, [50,100,150]. This is because for the given call the function first reduced the original price by 50% and rounding does not the values we get therefore the array [50,100,150] will be returned.
   
9.  ReferenceError: i is not defined. Since our variable is declared with 'let' it does not have block scope after the for loop. 
    
10. This prints out 3. This is because the length of our prices array is 3. 
    
11. We get this array: [ 50, 100, 150 ]. This is because our function populates the the array named 'discounted' with the discount added to the original prices. 
    
12. A = student.name;<br>
    B = student['Grad Year'];<br>
    C = student.greeting();<br>
    D = student['Favorite Teacher'].name;<br>
    E = student.courseLoad[0];<br>

13. A = "32", this is because javascript would perform string concatenation cause of '+'here since '3' is a string here. <br>
    B = 1, javascript would convert the result to a number because of the presence of '-'<br>
    C = 3, null is treated as 0<br>
    D = "3null", this is because of string concatenation taking place here.<br>
    E = 4 , true is treated as 1<br>
    F = 0 , false is treated as 0, and null is also treated as 0<br>
    G = "3undefined", this is because string concatenation takes place here agan. <br>
    H = NaN , undefined involved with '-' would always result in NaN<br>

14. A = 'true', '2' gets converted to a number before comparison<br>
    B = 'false' , this is lexicographical<br>
    C = 'true' , cause both have the same type after '2' is converted to a number<br>
    D = 'false'  , Checks both value and type, number and string are not the same type<br>
    E = 'false'  , does not follow type correction as true is 1<br>
    F = 'true' , since Boolean(2) has a value of true <br>

15. '==', checks if values compared are of same type before conversion, if not then convert them to the same tyoe and then compares. 
    '===', this does not perform the type conversion part and straight up compares the value as well as the type. 

16. In separate file

17. The result is [ 2, 4, 6 ]. Here we have the array: [1 ,2 ,3 ] getting passed and then in our function it is being sent to the num function which multiplies them by 2 resulting in the array: [ 2, 4, 6 ]. 
    
18. In separate file
    
19. The code prints:<br>
    1 <br>
    4 <br>
    3 <br>
    2 <br>
    The first line prints 2. Then due to set timeout line 5 gets executed printing 4. 3 after that, because the setTimeout with 0 milliseconds still defers the function until the current call stack is clear. 2 last, after a 1-second delay, as specified by its setTimeout

