1. The console will print `prices.length`, 3, since `i` is a `var` variable that exists outside the scope of the for loop.
2. The console will print the last discounted price in `prices`, 150, for the same reason as above.
3. The console will print the last *rounded* discounted price in `prices`, 150, for the same reason as above.
4. The function will return an array containing the values `[50, 100, 150]` since each discounted price was pushed to the array.
5. The function will throw an error because `i` is undefined in the scope.
6. The function will throw an error because `discountedPrice` is undefined in the scope.
7. The console will print the last *rounded* discounted price in `prices`, 150, since it is declared in the scope above the for loop.
8. The function will return an array containing the values `[50, 100, 150]` since each discounted price was pushed to the array which was declared in the scope.
9. The function will throw an error because `i` is undefined in the scope.
10. The console will print `length`, 3, since it was declared as the length of the prices array at the top of the funciton.
11. The function will return an array containing the values `[50, 100, 150]` since each discounted price was pushed to the array.
12. Given the above Object, write the notation for:
    1.  `student.name`
    2.  `student['Grad Year']`
    3.  `student.greeting()`
    4.  `student['Favorite Teacher'].name`
    5.  `student.courseLoad[0]`
13. Arithmetic
    1.  `'32'` Because the 2 is treated as a string to concatenate.
    2.  `1` Because the 3 is treated as an integer to subtract from.
    3.  `3` Because null is treated as a 0 to add.
    4.  `'3null'` Because `null` is treated as the string `'null'` to concatenate.
    5.  `4` Because the `true` is treated as a 1 to add.
    6.  `0` Because both are treated as 0s to add.
    7.  `'3undefined'` Because `undefined` is treated as the string `'undefined'` to concatenate.
    8.  `NaN` because `undefined` is treated as `NaN` to subtract.
14. Comparison
    1.  `true` Because `'2'` is treated like `2`
    2.  `false` Because `'2'` and `'12'` are treated like `2` and `12` respectively.
    3.  `true` Because they have the same value and the comparison is not strict.
    4.  `false` Because they are not identical and the comparison is strict.
    5.  `false` Because `true` is treated as 1
    6.  `true` Because the boolean conversion of nonzero ints is strictly equivalent to `true`
15. `==` is a non-strict equivalency, so types can be converted, and `===` is a strict equivalency and must be of the same type and value.
16. See [part2-question16.js](part2-question16.js)
17. The function creates a new array, and for the length of the input array, it calls back `doSomething` on each index of the input array. `doSomething` multiplies the value by 2, so the values pushed to `newArray` are `[2, 4, 6]` which is returned.
18. See [part2-question18.js](part2-question18.js)
19. The console will print 1, 4, 3, 2 because the actions without `setTimeout` will execute first regardless of wait time.