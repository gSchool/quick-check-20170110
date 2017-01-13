# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
function multiply(x) {
  return x * y
}
```

## Explain each of the below versins of writing functions

For each, answer:
- Is this ES5 or ES6?
- Is the function anonymous?
- How do you call the function?

### First

```js
function add(x, y) {
  return x + y
}
```
es5
no
add(arg, arg2);

### Second

```js
var add = function (x, y) {
  return x + y
}
```

es5
Yes. I think it's a named anonymous function. Which is a dumb thing to say.
add(arg, arg2);

### Third

```js
var add = (x, y) => {
  return x + y
}
```

es6
Ditto above.
add(arg, arg2);

### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

es5
No
obj.add(arg, arg2);

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

es5
Yes
obj.add(arg, arg2);

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

es6
Yes
obj.add(arg, arg2);

## What does the following code output to the console?

```js
var i = 0
for ( console.log('Bob'); (console.log('Curly') === undefined); console('Mo') ) { 
  console.log(++i)
  if (i >= 2)
    break
}
console.log(i)
```
```
Bob
Curly
1
Mo
Curly
2
2
```
for loops first evaluate the first statement in the parens, then the second. If the second is true code executes inside the block. After the block is complete, if it doesn't execute a break, the iterator, or third statement in the parens following the `for` keyword runs. From here on out the first statement in the parens is skipped. The second statement in the parens is run. If it evaluates to true, the code in the block executes. When the for loop breaks, code after the for loop is run.

