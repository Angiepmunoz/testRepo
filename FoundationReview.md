<h1>GIT </h1>
git init
git commit 

git add .
git add -A

git commit -am 'first commit'

git commit --amend --no-edit 

git remote add origin URL.git
- 'origin' is common practiced but can be named anything 
- origin is the name of the remote


Constant, Variables, Operators
```
var var1;
let var2;
const var2;
```

- var is not bound by block scope  
- let and const are bound by scope
- nothing can jump over function scope

Functions
``` 
function newFunc() { // Defined
  
}
const fourthFunc = function(){ // Assigned
  
}
const secFunc=()=>{ // Arrow
  
}
() => { // Anonymous Arrow
  
}

function (){ // Anonymous Defined
  
}

function anotherFunc/*Higher Order Function*/(/*Anonymous Arrow Callback Function*/() => { 

})
(function(){// IIFE immediately invoked function expression
    // limits scope of variables or functions
})();
```
- an arrow function doesn't retain context 
- only declared functions get 

