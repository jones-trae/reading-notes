##Reading Notes 10
* Understanding the JavaScript Call Stack
* 
1. What is a ‘call’? A function invocation
2. How many ‘calls’ can happen at once? 1?
3. What does LIFO mean?Last in first out
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();



1. What causes a Stack Overflow?Calls repeating infinitely until the stack reaches its call limit

* JavaScript error messages
1. What is a ‘refrence error’? When something is undefined or declared
2. What is a ‘syntax error’? Annoying: punctuation in the wrong spot
3. What is a ‘range error’? Invalid length in an object ie an array too short
4. What is a ‘type error’? Incompatible data being worked on
5. What is a breakpoint? Location of an ‘unexpected feature’
6. What does the word ‘debugger’ do in your code? Puts in a breakpoint.

[Back](README.md)