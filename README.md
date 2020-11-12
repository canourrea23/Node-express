# Node-express
Node express
## Creating Node
1. You go to your `Github' and create `Repo`.
2. Once you create that `Repo` go into your terminals to `clone` it locally.
3. once you `Clone` your repo
4. Be sure to go into your `repo folder` to start the process.
5. Two options you have are `npm intit` which will ask you details on your prohect if you want to ve more descriptive, like...
```iterm2
My-first-node-project git:(main) npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (my-first-node-project) my-first-node-project
version: (1.0.0)
description: "This is my first node project"
entry point: (index.js) npm init -y
test command: touch index.html
git repository: (https://github.com/canourrea23/My-first-node-project.git)
keywords: [],
author: Carolina Urrea
license: (ISC) "ICS",
Sorry, license should be a valid SPDX license expression (without "LicenseRef"), "UNLICENSED", or "SEE LICENSE IN <filename>".
license: (ISC)
About to write to /Users/carolinaurrea/Desktop/SEI1019/unit_two/codealong/My-first-node-project/package.json:

{
  "name": "my-first-node-project",
  "version": "1.0.0",
  "description": "\"This is my first node project\"",
  "main": "npm init -y",
  "scripts": {
    "test": "touch index.html"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/canourrea23/My-first-node-project.git"
  },
  "keywords": [
    "[]"
  ],
  "author": "Carolina Urrea",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/canourrea23/My-first-node-project/issues"
  },
  "homepage": "https://github.com/canourrea23/My-first-node-project#readme"
}


Is this OK? (yes) yes
```

6. or `npm init -y` which will defailt all the settings to yes and blank

```
 My-first-node-project git:(main) ✗ touch index.js
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
