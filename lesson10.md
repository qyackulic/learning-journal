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
}`

Three main types of loop counters:
1. Initialization.
2. Condition. 
3. Update. 
