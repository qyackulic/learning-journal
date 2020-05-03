## Operators and Loops 

Duckett discusses **Operators**, in this brief overview, from pages 150-151, 156, and 157.

Operator Sign | Meaning
------------ | ------------- 
`==` | Equal To
`!=` | Is not equal to 
`===` | Strict equal to
`!==` | Strict not equal to
`>` | Greater than
`>=` | Greater than or equal to
`<` | Less than
`<=` | Less than or equal to

__Boolean__ = true or false. A boolean value may result from a function.  EIther the function is *true*, ie it is valid, or it is *false*, ie it is invalid.  

*Logical Operators*
`&&` means "logical and".  It tests more than one condition.
`||` means "logical or".  It tests _at least_ one condition.
`!` means "logical not". This operator takes as single __Boolean__ value and inverts it.  
 
And **loops** from pages 170-173 and 176.  

Three main types of *loops*:
1. For -- "If you need to run code a specific number of times, use a for loop.  In a for loop, the condition is usally a counter whihc is used to tell how many times the loop should run."
2. While -- "If you do know know how many times the code should run, you can use a while loop.  Here the condition can be something other than a ounter, and the code will continue to loop for _as long as_ the condition is true."
3. Do While -- "The do...while loop is very similar to the while loop, but has one key difference: it will always run the statements inside teh curly braces at least once, even if the condition is evaluated to __false__".

**EXAMPLE**
`for (var i=0; i<10;i++){
    document.write(i);
}`  --> the loop will run until the condition is no longer true; when it is 10 or higher.  

Three main types of **loop counters**, which "instruct the code to run a specified number of times."  For example:
1. Initialization creates "a variable and set it to be 0.  THis variable is commonly called i, and it *acts as the counter*. 
- `var i = 0` --> 
`var i; 
for (i=0;i<10;i++){
    //code goes here
}`
2. Condition: "the loop should continue to run until the counter reaches a specified number." 
- `i < 10;`
`var rounds = 3;
i < (rounds)
3. Update: "every time the looopo has run the statements in the curly braces, it adds on to the counter"
- `i++`
- or, alternatively, the programmer can decrement, by writing `i--`

_While loop_ **example**
- (Duckett, 176):
`
var i=1;  // set counter to 1
var msg=''; // message
// store 5 times table in a variable
while (i<10){
    msg += i + ' x 5 = ' + (i * 5) + '<br />;
    i++;
}
document.getElementById('answer').innerHTML=msg;
`
- the above code will produce the times tables of 5 from 1 to 9. 
