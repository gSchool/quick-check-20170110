# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

-- YOUR ANSWER HERE --


function multiply(x,y){
let sum = x* y;

return sum;


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
its ES5, 

no, its not anonymous.

add(5,6) // how to call the function
-- YOUR ANSWER HERE --

### Second

```js
var add = function (x, y) {
  return x + y
}
```



-- YOUR ANSWER HERE --
ES5,

its an anonymous.

add(3,9)



### Third

```js
var add = (x, y) => {
  return x + y
}
```

-- YOUR ANSWER HERE --
its ES6

its an anonymous.

add(3,7)



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
its ES6

its not anonymous.

add(5,7)


### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

ES6
obj.add(3,6)
-- YOUR ANSWER HERE --

### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```
its an anonymous.
ES6
obj.add(x,y)
-- YOUR ANSWER HERE --

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

-- YOUR ANSWER HERE --

Bob
curly
1
error
