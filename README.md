# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

-- YOUR ANSWER HERE --

funtion multiply(x,y) (
  return x * y
)

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

-- YOUR ANSWER HERE --
This is ES5.
This function is not anonymous,  its name 'add'.
add(2,3)  - will return 5

### Second

```js
var add = function (x, y) {
  return x + y
}
```

-- YOUR ANSWER HERE --
This is ES5.
This function is  anonymous.
add(2,3)  - will return 5

### Third

```js
var add = (x, y) => {
  return x + y
}
```

-- YOUR ANSWER HERE --
This uses ES5 (var) and ES6 (=>)
This function is  anonymous.
add(2,3)  - will return 5

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
This is ES5
This function is not anonymous.
obj.add(2,3)  - will return 5
or add(2,3)  - will return 5

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

This is ES5
This function is anonymous.
obj.add(2,3)  - will return 5

-- YOUR ANSWER HERE --

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

-- YOUR ANSWER HERE --
This uses ES5 (var) and ES6 (function definition)
This function is anonymous.
ogj.add(2,3)  - will return 5

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

'Bob'
'Curly'
'Mo'
2

-- YOUR ANSWER HERE --

