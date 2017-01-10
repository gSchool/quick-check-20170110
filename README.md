# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
function multiply(x, y) {
  return x * y;
}
```

-- YOUR ANSWER HERE --

## Explain each of the below versions of writing functions

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

ES5, no, add(num1,num2)

### Second

```js
var add = function (x, y) {
  return x + y
}
```

ES5, no, add(num1,num2)

### Third

```js
var add = (x, y) => {
  return x + y
}
```

ES6, no, add(num1,num2)

### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

ES5, no, obj.add(num1, num2)

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

ES5, no, obj.add(num1, num2)

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

ES5, no, obj.add(num1, num2)

## What does the following code output to the console?

```js
var i = 0
for ( console.log('Bob'); (console.log('Curly') === undefined); console.log('Mo') ) {
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
Curly
2
2
