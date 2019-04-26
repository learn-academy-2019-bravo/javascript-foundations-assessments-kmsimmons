# Javascript Foundations Assessments

### Without using Google answer the following:

1. List the data types in Javascript. Indicate which are primitives.
Primitives: string, boolean, number, undefined, null, Non Primitives: functions, arrays

2. What's the difference between =, ==, and === in JavaScript?
=== is the most specific (when used the values have to be an EXACT match).  == uses type coercion to compare values (77 == '77' will come back as true because it will convert to the same data type).  I believe the = can only be used with a bang operator (!=) to show 'not equal to.'

3. What is the difference between an array's index and length?
The index of an array starts counting the items in the array at '0', while the length counts the actual number of things in the array (starts at '1')

4. What are the three parts of a for loop?
The three parts of a 'for loop' are the indications of 1. The index where the loop starts. 2. The length of items you want to loop through. 3. How you want to move through the loop (i++ goes one item in an array at a time).

5. What is a function's declaration, argument, and call?
A function's declaration can also be thought of as the name of the function (function applePie).  The argument is the value that's being passed through the function (function applePie(arr)), where 'arr' is the argument.  The call is where we want to use the function, which is usually where we want to log the function itself.

6. What are the three main steps in saving work to github?
git add .
git commit -m "message describing the work"
git push

7. What is the terminal command to move directories?
cd will change the directory.

8. Do you have a suggestion for a Check In question?
What is your favorite alcoholic beverage (hopefully everyone could answer this one)?

9. What was your favorite topic this week?
It's hard to pick a favorite when they're all difficult, but I liked making the different types of cars using classes, super(), etc.

10. What was your "A-ha!" moment this week?
After the panel, I realized that I'm right where I need to be.

### Stretch: The following questions are potential interview questions. First, try to answer each question on your own then Google the answer to further your knowledge.

1. Look at this Javascript and try to predict, what will the browser's console show?

``` javascript
var text = 'outside'
function logIt(){
    console.log(text)
    var text = 'inside'
}

logIt()
```
Since the point that console.log(text) is called is before the var 'text' is redefined, I would think the browser's console would show 'outside.'

2. What is JSON? How does it relate to javascript objects?
JSON stands for JavaScript Object Notation.  It allows/helps us connect data in computer terms to more easily readable notation.

3. Describe a closure, what is it good for and how do you recognize one?
When your girlfriend breaks up with you, then you see her out the next day with another dude.  (I'm not sure in dev terms though and I ran out of time :( ...)
