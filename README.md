# Explain the Midterm


### capitalizeSentences
1. Make a new empty string that will hold our result
2. Go through each position(a.k.a. index) in our paragraph from left to right, all the way until the end.
3. If the character two positions to the left of the current index is a period or the current index is equal to zero...
4. Add the current index's character to the result string uppercased. 
5. Otherwise...
6. Add it to the result string lowercased.
7. Continue on to the next index until at the end of the paragraph.
8. When complete, show(a.k.a. return) the result.


### isValidPassword
1. The function will check if as password is valid if it meets two specific criteria.
2. It will first check if the password's length is less than 12 characters. If yes, then it will return an answer of false. If not, true.
3. Next, it will check if the password contains any spaces. If yes, it will return an answer of false. 
4. If both criteria are met with false returns, the final answer returned will be true. 


### makeHalfSquares
1. Make a new empty array which will hold our result. An array is like a container.
2. The current array and its data will be evaluated left to right.
3. The first number(which is located at the first index) will be multiplied by its value(a.k.a squared) and then divided by two.
4. That total will be added to the new array created in Step 1. 
5. The next number will be evaluated similarly and will continue until the last number in the array.
6. Once complete, the new array will be returned(shown).


### countAs
1. This function will count how many grades in an array(container) are greater than or equal to the number 90.
2. The count will start at zero. 
3. When the first number(from left to right in the array) is taken, it will be evaluated if it is greater than or equal to the number 90. 
4. If it is, the count will go from zero to one.
5. The next number will be evaluated similarly and will continue until the last number in the array.
6. Once the all numbers have been evaluated, the total count of numbers greater than or equal to 90 will be returned(shown).


### deleteMiddleLetters
1. Create an empty string which will hold our result.
2. In order to delete the middle letter, we will need to calculate the length of the string and divide by two. A function may be used to round down numbers to the nearest integer. This calculated number is the index of the omitted character. 
3. If other index's characters are:
   1.  an odd index number and not the same index value of the character in Step 2 or,
   2.  an even index number, not the same index value of the character in Step 2 nor the character located at one index to the left of the character in Step 2
   then character will be added to the new string.


### lastIndexOfSpace

1. To find the last index(position) of a ' '(space) in a string, we must loop in the opposite direction of the string(a.k.a. evaluate the string starting from the end and working backwards.)
2. Starting with that first letter/index(but last letter in the string), if it's value is equal to a ' '(space), return the index. If not, continue on to the next letter/index.
3. If there are no spaces, return the number -1.


### hyphenateName
1. Create an empty string which will hold our result.
2. We must find the last ' '(space) of a name so that we know where to place the hyphen.
3. Using a special method called .lastIndexOf, we will be able to find the last occurrence of a space. 
4. Starting from the beginning of the string, evaluate each index's value and add it to the new string.
5. Once you get to the last space in the string, insert a hyphen in its place to the new string. 
6. Continue evaluating the remaining index letters until the end of the string.
7. Return/show the new string. 