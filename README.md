# SwiftCart-Website

### 1) What is the difference between `null` and `undefined`?
Ans : `undefined` means something is not defined and `null` means it is totally empty. When we declare a variable but don't give it a value then javascript will give it a value of `undefined`. On the otherhand, `null` is empty value. We can assign `null` to a variable to tell that this variable is empty.

-

### 2) What is the use of the `map()` function in JavaScript? How is it different from `forEach()`?
Ans : `map()` function is used to transform every item in a array into a new array. It creates a brand new array means it return array. On the otherhand, `forEach()` function change the existing array and return `undefined`. `map()` is used when we need to change the array to new array and `forEach()` is used to doing something with the data.

-

### 3) What is the difference between `==` and `===`?
Ans : `==` is Loose Equaily. It's check if the value is matched or not. If the there data type is different but value is same it will return `true` like - `5 == '5'` is `true`. On the filp side the `===` is strict equality. It will check both value and data type. so `5 == '5'` will become `false` because one of them is `Number` and other is `String`.

-

### 4) What is the significance of `async`/`await` in fetching API data?
Ans: Long time ago the fetching data in javascript was problematic. Back then we uses long chains of `.then()`. But that was messy. Then the `async/await` appear to save the day. It imporve the readability and control flow also improve the error handling. 

-

### 5) Explain the concept of Scope in JavaScript (Global, Function, Block).
Ans : variable that is outside of any function or curly braces is global scope. it's means from anywhere we can get the variable. when we declare  a variable inside a function then that's the function scope, means variable declear in that scope only visible inside the function. And block scope is something inside a curly braces llke if statemets, for loops or while loops.
