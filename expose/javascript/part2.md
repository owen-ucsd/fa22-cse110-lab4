# Part 2

1. the length of the prices array will be printed (in this case, `3`), since it is given function scope and ends the for loop with a value equal to that length
2. the final discounted price is printed (in this case, `150`),since it is given function scope and exits the for loop with that value
3. the final rounded discounted price is printed (in this case, `150`), since it is given function scope and exits the for loop with that value
4. an array of rounded discounted prices is returned (in this case, `[50, 100, 150]`), since the function computes each discounted price, adds them to an array, and returns that array
5. error, since `i` is not defined in that scope (it's only defined in the `for` loop)
6. error, since `discountedPrice` is not defined in that scope (it's only defined in the `for` loop)
7. the final rounded discounted price is printed (in this case, `150`), since it is exists in that scope and exits the for loop with that value
8. same as before: an array of rounded discounted prices (in this case, `[50, 100, 150]`), since the function computes each discounted price, adds them to an array, and returns that array
9. error, since `i` is not defined in that scope (it's only defined in the `for` loop)
10. the length of the prices array will be printed (in this case, `3`), since it exists in that scope and is never changed
11. same as before: an array of discounted prices (in this case, `[50, 100, 150]`), since the function computes each discounted price, adds them to an array, and returns that array
12. * A. `student.name`
    * B. `student['Grad Year']`
    * C. `student.greeting()`
    * D. `student['Favorite Teacher'].name`
    * E. `student.courseLoad[0]`
13. * A. `'32'`, since `2` maps to `'2'`
    * B. `1`, since `'3'` maps to `3`
    * C. `3`, since `null` maps to `0`
    * D. `'3null'`, since `null` maps to `'null'`
    * E. `4`, since `true` maps to `1`
    * F. `0`, since `false` and `null` map to `0`
    * G. `'3undefined'`, since `undefined` maps to `'undefined'`
    * H. `NaN`, since `undefined` has no integer mapping
14. * A. `true`, since `'2'` maps to `2` and is greater than `1`
    * B. `false`, since `'2'` comes after `'1'` (the first character of `'12'`)
    * C. `true`, since `'2'` maps to `2` and is equal to `2`
    * D. `false`, since the types are different
    * E. `false`, since `true` maps to `1` and is not equal to `2`
    * F. `true`, since `Boolean(2)` is strictly equal to `true`
15. `==` does type conversion when checking for equality, while `===` does not and checks for strict equality instead
16. see `part2-question16.js`
17. `[2, 4, 6]`, since `modifyArray` iterates through each value in the array (in this case, `[1, 2, 3]`), calls the `callback` function (`doSomething`, which doubles the value), adds the new value to a new array, and returns the new array
18. see `part2-question18.js`
19. `1` and `4` will be printed first (no delay), with `3` immediately after (delay of 0 ms), and finally `2` one second later (delay of 1000 ms)
