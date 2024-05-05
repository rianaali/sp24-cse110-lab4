1. "3" is printed. this is because i was declared with var and var has function scope and ignores code blocks. Also i = 3 breaks the loop, so it will have that value.
2. "150" is printed. this is because discountedPrice was declared with var and var has function scope regardless of code block. the last value in the loop of discountedPrice was updated to was 150.
3. "150" is printed. this is because finalPrice was declared with var and var has function scope regardless of code block. the last value in the loop of finalPrice was updated to was 150 (it's just discountedPrice rounded).
4. The function returns the list discounted = [50, 100, 150]. The function simply takes the prices of the original list (100, 200, 300), discounts them by 0.5, rounds them, and adds them to the list discount to return them. All variables are declared with var and properly handled in their function scope, so the function works properly with no errors.
5. The code will cause an error. the line tries to print i, which was declared using let. let has block scope and i was declared in the line 6 in the for loop which is outside the block of line 12.
6. The code will cause an error. the line tries to print discountedPrice, which was declared using let. let has block scope and discountedPrice was declared in the line 7 inside the for loop and outside the block of line 13.
7. "150" is printed. finalPrice was declared using let and has function scope, and it was declared on line 4 inside the same code block/scope of line 14. 150 is the latest value of finalPrice in the for loop.
8. The function returns the list discounted = [50, 100, 150]. The function simply takes the prices of the original list (100, 200, 300), discounts them by 0.5, rounds them, and adds them to the list discount to return them. All variables are declared with let and properly assigned/referenced in their blocked scope, so the function works properly with no errors.
10. The code will cause an error. the line tries to print i, which was declared using let. let has block scope and i was declared in the line 6 in the for loop which is outside the block of line 11.
11. the line with print "3". length is declared with const and is assigned with the length of the prices list passed in (which is 3). this never changes and the variable is never reassigned as it should be.
12. The function still returns the list discounted = [50, 100, 150]. the discounted list was declared with const, but the values can still be modified under this. it simply defined a constant reference to the array, do it can not be reassigned to a different array but the values can be muted. So the function works similar as above, discounting all the prices of the original list by 0.5 and returns the list discount. No const variables are reassigned improperly and the function works with no errors.
13.
    A. '32'. 2 maps to '2' concatenated to '3'
    B. 1. '3' maps to 3 subtracted to 2
    C. 3. null maps to 0 added to 3
    D. '3null'. null maps to 'null' concatenated to '3'
    E. 4. true maps to 1 added to 3.
    F. 0. false maps to 0 and null maps to 0, and they are added together.
    G. '3undefined'. undefined maps to 'undefined' concatendated to '3'.
    H. NaN. undefined maps to 'undefined'. but the subtraction - operation is only for numeric operations, and is not defined for strings. so Nan is returned.  

14.
A. true. '2' maps to 2, and 2 > 1 is true.
B. false. '2' maps to 2 and '12' maps to 12, and 2 < 12 is false.
C. true. '2' maps to 2 and 2 equal to 2 is true.
D. false. no type changes with ===, so 2 equal to '2' is not true.
E. false. true maps to 1 and 1 does not equal 2.
F. true. Boolean(2) converts 2 to true since it is a truthy value. so true equal true returns true.

15. == evaluate equality with possible type conversions that exist in Javascript. === will also apply equality, but will not apply any type converstions.
    
