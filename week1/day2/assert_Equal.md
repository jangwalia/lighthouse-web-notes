### Tips
Tried to built-in way and implement our own custom assertEqual function to help us test our code.
First Created Lotide directory inside week 1 folder and  created assertEqual.js File
created a function to check the assertion for the input values
``` javascript
const sum = function(a, b) { 
  return a + b;
}

// TEST CODE
console.assert(sum(1, 2) === 3);
console.assert(sum(1, 20) === 3); // bad / incorrect assertion, and we see it fail!

```

added emojis to make code look little more expressive..!!!
``` javascript
const assertEqual = function(actual,expected) {
  if (actual === expected) {
    console.log(`😂 Assertion Passed :${actual} === ${expected}`);
  } else {
    console.log(`💀 Assertion Failed :${actual} !== ${expected}`);
  }
};
assertEqual('Lighthouse Labs','Bootcamp');
assertEqual(1,1);
assertEqual('Hello','Hello');
assertEqual(12,21);
```
In the ende commited and push the changes to the Repo created of the same name : Lotide
