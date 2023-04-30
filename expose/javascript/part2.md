1. The code will print `3` because that is the value of `i` after the `for` loop is run on an array of length 3. Since `i` is declared as type `var`, we are able to access it outside the loop.
2. The code will print `150` because that is the value of `discountedPrice` of the last element in `prices`. Since `discountedPrice` is declared as type `var`, we are able to access it outside the loop.
3. The code will print `150` because that is the value of `finalPrice` after rounding `discountedPrice`. Since `finalPrice` is declared as type `var`, we are able to access it.
4. The function will return an array of `[50, 100, 150]`. This is because all the variables are of type `var`, so there is no issue with accessing them. The `for` loop takes each element in the `prices` array and applies the `discount` to it based on the operations inside the loop.
5. The code produces an error because `i` is only defined inside the `for` loop. Thus, it cannot be called from outside the loop.
6. The code produces an error because `discountedPrice` is only defined inside the `for` loop. Thus, it cannot be called from outside the loop.
7. The code will print `150` because that is the value of `discountedPrice` of the last element in `prices`. Since `discountedPrice` is declared in the same block as line 14, we are able to access it.
8. The function will return an array of `[50, 100, 150]`. 
9. The code produces an error because `i` is only defined inside the `for` loop. Thus, it cannot be called from outside the loop.
10. The code will print `3` because that is the value assigned to `length` in line 4.
11. The function will return an array of `[50, 100, 150]`.  This is because in each iteration of the `for` loop, the value of `discountedPrice` is reinitialized. The `discounted` array is not reassigned, but updated with the `push` funtion.
12. \
    A. `student.name` \
    B. `student['Grad Year']` \
    C. `student.greeting()` \
    D. `student['Favorite Teacher'].name`\
    E. `student.courseLoad[0]` 
13. \
    A. `'3' + 2 = '32'` because integers map to their exact string representation. \
    B. `'3' - 2 = 1` because strings map to their exact integer representations. \
    C. `3 + null = 3` because `null` maps to `0`. \
    D. `'3' + null = '3null'` because `null` maps to the string `'null'`. \
    E. `true + 3 = 4` because `true` maps to `1`. \
    F. `false + null = 0` because both `false` and `null` map to `0` for arithmetic operations. \
    G. `'3' + undefined - '3undefined` because `undefined` maps to a string for string concatenation.  \
    H. `'3' - undefined = NaN` because `undefined` maps to `NaN` for arithmetic operations and any operation involving `NaN` results in `NaN`.
14. \
    A. `'2' > 1` outputs `true` because strings map to their exact integer representations. \
    B. `'2' < '12'` outputs `false` because the first character of each string is compared and `'2' < '1'` is `false`. \
    C. `2 == '2'` outputs `true` because strings map to their exact integer representations.\
    D. `2 === '2'` outputs `false` because the strict equality operator `===` checks the equality without type conversion. \
    E. `true == 2 ` outputs `false` because `true` maps to `1`. \
    F. `true === Boolean(2)`outputs `true` because the `Boolean` constructor evaluates all non-falsy values to `true`.
15. The `==` operator will convert different types before performing a comparison. However, `===` checks the equality without type conversion.
16. [part2-question16.js](part2-question16.js)
17. The code will produce `[2, 4, 6]`. First, an empty array is initialized on line 2. Then, for every element in `array`, we perform `doSomething()` to it, and push it into `newArr`. In our case, `doSomething()` multiplies a number by two, so our final output should be an array with all its elements doubled.
18. [part2-question18.js](part2-question18.js)
19.  
``` 
1 
4
3
2
```


