1. Line 12 will print '3' because var i is function-scoped, so i can be accessed and its value is prices.length
2. Line 13 will print '150' because discountedPrice is function-scoped, and 300 * (1-0.5) = 150
3. Line 14 will print '150' because Math.round(150 * 100) / 100 = 150
4. This function will return [50, 100, 150], because discounted is an array where finalPrice is pushed onto it every for loop iteration
5. Line 12 will return an error because i is block-scoped because of the 'let'
6. Line 13 will return a ReferenceError because discountedPrice is defined with 'let' inside the for loop, so outside that block it is not accessible
7. Line 14 will print '150', which is the value of finalPrice after the for loop ends. Since finalPrice is defined before the for loop, it is scoped to the function, so the for loop can access and change its value.
8. It will return [50, 100, 150] because the for loop pushes the final price onto the discounted array through every iteration, and all the variables are accessible.
9. Line 11 will return a ReferenceError because i is not accessible since it is declared with 'let'
10. Line 12 will print '3' because length is a constant and prices.length = 3
11. This function will return [50, 100, 150] because inside the for loop the discounted price is pushed into the discounted array.
12. 
    1.  student.name
    2.  student['Grad Year']
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. 
    1.  '32' because the + with a string concatentaes the two elements as strings
    2.  1 because the - makes it numeric subtraction
    3.  3 because null is converted to 0
    4.  '3null' because the + is treated as string concatenation
    5.  4 because true is converted to a 1
    6.  0 because false and null both convert to 0
    7.  '3undefined' because the + is treated as string concatenation
    8.  NaN because '3' is converte to int 3, but undefined cannot be converted to an integer
14. 
    1.  True because '2' converts to integer 2, which is greater than 1
    2.  False because '12' is compared by character, and '2' is not less than '1'
    3.  True because == supports type conversion, '2' is converted to 2
    4.  False becasue 2 is not the same type as '2'
    5.  False because true converts to 1, which is not equal to 2
    6.  True because boolean(2) converts to 2
15. == allows for type conversion, but === is strict and doesn't allow type conversion before comparison.

   17\. The result will be newArr, which will contain [1, 4, 6]. The arry passed in is [1,2,3], and the for loop iterates through each element and calls the callback function, which is doSomething. The callback function will return that number multiplied by 2, and then the result will be pushed onto newArr.

   19\. Output will be 1, 4, 3, 2.