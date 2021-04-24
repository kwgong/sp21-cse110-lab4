# Part 1a
## var declaration
1. What is printed by line 9? If the code returns an error, explain why.  
   The line printed is: 
   ``values added: 20``
   
2. What is printed by line 13? If the code returns an error, explain why.   
   The line printed is: 
   ``final result: 20``
   
## let declaration   
1. What is printed by line 9? If the code returns an error, explain why.  
   The line printed is: 
   ``values added: 20``
   
2. What is printed by line 13? If the code returns an error, explain why.  
   The line would cause an error as the scope of let is only within the if block.

## const declaration
1. What is printed by line 9? If the code returns an error, explain why.  
   The line printed is: 
   ``values added: 0``
   
2. What is printed by line 13? If the code returns an error, explain why.   
   The line printed is: 
   ``final result: 0``
   
# Part 1b
1. At line 12, ``3`` would be printed out.
2. At line 13, ``150`` would be printed out. 
3. At line 14, ``150`` would be printed out.
4. The function would return the array ``discounted`` with the elements ``[50, 100, 150]``. This array is made from finding the discounted price of the ith element 
   in the ``prices`` array, then it being mutliplied by 100 and divided by 100 to get the final price. This final price is the ith element in ``discounted``.   
5. This would cause an error as the variable ``i`` is declared with ``let`` which limits the variable's scope to the for-loop block.
6. This would also cause an error as the variable ``discountedPrice`` is declared with ``let`` which limits the variable's scope to be in the for-loop block.
7. At line 14, ``150`` would be printed as the variable's scope is the function of ``discountPrices``.
8. This function would return an array of ``[50, 100, 150]`` which comes from calculing the discountedPrice then finalPrice and updating the discounted array with the new value.
9. Line 11 would cause an error as the declaration of ``i`` used ``let`` which limits the scope of the variable to the for-loop block.
10. At line 12, ``3`` would be printed out because that is the length of the ``prices`` array.
11. The function would return an array of ``[50, 100, 150]`` which comes from updating the discount array with the discountedPrice calculated with the discount.

12. Data Types  
    a. Access the name property with ``student.name``.  
    b. Access the Grad Year property with ``student['Grad Year']``.  
    c. Call the greeting function with ``student.greeting()``.  
    d. Access the name in Favorite Teacher with ``student['Favorite Teacher'].name``.  
    e. Access the first index in the array with ``student.courseLoad[0]``.   

## Basic Operators & Type Conversion
13. 
    a. The output is ``32`` which is due to the `2` in the equation converting to a string to be concatenated with the `3`.  
    b. The output is `1` which is due to the `3` in the equation converting to a numeric type to have `2` subtracted from.  
    c. The output is `3` which is due to the `null` converting to `0` to be added to `3`.  
    d. The output is `3null` which is due to the `null` converting to a string to be concatenated with the `3`.  
    e. The output is `4` which is due to the `true` converting to the numeric value of `1` to be added to `3`.  
    f. The output is `0` which is due to `false` and `null` converting to their numeric equivalents, `0` and `0`.  
    g. The output is `3undefined` which is due to `undefined` converting to a string to be concatenated with the `3`.  
    h. The output is `NaN` which is do to `undefined` converting to the numeric equivalent which is `NaN`.   

14. 
    a. The output is ``true`` because `2` is converted to the numeric equivalence to be compared with `1`.  
    b. The output is ``false`` because the `2` and `12` is converted to their numeric equivalence to be compared with each other.  
    c. The output is `true` because the string `2` is converted to the numeric equivalence to be compared with `2`.  
    d. The output is `false` because the strict equality operator checks equivalence without type conversion.  
    e. The output is `false` because the `true` is converted to the numeric equivalence of `1` to be compared with `2`.  
    f. The output is `true` because the `Boolean(2)` returns `true`.   
    
15. The ``==`` operator checks for equivalence with type conversions while the ``===`` operator checks for equivalence without type conversion.  
17. The resulting array would be ``[2, 4, 6]`` which is from modifyArray calling doSomething within the for-loop as a callback function with the arguments being the value at ``array[i]``. This is due to the callback function allowing another function to be called before the conclusion of another.  
19. The output is:  
    ``1``  
    ``4``  
    ``3``  
    ``2``  


