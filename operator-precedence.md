## Operator Precedence in Javascript

* Which operator function gets called first when there are two operators on the same line?
* Operator Functions are called in the order of precedense

Operator associativity how to call operator functions with the same precedence?
Left to right or right to left?
  
See the following example: 

  ```javascript
  var a = 4 + 3 * 5;
  // 19 
  
  ```
See:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence

For a full prescendence table.

```javascript
var a = 2, b = 3, c = 4;

a = b = c

console.log(a);
console.log(b);
console.log(c);

// 4
// 4
// 4
```
Why 4? Because addition has a right to left associativity. This means 

So

```javascript
b = c 

// 4 

// then

a = b

//4 

```

Not all operators have right to left associativty. Review the abovementioned tables for certain
operators


