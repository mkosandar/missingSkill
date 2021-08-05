# JAVASCRIPT

[CONTROL STRUCTURE:](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/CONTROL%20STRUCTURE%2068cb4d7b0b01415ca6b25b9650880329.csv)

# Variables

Variable means anything that can vary. In JavaScript, a variable stores the data value that can be changed. Use the reserved keyword var to declare a variable in JavaScript.

**Syntax:**

`var <variable-name>; 
var <variable-name> = <value>;`

**example :**

`var msg;`

# Datatypes:

JavaScript has different data types to hold different types of values. There are two types of data type in JavaScript.

1. **Primitive data type**
2. **Non-Primitive data type**

JS is a dynamic type language, we don't need to specify type of the variable because it is dynamically used by JS engine.

Example:
`var a = 1 ; //holding a number
var b= "mayuresh"; //holding a string`

![JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/UNIX_(12).png](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/UNIX_(12).png)

# Identifiers:

All variables in Javascript must be identified with a unique name. These unique names are called identifiers.
The general rules for constructing identifiers name are :-

- Names must contain letters, digits, underscores, dollar sign
- Names must begin with a letter
- Names can also begin with $ and _
- Names are case sensitive
- Reserved words cannot be used as names

Example :

`var x = 4; or var sum = 4;`//Identifiers can be short names (x and y) or can be detailed 
 `var x = 4; and var X = 4;` //x and X are considered to be different variables due to case sensitivity.

# Reserved words

JavaScript has certain words that must not be used as variables. These words are known as Reserved words.

example:

- abstract
- boolean
- class
- delete
- do
- double

[ARITHMETIC OPERATOR:](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/ARITHMETIC%20OPERATOR%205970dc4ad9044d438d7166b994caf53b.csv)

### **LOGICAL OPERATOR**

[Untitled](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/Untitled%20Database%209e9a8e7c090249d3a702dd194123e45a.csv)

### **CONDITIONAL OPERATOR**

[Untitled](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/Untitled%20Database%20668f2b9a304f4125aa048ad1b5cb997d.csv)

# FUNCTION:

A function is a block of code design to perform a specific task. We can pass a function as parameter also. Pure Function doesn't modify values outside the function, Pure function also returns the same values passed as input. High order Function that takes a function as parameter and returns function.
 
Every JavaScript function is actually a Function object. This can be seen with the code (function(){}).constructor === Function, which returns true.

**syntax:**

```jsx
function mkFunction(m1, m2) {
```

```jsx
return m1 * m2;   // The function returns the product 
```

```jsx
}
```

# CONSTRUCTOR:

Function()
Creates a new Function object. Calling the constructor directly can create functions dynamically but suffers from security and similar (but far less significant) performance issues to Global_Objects/eval. However, unlike eval, the Function constructor creates functions that execute in the global scope only.

**syntax:**

```jsx
function Person(first, last, age) {
```

```jsx
this.firstName = first;
```

```jsx
this.lastName = last;
```

```jsx
this.age = age;
```

```jsx
}
```

# built-in- constructor:

new String()    // A new String object

new Number()    // A new Number object

new Boolean()   // A new Boolean object

new Object()    // A new Object object

new Array()     // A new Array object

new RegExp()    // A new RegExp object

new Function()  // A new Function object

new Date()      // A new Date object

# ARRAY:

An array is a special variable, which can hold more than one value at a time.

Using an array literal is the easiest way to create a JavaScript Array.

**syntax:**

`const array_name = [item1, item2, ...];`

**eaxample:**

`const cars = ["mk", "tata", "maruti"];`

[ARRAY METHOD:](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/ARRAY%20METHOD%201a563a3a9d3f40c79ef2edc9e44385c5.csv)

# OBJECTS:

Objects are variables too. But objects can contain many values.

All JavaScript values, except primitives, are objects.

Objects can be created using the Object() constructor.

**Syntax:**

`var <object-name> = { key1: value1, key2: value2,...};`

## method of object:

**`[Object.assign()assign)`**

Copies the values of all enumerable own properties from one or more source objects to a target object
Object.create()
Creates a new object with the specified prototype object and properties.

** Object.defineProperty() **
Adds the named property described by a given descriptor to an object.

**`[Object.freeze() **
Freezes an object. Other code cannot delete or change its properties.

**`[Object.is()`**

Compares if two values are the same value. Equates all `NaN` values (which differs from both Abstract Equality Comparison and Strict Equality Comparison).

**`[Object.isExtensible()`**

Determines if extending of an object is allowed.

**`[Object.isFrozen()`**

Determines if an object was frozen.

**`[Object.isSealed()`**

Determines if an object is sealed.

**`[Object.keys()`**

Returns an array containing the names of all of the given object's **own** enumerable string properties.

**`[Object.preventExtensions()`**

Prevents any extensions of an object.

**`[Object.seal()`**

Prevents other code from deleting properties of an object.

# String:

A string is a data type used in programming, such as an integer and floating point unit, but is used to represent text rather than numbers.

[String methods:](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/String%20methods%20cdf5fed341bc4a4ba2dd99bed6982610.csv)

### **BUILT-IN-FUNCTION IN ES6**

[Untitled](JAVASCRIPT%20b07046575f1a404f8f58041b3d3cd444/Untitled%20Database%20389b652e5c8f42d695f8e4b9228fd8b0.csv)
