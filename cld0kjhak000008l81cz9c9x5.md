# Prototype and Prototype chaining in JavaScript

## What is a Prototype?

Prototypes are the mechanism by which JavaScript objects inherit features from one another.

All JavaScript objects inherit properties and methods from a prototype. For example:

* `Date` objects inherit from `Date.prototype` .
    
* `Array` objects inherit from `Array.prototype` .
    

The `Object.prototype` sits on the top of the prototype inheritance chain. Date objects, Array objects, and every other object we create inherits from `Object.prototype` .

Let's understand this by using an example:

* Let's create an array in the console.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673971472794/df11f35b-7f23-4804-a96a-ffa3c8aceb90.png align="left")
    
* Here, when we call the array we can see the array items and a prototype. And when we expand this prototype, we will see the below output.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673971965468/76dbbbde-af90-4ccb-98d5-259ddaad7a1e.png align="left")
    
* In the above image, we can see that the different Array methods are present in the Prototype.
    
* Any array that we create will inherit properties from the prototype called as `Array.prototype`.
    

## Prototype Chaining

Now, let us understand the prototype chaining with the help of the previous example only.

* In the previous example, we created an array. And we saw that this array inherits the properties from `Array.prototype`.
    
* This `Array.prototype` inherits the property from another prototype named `Object.prototype` .
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673973725381/af9bee65-e66e-43eb-bfb8-3ecea253450a.png align="center")
    
* Here, after expanding the prototype of the array, we are seeing that the prototype of the object is also present there.
    
* And if we expand this object prototype we will see different sets of properties or methods which are associated with the object.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673974320680/48958631-a7b6-4e07-81a8-44e5ddb381e6.png align="left")
    
* This `Object.prototype` sits on top of the hierarchy and every other data type such as Array or String inherits from `Object.prototype`. This is called prototype chaining or prototype inheritance.
    

## Conclusion

In this article, we looked into prototype and prototype chaining. And also we came to know that `Object.prototype` sits on top of the inheritance hierarchy and every other data type such as Array or String inherits from `Object.prototype` . From this, we can conclude that almost everything in JavaScript can be considered as objects.

Thanks for Reading🙂