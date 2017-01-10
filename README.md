# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

```js

function multiply(x, y) (
  return x + y
)
```

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

- ES5
- no, it is named 'add'
- add(3, 4);

### Second

```js
var add = function (x, y) {
  return x + y
}
```

- ES5 still
- it is anonymous. the variable add will store the result of the anonymous function
- because it is anonymous, it is not callable in another context

### Third

```js
var add = (x, y) => {
  return x + y
}
```

- ES6 (includes fat arrow declaration)
- it is anonymous. the variable add will store the result of the anonymous function
- because it is anonymous, it is not callable in another context

### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

- ES5
- not anonymous, function is called 'add'
- add(3, 4);

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

- ES6 because the function is stored as a value in an object, which I think is new in ES6
-  not anonymous, called 'add'
- obj.add(3, 4);

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

- I don't think this is valid JS because the contents of the object are not setup as key:value pairs


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
Mo
1
2
2
