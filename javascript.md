# null and undefined

null - null is assignment value then null can be assigned to variable as represent of "no value"
typeof null = object
undefined - undefined means we have declear variable but not yet assigned value to the variable

When you try to access a variable which does not exist in the program or it is not decleared then you encounter a runtime error which is referance error that means that variable is not defined.

# 1 What is debugger ?

- The debugger keyword stop the execuation of javascript and call the debugging function.( debugger is available in almost all javascript engine )

# 2 What is hoisting ?

- Hoisting is javascript dafault behaviour of moving all declearation to the top of the current scope before code execuation.
  -- arrow and anonymous function are not hoisted
  # Execuation Context
  -Execuation context is abstract concept that hold information about the environment where the current code is being execuated.

# 3 temperal dead zone ?

- the let and const variable are not accessable before they are initialized with some value and the phase between the starting of the execuation of block in which the let and const variable is decleard till that variable is being initialized is called tempored dead zone for the variable

# 4 What is IIFE ?

- a immediatly invoked function expreation is way to execuate function immadiatly as soon as they are created
  this function is very usefull because they don't pollute the global object

# 5 What is eventloop ?

- The event loop is constantly running process that moniters both the callback que and the callstack

All the Web API function like setTimeout() setInterval() fetch() etc will not be directly execuated inside the execuation context.
firstly they will be moved to callback que and then moment the callstack gets empty these function will be pushed to callstack from callback que by event loop

# 6 Event Bubbling ?

# 7 What is first class function

programming language is set to have first class function
when function are treated like any other variable
function can be passed as argument to other function

# 8 What is pure function ?

in pure function you get the same output value for the same input value

# 9 What is this keyword ?

- this keyword refer to the object from where the function is called
  object method - call() , apply() , bind()

# 10 What is callback function ?

# 11 HOC function

# 12 Arrow Function

- it is better way to write then regular function , it is introduced in ES6

# 13 What is closure ?

- A closure is combination of function bundled together with referance to its surrounding state i.e the laxical environment
  A clousure gives you access to a outer function scope from a inner function
