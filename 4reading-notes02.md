1. # Describe (in plain English) what Array.map() does?
 
- The map() method in JavaScript creates an array by calling a specific function on each element present in the parent array. It is a non-mutating method, which means it does not change what it is working on. Generally map() method is used to iterate over an array and calling function on every element of array. It sort of hops from one element to the next doing the same function to each element, in order. src:https://www.geeksforgeeks.org/javascript-array-map-method/#:~:text=The%20map()%20method%20in,on%20every%20element%20of%20array.

2. # Describe (in plain English) what Array.reduce() does 
- The reduce() method executes a user-supplied “reducer” callback function on each element of the array, passing in the return value from the calculation on the preceding element. The final result of running the reducer across all elements of the array is a single value, so it makes every value in the array subtracted by the end return value of the previous value. Pretty cool. src:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce

3. # Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
# With normal Promise .then() syntax
 request
   .post('/api/pet')
   .send({ name: 'Manny', species: 'cat' })
   .set('X-API-Key', 'foobar')
   .set('Accept', 'application/json')
   .then(res => {
      alert('yay got ' + JSON.stringify(res.body));
   });
     
  # Again with async / await syntax
const superagent = require('superagent');

const NUM_RETRIES = 3;

test();

async function test() {
  let i;
  for (i = 0; i < NUM_RETRIES; ++i) {
    try {
      await superagent.get('http://google.com/this-throws-an-error');
      break;
    } catch(err) {}
  }
  console.log(i); // 3
}
    * src. :https://thecodebarbarian.com/common-async-await-design-patterns-in-node.js.html
4. # Explain promises as though you were mentoring a Code 301 level student: in an asynch/await function a promise is like a delayed execution of a function.

5. # Are all callback functions considered to be Asynchronous? Why or Why Not? 
I do not know yet and am finding differing opinions on the subject

[Back](README.md)