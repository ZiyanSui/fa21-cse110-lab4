# Part2 Answer

1. Line 12 prints "3". Because the prices.length is 3, the prices contains 100, 200, 300, and when i reaches 3 the for loop stops. Using var to declare variable, the scope is global, so everywhere can reach the variable declared by var.
2. Line 13 prints "150". Because for the final for loop, prices[2] is 300, and 300*(1-0.5) = 150. Using var to declare variable, the scope is global, so everywhere can reach the variable declared by var.
3. Line 14 prints "150". Because for the final for loop, discountedPrice is 150, so the result of Math.round(150 * 100) / 100 is 150 as well. Using var to declare variable, the scope is global, so everywhere can reach the variable declared by var.
4. Return an array that contains three discounted prices 50, 100, 150.
5. Return a referenceError: i is not defined. Because variables declared by let only have scope limited the the bracket, when trying to print out i, i can't be found because i only exists within the for loop.
6. Return a referenceError: discountedPrice is not defined. Because variables declared by let only have scope limited the the bracket, when trying to print out discountedPrice, it can't be found because discountedPrice only exists within the for loop as well.
7. Line 14 prints 150. Because finalPrice has scope for the whole function, when trying to print finalPrice, it can be found and the result is 300 * (1-0.5) = 150.
8. Return an array that contains three discounted prices 50, 100, 150. Because every for loop pushes the finalPrice into the discounted array and discounted scope is for the whole function.
9. Line 11 return a ReferenceError: i is not defined. Because i only exists within the for loop, after the for loop, it would be destroyed. Thus, the print statement can't find the i variable.
10. Line 12 prints 3. Because when length was declared by const, and assigned by prices.length, the value can't be changed. We know the length of the array prices is 3, so length is always 3. For the scope, const makes the scope include the whole funciton.
11.  Return an array that contains three discounted prices 50, 100, 150. The const only makes the discounted array can't be reassigned, so it can't be equal to another new array. However, because it only defines a constant reference to an array, we can still change the elements of a constant array.
12.  A: student.name\ B: student["Grad Year"]\ C: student.greeting()\ D: student["Favorite Teacher"].name\ E: student.courseLoad[0]
13.  A: 32, 2 is converted to string.\ B: 1, 3 is converted to number\ C: 3, null becomes 0\ D: 3null, null becomes string\ E: 4, true becomes number 1\ F: 0, false and null both becomes number 1\ G: 3undefined, undefined becomes string\ H: NaN, not a number
14.  A: true, 2 becomes number\ B: false, ASCII value of 2 is bigger\ C: true, '2' becomes number\ D: false, strict comparison gives false for different type comparison\ E: false, true becomes number 1 and is not equal to 2\ F: true, boolean(2) becomes 1 and is equal to true
15.  "===" is strict equality check, if two objects are differnt type, the result would be false. "==" is non-strict check, so even though two items are different types, they can still be compared by automatic type conversion
16. Print out 21, 45, ,5, 2
17. The result is returning a new array containing [2, 4, 6]. Because in the for loop, the new empty array pushes doSomething(array[i]) every time, and 1 * 2 = 2, 2 * 2 = 4, 3 * 2 = 6. Thus, after the for loop, the new array has 2, 4, 6, and then the function ends.
18. In part2-question18.js
19. 1, 4, 3, 2