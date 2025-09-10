1) What is the difference between var, let, and const?
answer:var Function-scoped, can be redeclared & reassigned, hoisted as undefined.
let Block-scoped, can be reassigned but not redeclared, hoisted in temporal dead zone.
const Block-scoped, cannot be redeclared or reassigned, hoisted in temporal dead zone, but objects/arrays can be modified.

2) What is the difference between map(), forEach(), and filter()?
forEach loops, no return (just side effects)
map loops, returns new array (same length)
filter loops, returns new array (only items passing condition)

3) What are arrow functions in ES6?
Arrow functions: short ES6 syntax for functions, inherit this, single-expression can omit return. const add = (a, b) => a + b;

4) How does destructuring assignment work in ES6?
Destructuring:extract values from arrays or objects into variables.
const [a, b] = [1, 2];
const {x, y} = {x: 10, y: 20};

5) Explain template literals in ES6. How are they different from string concatenation?
Template literals: use backticks for strings with ${} for variables and multi-line support.

const name = "Alice";
const msg = Hello, ${name}!;