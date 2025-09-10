1) What is the difference between var, let, and const?
answer:var Function-scoped, can be redeclared & reassigned, hoisted as undefined.
let Block-scoped, can be reassigned but not redeclared, hoisted in temporal dead zone.
const Block-scoped, cannot be redeclared or reassigned, hoisted in temporal dead zone, but objects/arrays can be modified.