__*Logical operators*__  
== is equal to - compares numbers, strings or booleans to see if they are true.  
*=== strict equal to - this operator compares two values to check that both the data type and value are the same.  
!= is not equal to - compares two values to see if they are not the same  
!== strict not equal to - checks both data type and value and if they are not the same  

Other types that are obvious:   
*>  
*<  
*>=  
*<=  

__*Loop*__  
Loops check a condition. If returned true, the code block will run. It is checked again, if it still returns true, it will run again. If it ever returns false, it will not run.  

There are three common types of loops:  
For  - runs a specific number of times based on the condition  
While  - if you don't know how many times it should run  
Do While  - Like above, but will run anything inside {} if it continues as false.  

__*Counter loop(loop counters)*__  
A for loop uses a counter as a condition. 

for (var i = 0; i < 10; i++) {  
    document.write(i);  
}  

Initialization - creates a variable and set it to 0. This is commonly called i and acts as the counter.  
Condition - The loop should continue to run until the counter reaches a specific number (10 in the example above).  
Update - Every time the loop has run the statements in the curcly braces, it adds one to the counter (i++).

