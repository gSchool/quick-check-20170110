# Quick Check

## Re-write this function to get it to work without errors and to return the product of two numbers

```js
funtion multiply(x) (
  x + y
)
```

-- YOUR ANSWER HERE --
function multiply(x,y) {
  return x * y;
}

multiply(2,3);


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

-- YOUR ANSWER HERE --
- This is ES5.
- No, it is not. Its name is add.
- add(param1, param2);


### Second

```js
var add = function (x, y) {
  return x + y
}
```

-- YOUR ANSWER HERE --
- This is ES5.
- The function is anonymous, however, its value has been assigned to a var named add.
- console.log(add); I execute it by calling var add.

### Third

```js
var add = (x, y) => {
  return x + y
}
```

-- YOUR ANSWER HERE --
- This is ES6.
- Yes, it is. Fat arrow functions are anonymous.
- console(add);



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
- ES5.
- No, its name is add.
- add(param1, param2);


### Fifth

```js
var obj = {
  add: function (x, y) {
    return x + y
  }
}
```

-- YOUR ANSWER HERE --
- ES5.
- This function is anonymous.
- obj.add (I can't remember if I need to pass the parameters like obj.add(x,y)). 


### Sixth

```js
var obj = {
  add(x, y) {
    return x + y
  }
}
```

-- YOUR ANSWER HERE --
- ES5.
- Its name is add.
- You call it by using/calling the var obj.


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
I have no idea. I have never seen a for loop using console.log(). 
