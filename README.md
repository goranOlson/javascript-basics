# Javascript Basics

### Comments
Comments are used to add explanations within your code
They are ignored by the Javascript Engine.

Single-line comments

```js
// This is a single line comments
```

Multi-line comments

```js
/* This is a multi-line comment.
We can write over many rows */
```

### Logging to the console
Logging to the console is used to print information to the browser console. It's helpful for debugging our code and understanding how our code is executing.

It is used with this method: `console.log();`

```js
console.log("Hello from the console!");  // Prints the text int the parentheses to the console
```

### Variables and scoop
More info about variables: https://javascript.info/var

#### let
Declares a variable that can be reassigned. It has block-level scope.
```js
let number = 10;
let name = "Goran";
let firstName;  // Variable unassigned.

firstName = "Happy";


number = 20;
 ```
`=` is the assignment operator for variables.

#### const
Declares a constant variable whose value can not be reassigned. It is assigned at the declaration. It also has a block-level scope.

```js
const myAge = 18;
```

#### var
The old way to declare variables. It has a function-level scope, which means it's available al over the place, it's hoisted to the top of the file. This in not a behavior that we want.

```js
var address = "js street 99";
```
More info about using strict to get more mean variable hangling: https://www.w3schools.com/js/js_strict.asp


### Data types

#### Number
Represents a numeric value like a integer or a decimal.

```js
let age = 18;  // Integer
let price = 24.99;  // Decimal (uses periods, not comma)
```

#### String
Represents textual data enclosed in quotes, and it can be single quotes or double quotes or even back ticks.

```js
let lastName = "Joy";
let firstName = 'Happy';
let otherName = `Sun`;  // Can injects with variables...

const fullName = firstName + ' ' + lastName;  // Concatenation
```
With back ticks we can includes variables and we can build multi-line strings.

```js
const greeting = `Hello, I am
a multi-line string, and
I can exist on many different rows`;

```

Now lets look at injections inside a string.
```js
const firstName = "Tom";
const lastName = "Top";

const hiThere = `Hi $(firstName) $(lastName)`;
```

#### Boolean
Represents true or false value.

```js

```


