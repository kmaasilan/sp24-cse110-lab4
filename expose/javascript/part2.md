1. 3 will be printed to the console because i is declared with var, so i has function scope. Thus, i can be accessed outside of the for loop without errors.
2. 150 will be printed to the console because discountedPrice is declared with var, so discountedPrice has function scope. Thus, discountedPrice can be accessed outside of the for loop without errors.
3. 150 will be printed to the console because finalPrice is declared with var, so finalPrice has function scope. Thus, finalPrice can be accessed outside of the for loop without errors.
4. This function will return [50, 100, 150] because discounted is an array of all discounted prices, and discounted is declared with var and accessed with its function scope at line 16.
5. The code returns an error because i is declared with let, so i is out of scope at line 12.
6. The code returns an error because discountedPrice is declared with let, so discountedPrice is out of scope at line 13.
7. 150 will be printed to the console because finalPrice is declared with let and is accessed within its block scope at line 14.
8. This function will return [50, 100, 150] because discounted is an array of all discounted prices, and discounted is declared with let and accessed within its block scope at line 16.
9. The code returns an error because i is declared with let, so i is out of scope at line 11.
10. 3 will be printed to the console because length is declared with const and is accessed within its block scope at line 12. Additionally, length is never reassigned.
11. This function will return [50, 100, 150] because discounted is an array of all discounted prices, and discounted is declared with const and accessed within its block scope at line 14. Additionally, discounted is never reassigned.
12. - A. student.name
    - B. student['Grad Year']
    - C. student.greeting()
    - D. student['Favorite Teacher'].name
    - E. student.courseLoad[0]
13.
    - A. '32' as the 2 is converted to a string and concatenated to the '3'
    - B. 1 as the 3 is converted to an int and has 2 subtracted from it
    - C. 3 as the null is converted to the int 0 and added to 3
    - D. '3null' as the null is converted to a string and concatenated to the '3'
    - E. 4 as the true is converted into the int 1 and added to the 3
    - F. 0 as both the false and the null are converted to the int 0 and added to one another
    - G. '3undefined' as the undefined is converted to a string and concatenated to the 3
    - H. NaN as the '3' is converted to the int 3, but undefined becomes NaN since it has no int representation. Ultimately, we end up with NaN.
14.
    - A. true as the '2' is converted to the int 2. Since 2 is greater than 1, we end up with true.
    - B. false because 1 is less than 2 and javascript compares strings based on lexigraphical order. Since '12' is less than '2', we end up with false 
    - C. true as the '2' is converted to the int 2. Since 2 equals 2, we end up with true.
    - D. false as 2 and '2' are different types 
    - E. false as the true is converted to the int 1. Since 1 is not eqal to 2, we end up with false
    - F. true as Boolean(2) is true since 2 is non-zero. Since true and Boolean(2) have the same type, we compare their values and see that true equals true. Thus, this comparison evaluates to true.
15. The === operator ensures both operands are the same type, whereas the == operator does not.
16. In part2-question16.js
17. The result would be [2,4,6]. I arrived at this result because of the following ... 
    - i. modifyArray loops through the input array.
    - ii. Each element of the input array is passed to the input function.
    - iii. The output of the input function is appended to newArr.
    - iiii. Since, in this case, the input function is doSomething, each element of the input array is multiplied by 2.
    - iiiii. The index of the callback's output in newArr is equal to the index of the callback's input in array because we call callback and append its output to newArr as we loop through array. \
Thus, [1,2,3] becomes [2,4,6].
18. In part2-question18.js
29. 1 \
    4 \
    3 \
    2
