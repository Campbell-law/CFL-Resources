# Review
## Terminal
## Git
## HTML

—

# Terminal What You Need to Know

```bash
- cd    . . .   Change Directories 
- cd    . . .   Move up a directory 
- ls    . . . List the files in a Directory 
- rm filename  . . .     delete a file 
```

---

# Git What You Need to Know

```bash
-  git init    . . . Initialize a repository (directory)
-  git add -A  . . . Stage all files — get them ready to Commit
-  git commit -m ‘Describe what you did’   . . . commit files
-  git push    . . . send them to github
```

---

# HTML What You Need to Know

An HTML page is known as the DOM Document Object Model
Page Starts with <!DOCTYPE html>

```html
- <h1>   . . .  Open Tag
- </h1>  . . . Close Tag
- <script>Where your javascript goes </script>
```

---

# javaScript 101

-  Created in 1995 by Brendon Eich for Netscape
-  Created in 10 days
- Several Variations Ecmascript 6 (ES6) new version

---

## javaScript Use Cases
- In Browser
- node,  command line or on server
- stand alone npm packages
- Serverless - AWS Lambda, Microsoft Functions (server less node)
- Microsoft Office 365 - Word

---

### In JavaScript, there are six primitive data types:
- Boolean  . . . true false
- Number   . . . 1 2 3
- String   . . . "string"
- Null     . . .  null
- Undefined . . . undefined 
- Symbol (new) . . . Symbol()

Objects:  Everything else

---

# Reserved Words

break, case, catch, continue, debugger, default, delete, do, else, finally, for, function, if, in, instanceof, new, return, switch, this, throw, try, typeof, var, void, while, and with

---

# Variables
### Containers for storing values
```js
var tom = “Tom”;
var age = 20;
let camelCoders = [“Taylor”, “Connor”, “Logan”, “Paul”, “Greg”]
const pi = 3.14
```
* Can not start with a Number
* Can not have Spaces 
* Can not contain a reserved word
* [Variable Checker](https://mothereff.in/js-variables#%E0%B2%A0%5C%5C_%E0%B2%A0)

---

# Variables Cont'd.

Initialized Variable

```js
var food = 'pizza'
```
Uninitialized Variable

```js
var food     // returns undefined
```
Should be CamelCase

```js
var goodFood = 'pizza'
```

---

## “Strings”

“Hello World”    'Hello World'
“Wayne’s World”
‘Wayne’s World’     ‘Wayne/’s World’
’20’

Can assign a string to a variable

```js
let food = 'pizza'
```

---

## "Strings"

Get it's length

```js
food.length
5
'pizza'.length
5
```

Convert Case

```js
'pizza'.toUpperCase();
'PIZZA'
food.toUpperCase();
'PIZZA'
```

---

## Putting "Strings together"

```js
let camel1 = "camel"
let camel2 = "Coders"
camel1 + camel2
'camelCoders'
camel1 + " " + camel2
'camel Coders'
`${camel1}${camel2}`
'camelCoders'
`${camel1} ${camel2}`
'camel Coders'
```

