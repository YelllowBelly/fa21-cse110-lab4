1. It will log the number 12 because i will keep incrementing in the loop until it is not < 3.
   Since 3 is not less than 3, it exits the loop with value of 3.

2. It will log 150 since discountedPrice will have the discounted price of the last
   element of the prices array, which is 300 * (1-.5) = 150.

3. It will also log 150 since finalPrice will contain the value of the last element's
   final price before it exited the for loop, which is equal to the discounted price in this case.

4. This function will contain an array with the following elements: [50,100,150]. It is essentially
    the discounted price of each corresponding elemet from prices since in the for loop
    we are calculateing each element's discounted price and then pushing to the dicsounted array.

5. This will return an error because we are using let for i, which means it can only
    be accessed within the forloop. We are are trying to use i outside, so it is not defined.

6. This will also return an error since we use let when intializing the discountedPrice variable.
    It can only be accessed within the forloop.

7. This will log 150. We use let in the function (not in any loops or conditionals), so the variable has scope within the whole function and will behave similarly in THIS scenario to when we used var.
   
8. This will return an array containing the elemnts [50,100,150]. Since we used let at the 
    beginning of the function, it's scope is accesses the whole function and will behave similarly
    to var in THIS scenario.

9. There will be an error since i is not defined outside of the scope of the forloop since it was initialized with let.

10. This will simply log the number 3 since length is defined as a constant equal to the lenght of the prices array.
    
11. This will output an array with elements [50,100,150]. Although discounted is declared as a const,
     we can still add elements to it because js documentation only states that we cannot change a const 
     through reassignment, and a const can't be redeclared. Adding to the array does not violate any
     of these rules, which is why the end result is the result we got.

12. A: student.name;
    B: student["Grad Year"];
    C. student.greeting();
    D. student['Favorite Teacher']['name'];
    E. student['courseLoad'][0];

13. A. 32; since 3 is a string it will perform string concatenation with 3 and 2
    B. 1; We cannot string concatenate since there is a minus so the 3 string will be converted to an int and perform arithmetic
    C. 3; null will be counted as a zero resulting in 3 + 0
    D. 3null; Again, 3 is a string so this will perform string concatenation
    E. 4; the true will count as a 1 since it is not a string, resulting in 1 + 3
    F. 0; false will be converted to 0 and since it is not a string, null also will be converted to 0 (0 + 0)
    G. 3undefined; since 3 is a string, string concatenation
    H. NaN; since 3 is a string but we cannot concatenate an undefined or perform arithmetic with an undefined, we get a NaN value (number cannot be parsed)

14. A. true; this will convert string to the numeric value when comparing
    B. false; compares alphanumerically and since 1 is less than 2 in this case '12' would be less than '2'
    C. true; this interprets the string to the numerical value
    D. false; the === checks for both the same value AND the same type
    E. false; true will be converted to a 1 and 1 != 2
    F. true; since both sides now contain the same value AND type (Boolean(2) is equivalent to Boolean(true))

15. == compares two variables while ignoring the datatype while === compares value and datatype.

17. This function will result in a new array with double values since we are using a function doSomething which doubles the values
    of the original array and pushes them into the newArr

19. This will output the numbers on new lines in the following order: 1, 4, 3, 2. Since 1 and 4 have no timeouts, while 3 has a timeout of 0 and 2 has a timeout of 1 second.

