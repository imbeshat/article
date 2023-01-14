# Objects & Working with Objects in JavaScript

## What is an object in JavaScript?

An object is one of the type of data types present in JavaScript. An object is a standalone entity, with properties and type. It is a collection of properties that stores various key-value pairs.

For example - if we want to store the details of employees, we generally use objects to store them.

```javascript
const employee = {
    empName: "Tony",
    empId: 1
}

// empName: "Tony" - this entirely is called property of the object
// empName is key
// Tony is value

// For accessing the objects value we use:
// a.) object.key
// b.) object["key"]
```

Apart from Primitive Data Types, almost everything in javascript is considered as an object. A typical object inherits properties (including methods) from `Object.prototype`, although these properties can be overridden.

## Different ways of creating an object

### Using object initializers

* We can create an object by using `object initializer`. An ***object initializer*** is a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces (`{}`).
    
    ```javascript
    const ironMan = {
        team: 'Avenger',
        power: 'Tech',
        suit: {
            name: 'Mark LXXXV'
        }
    }
    console.log(ironMan);
    
    // output
    { team: 'Avenger', power: 'Tech', suit: { name: 'Mark LXXXV' } }
    ```
    

### Using a Constructor

* We can create the object by using the constructor. We use `Object()` constructor and create the instance of the object by using `new` keyword.
    
    ```javascript
    const bike = new Object();
    bike.name = 'Kawasaki Ninja ZX25R';
    bike.color = 'Green';
    bike.engine = '250cc inline-4 cylinder';
    
    console.log(bike);
    
    // output
    {name: 'Kawasaki Ninja ZX25R',
     color: 'Green',
     engine: '250cc inline-4 cylinder'}
    ```
    

### Using Object.create() method

* Objects can also be created using the `Object.create()` method. This method can be very useful because it allows you to choose the `prototype object` for the object, you want to create, and in this, we do not have to define a constructor function.
    
    ```javascript
    const ironMan= {
    	fly: true,
    	superHero: true,
    };
    
    const superMan = Object.create(ironMan);
    
    console.log(superMan);
    console.log(superMan.superHero);
    
    // output
    { fly: true, superHero: true }
    true
    ```
    

### Using Object.defineProperty()

* This static method defines a `new` property directly on an object, or `modifies` an existing property on an object, and returns the object.
    
* Syntax:
    
    ```javascript
    Object.defineProperty(obj, prop, descriptor)
    
    // obj - The object on which to define the property.
    // prop - A string or Symbol specifying the key of the property to be defined or modified.
    // descriptor - The descriptor for the property being defined or modified.
    ```
    
* Example:
    
    ```javascript
    const superHero = {};
    
    Object.defineProperty(superHero, 'name', {
        value: "IronMan",
        writable: false
    });
    
    superHero.name= "SuperMan";
    // Throws an error in strict mode
    
    console.log(superHero.name);
    
    // output
    IronMan
    ```
    
* In the above example, even though we have modified the the value of name, it will only print the previous value i.e., `IronMan` because here the value of the `writable` is `false`. If we make writable as true, then the new value will be printed in the console.
    

### By using this keyword

* `this` refers to the parent scope. Here, we should remember one thing we can't use the arrow function as the arrow function does not have the context for `this`
    
    ```javascript
    const superHero = {
    	comics: "marvel",
    	hero: "",
    	printComic: function () {
    		this.hero += "IronMan";
    		return this;
    	},
    };
    
    console.log(superHero.printComic());
    
    // output
    {
      comics: 'marvel',
      hero: 'IronMan',
      printComic: [Function: printComic]
    }
    ```
    

* Here, we can do chaining of the function also.
    
    ```javascript
    const superHero = {
    	comics: "marvel",
    	hero: "",
    	printComic: function () {
    		this.hero += "IronMan";
    		return this;
    	},
    };
    
    console.log(superHero.printComic().printComic().printComic());
    
    // output
    {
      comics: 'marvel',
      hero: 'IronManIronManIronMan',
      printComic: [Function: printComic]
    }
    ```
    

That's all about object and working with it.

Thanks for reading 🙂.