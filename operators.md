### Javascript Operators

** A special function that is written different in the syntax.

* Take two parameters and return one result

```javascript
var a = 3 + 4
console.log(a);
// => 7
```
So how does the ```+``` operator work? 

```+``` and all other operators like it, are actually functions.

```javascript
function +(a,b) {
  return // add the two #s
}
```

Why does this function not run like a standard JS function?

For example:

```javascript
+(3,4);
```

Javascript uses __Infix notation__ (instead of prefix notation for standard functions.

```javascript

3 + 4;

```

