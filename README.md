# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x,) (
  x + y
)
```

function multiply(x,y) {
  return x+y;
}

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
ES5.
NO.
add(1,2).

### Second

```js
var add = function (x, y) {
  return x + y
}
```

ES5.
NO.
add(1,2).


### Third

```js
var add = (x, y) => {
  return x + y
}
```

ES6.
YES.
add(3,4).

### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

ES6.
NO.
obj.add(5,6).

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```
ES6
Yes.
obj.add(7,8)

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

ES6.
No.
obj.add(9,10)

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

Bob
Curly
1 
Mo
1


