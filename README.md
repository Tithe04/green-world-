1) What is the difference between var, let, and const?
answer:var Function-scoped, can be redeclared & reassigned, hoisted as undefined.
let Block-scoped, can be reassigned but not redeclared, hoisted in temporal dead zone.
const Block-scoped, cannot be redeclared or reassigned, hoisted in temporal dead zone, but objects/arrays can be modified.

2) What is the difference between map(), forEach(), and filter()?
forEach loops, no return (just side effects)
map loops, returns new array (same length)
filter loops, returns new array (only items passing condition)