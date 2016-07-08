# English
My first english article

### Object in javascript

Hi, today we're going to study some things about objects in JavaScript.

What is an Object? Object is a data type made with keys and values. For example:

```javascript
var myFirstObject = {
    name: 'Jhon',
    age: 23
}
```

So 'name' and 'age' are the keys, 'Jhon' and 23 are the values. It is very important and easy to use for example to use it you just put:

```javascript
console.log(myFisrtObject.name);
console.log(myFirstObject.age);
```

You will see respectively 'Jhon' and 23. 

What kind of types can we put in an Object? All the type it includes arrays, other objects, functions.

```javascript
var obj = {
    name: 'Jhon',  // It is a string
    age: 23,  //It is number
    phone: [],  // It an array
    adress: {street: '12C'},
    getName: function(){ return this.name }; // It is a function
}
```
