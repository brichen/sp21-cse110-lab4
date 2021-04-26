# Part 1: Intro to Javascript

## Part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. The code in line 13 causes an error because the 'result' variable was defined using the "let" keyword, but in a different block, so it is not in its scope. 
5. The program will not reach line 9 because line 7 will cause an error for attempting to reassign a const variable.
6. The program will not reach line 13 because line 7 will cause an error for attempting to reassign a const variable.

## Part 1b
1. The console will print out '3' because the for loop ends when 'i' is incremented to the value 3. 'i' is also defined in line 12's scope, so there are no errors.
2. The console will print '150' because the last reassignment of 'discountedPrice' happened at 'i' = 2, which resulted in the calculation 300 * (1 - 0.5) = 150.
3. '150' will again be printed out, as the calculation done by "Math.round(discountedPrice * 100) / 100" will not actually round anything. 
4. The function will return the array: [50, 100, 150]. This is because the function took the original array [100, 200, 300] and applied a 50% discount to all the prices.
5. Line 12 will cause an error because 'i' was not defined in its scope.
6. Line 13 will cause an error because 'discountedPrice' was not defined in its scope.
7. '150' is printed out because 'finalPrice' was defined in line 14's scope at the beginning of the function.
8. The function will return [50, 100, 150]; every variable was accessed in its right scope that it was defined, causing no errors. The calculations were all able to be done correctly.
9. Line 11 will cause an error because 'i' was defined in the scope of the for loop, which is out of the scope of line 11.
10. Line 12 will print '3' because that is the length of the input 'prices' array.
11. The function will return [50, 100, 150]; The function is able to run properly and applied a 50% discount to [100, 200, 300].
12. Object
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. Arithmetic
    1.  '32'; the number 2 is mapped to a string and concatenated with '3'
    2.  1; the string '3' is mapped to an integer and subtracts 2
    3.  3; null is mapped to the integer 0. 3 + 0 = 3.
    4.  '3null'; null is mapped to the string 'null' and concatenated with '3'.
    5.  4; true is mapped to the integer 1 and added to 3, resulting in 4.
    6.  0; false and null are both mapped to the integer 0 and added, resulting in 0.
    7.  '3undefined'; undefined is mapped to the string 'undefined' and concatenated with the string '3'
    8.  NaN; '3' and undefined are mapped to integers, but the resulting calculation is NaN, or "not a number".
14. Comparison
    1.  true; '2' is mapped to its integer, and 2 is greater than 1
    2.  false; the string '2' is not the same as the string '12'.
    3.  true; The values are converted to a like datatype, either integer or string. In either case, both will have the same value.
    4.  false; === is a stricter comparison operator that cares about datatypes. Since we are comparing an integer to a string, which are not the same, it will return false.
    5.  false; true is mapped to the integer 1, but 1 != 2, so it will return false.
    6.  true; Boolean(2) results in the boolean true, and true === true, as they have the same value and datatype.
15. Both compare two variables but '==' ignores datatypes, whereas '===' checks for datatypes and is a stricter comparison. For example, 1 == '1' would return true because the variables would be mapped to a common datatype, but 1 === '1' would return false because we are comparing a number to a string.
17. The modifyArray function will return the array [2, 4, 6]. The function takes in the input array, iterating through it and calling the 'doSomething' function on each index, which multiuplies the value in it by two. The modifyArray function then pushes the new value into the 'newArr' array that it defined and returns it after the for loop ends. Essentially, the modifyArray function given these parameters will take in the array and return a new array with all the values multiplied by two.
19. 1 4 3 2 