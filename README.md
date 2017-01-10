# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

-- YOUR ANSWER HERE --
```js
function multiply(x,y) {
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

-- YOUR ANSWER HERE --
- ES5
- no
- add(1,2)

### Second

```js
var add = function (x, y) {
  return x + y
}
```

-- YOUR ANSWER HERE --
- ES5
- yes
- add(1,2)

### Third

```js
var add = (x, y) => {
  return x + y
}
```

-- YOUR ANSWER HERE --

- ES6
- yes
- add(1,2)

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
- no
- obj.add(1,2)


### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

-- YOUR ANSWER HERE --

- ES6
- no
- obj.add(1,2)

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
- no
- can't be called in the form written

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

```js
0
1
2
2
```
