# Node-express
Node express
We added the index.js and module.js
opened index.js 
All files are linked from one js file to an other

```javaScript
const { add, subtract } = require("./myModule");

let name = 'Carolina Urrea'
console.log(name)

function printName(person) {
    return `Hello, ${person}`;
}
console.log(printName(name));

console.log(add(50, 5));
console.log(subtract(5, 15));
```

```javaScript
const beBasic = () => "That's so fetch!"
function add(num1, num2){
    return num1+ num2;
}

function subtract(num1, num2) {
    return num2 - num1;
}
module.exports = {
    beBasic,
    add,
    subtract,
}
```