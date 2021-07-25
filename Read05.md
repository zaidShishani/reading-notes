# Intro to Operators and Loops
 
## summary
 
I will be listing some logical operators that will help us run our loop focusing on IF statements and for statements.
 
| Operator  | What it means |
| ------------- | ------------- |
| Equal (==)  | Returns true if the operands are equal.  |
| Not equal (!=)  | Returns true if the operands are equal. |
| Strict equal (===)  | Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. |
| Strict not equal (!==) | Returns true if the operands are of the same type but not equal, or are of different types. |
| Greater than (>)  | Returns true if the left operand is greater than the right operand. |
| Greater than or equal (>=) | Returns true if the left operand is greater than or equal to the right operand. |
| Less than (<)  | Returns true if the left operand is less than the right operand. |
| Less than or equal (<=) | Returns true if the left operand is less than or equal to the right operand. |
 
how we will use the listed operators to run our if and for loops
 
**if example**
 
if (score >= 90)
  grade = 'A';
 
now every time a score is inputed over 90 the system gonna automatically give us grade A.
 
**for loop example**
 
for (let step = 0; step < 5; step++) {
 console.log('Walking east one step');
}
 
the system will log only for 4 times since it starts for 0 til the number lower than 5 if we used the <= it would run til 5
 
we can also use if in our for loops
 
**example**
 
for (let i = 0; i < a.length; i++) {
 if (a[i] === theValue) {
   break;
 }
}
 
our for loop gonna check the values of a til it's either run through it all and stop or if a value is found the if statement will break and stop the for loop.
 
there is still many different ways to do loops like while ,do while but this is what we got for now. :D
