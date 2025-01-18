Ques1:- Create a function fetchUserData that uses async/await to fetch data from a mock API (use https://jsonplaceholder.typicode.com/users) and logs the user names to the console.
Input: None (function fetches from the API).
Output:
User Names:
- Leanne Graham
- Ervin Howell
- Clementine Bauch
- Patricia Lebsack
...


Ques2: Create a chainPromises function that demonstrates promise chaining:
Start with a number.
Add 10 to the number in the first .then.
Multiply the number by 5 in the second .then.
Divide the number by 2 in the third .then.
Handle errors in a .catch block.

Input: Initial number: 10.
Output:
After addition: 20
After multiplication: 100
After division: 50


Ques3: Write a function counter that uses closures to create an incrementing counter:
const myCounter = counter();
myCounter.increment() increases the count.
myCounter.getValue() returns the current count.

Input:
const myCounter = counter();
myCounter.increment(); // Call 1
myCounter.increment(); // Call 2
console.log(myCounter.getValue());

Output:
2


Ques4: Create a function createMultiplier that takes a number n and returns a new function. The returned function takes another number m and multiplies it by n. Demonstrate the usage with different values of n.
Input:
const double = createMultiplier(2);
const triple = createMultiplier(3);
console.log(double(5));
console.log(triple(5));

Output:
10
15





