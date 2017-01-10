# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

```js
function multiply(x, y) {
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

ES5
not anonymous
add()

### Second

```js
var add = function (x, y) {
  return x + y
}
```

ES5
not anonymous
add()

### Third

```js
var add = (x, y) => {
  return x + y
}
```

ES6
not anonymous
add()

### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

ES5
not anonymous
add()

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

ES5
not anonymous
add()

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

ES5
not anonymous
add()

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

Mo

-- YOUR ANSWER HERE --

