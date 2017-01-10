# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

function multiply(x, y){
 x * y
};

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
add(2, 4)

### Second

```js
var add = function (x, y) {
  return x + y
}
```

es5
no
add(3, 5)

### Third

```js
var add = (x, y) => {
  return x + y
}
```
es6
yes
add(4, 6)
### Fourth

```js
function add(x, y) {
  return x + y
}

var obj = {
  add: add
}
```

es6
no
add(4, 1)

### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

es6
no
obj.add(3, 1)

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
obj(3, 6

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
(bob,
curly,
1,
mo,
curly,
2,
2,
)
bob
curly
Mo
1
0
