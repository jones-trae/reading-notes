Reading 03
* React Docs - lists and keys
1. What does .map() return?An array that is doubled in value
2. If I want to loop through an array and display each value in JSX, how do I do that in React? Use curly braces, use map, and return an <li> element for each item
3. Each list item needs a unique __key__.
4. What is the purpose of a key?identifies elements in an array, tells js what has changed
* The Spread Operator (…)
1. What is the spread operator? Expands an utterable object into the list of arr into arguments..?
2. List 4 things that the spread operator can do. Find the largest number in an array, spreads an array, copies an array, combines arrays.
3. Give an example of using the spread operator to combine two arrays.

const arr1 = [‘1’, ’2’, ‘3’]
const arr2 = [‘4’, ’5,’ ‘6’]
const arr3 = […arr1,…arr2]

1. Give an example of using the spread operator to add a new item to an array.
2. const newI = [‘1’, ‘2’, ‘3’]
3. const newI2 = [ ‘4’, ‘5’, …newI]
4. Give an example of using the spread operator to combine two objects into one.
const objectOne = {hello: "🤪"}	
	const objectTwo = {world: "🐻"}
	const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
	console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
	const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
	objectFour.laugh() // 😂😂😂😂😂
(Cred dr. Derek Austin)
 
Videos
* How to Pass Functions Between Components
1. In the video, what is the first step that the developer does to pass functions between components?create the function in the state you wish to change and pass in an object
2. In your own words, what does the increment function do? Takes an item from an array, loops through it and modifies it via map etc
3. How can you pass a method from a parent component into a child component? No clue so far
4. How does the child component invoke a method that was passed to it from a parent component? pass the prop from the state you want to alter to another child object (this.props.increment, ex) pass it to the child object with a name, or a ref etc.  and call it 

## Things I want to know more about
Bootstrap. How to use it etc.


[Back](README.md)