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

So 'name' and 'age' are the keys, 'Jhon' and 23 are the values. It is very important and easy to use for example to use it you just put '.'(a dot) between the object's name and the key:

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
    phone: ['(99) 99999 - 9999'],  // It an array
    address: {street: '12C'}, // It is an another object
    getName: function(){ return this.name } // It is a function
};
console.log(obj.name);
console.log(obj.age);
console.log(obj.phone[0]);
console.log(obj.address.street);
console.log(obj.getName);
```

Yeah, if we have an object inside to another object we have to put '.'(a dot)!

Be careful, see this:

```javascript
var obj2 = {
    name: 'James'
};

console.log(obj2.age);
```

In this case you will see -undefined-, it is just a type value, it tell us "this field don't have a value", ok, but it will be a problem if you want acess a another object.

```javascript
var obj3 = {
    name: 'James'
};
var obj3.address.street;
```

It will return to us a error.
