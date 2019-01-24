Practice

Let’s write some functions! Write these in the script tag of a skeleton html file. If you’ve forgotten how to set it up, review the instructions from fundamentals 1.

For now just write each function and test the output with console.log.

* Write a function called add7 that takes one number and returns that number + 7.
* Write a function called multiply that takes 2 numbers and returns their product.
* Write a function called capitalize that takes a string and returns that string with only the first letter capitalized. Make sure that it can take strings that are lowercase, UPPERCASE or BoTh.
* Write a function called lastLetter that takes a string and returns the very last letter of that string:
lastLetter("abcd") should return "d"

**My Code:**
```javascript

//add7
function add7(n){
  return n + 7
}

console.log(add7(20))

//multiply
function multiply(n,n1){
  return n * n1
}

console.log(multiply(2,3))

//capitalize
function capitalize(str){
  return str.charAt(0).toUpperCase() + str.slice(1)
}

console.log(capitalize("be cool"))

//lastLetter
function lastLetter(str) {
  return str.charAt(str.length-1)
}

console.log(lastLetter("suck"))
```
