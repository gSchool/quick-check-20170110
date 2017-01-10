# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

function multiply(x, y){
  return x + y
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
es5, es6 would be with fat arrow;
no
add(x,y)

### Second

```js
var add = function (x, y) {
  return x + y
}
```
es5
yes....? because variable add references the anonymous function but the fuction will be asocciated with variable add
add(x,y)

### Third

```js
var add = (x, y) => {
  return x + y
}
```
es6
no
add(x,y)

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
no
add(x,y)

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

es5
yes but the function will be refenced by variable add
obj.add(x,y)

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

es5
no
obj.add(x,y)

## What does the following code output to the console?

```js
var i = 0
for ( console.log('Bob');
(console.log('Curly') === undefined); 
console.log('Mo') ) { 
  console.log(++i)
  if (i >= 2)
    break
}
console.log(i)
```
1
