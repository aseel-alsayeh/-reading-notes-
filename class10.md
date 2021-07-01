### The JavaScript Call Stack 

- What is a ‘call’?
With the call() method, you can write a method that can be used on different objects.

- How many ‘calls’ can happen at once? 
one

- What does LIFO mean?
Last In, First Out,it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![image](https://miro.medium.com/max/437/1*rLV0q6if8Drx1PbrncybXw.png)

- What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.