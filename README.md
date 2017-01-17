# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
function multiply(x) (
  x + y
)
```

-- YOUR ANSWER HERE --

function multiply(x) {
  return x * y;
}

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

Hey Matt, can you double check that this is actually ES6? I looked this up and can't figure out how this is ES6, still looks like ES5 to me. Are we talking about the problem:
function multiply(x) {
return x * y;
}

-- YOUR ANSWER HERE --

- ES5
- Is the function anonymous? NO
- How do you call the function? add(5,9);

### Second

```js
var add = function (x, y) {
  return x + y
}
```

-- YOUR ANSWER HERE --

- ES5
- Is the function anonymous? NO
- How do you call the function? add(5,9);

### Third

```js
var add = (x, y) => {
  return x + y
}
```

-- YOUR ANSWER HERE --

- ES6
- Is the function anonymous? NO
- How do you call the function? add(7,4);

### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

-- YOUR ANSWER HERE --

- ES5
- Is the function anonymous? NO
- How do you call the function? ? add(3,4);

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

-- YOUR ANSWER HERE --

- ES6?
- Is the function anonymous? NO
- How do you call the function? obj.add(3,4);

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

-- YOUR ANSWER HERE --

- ES5
- Is the function anonymous? NO
- How do you call the function? obj;

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

-- YOUR ANSWER HERE --

Mo  ?
