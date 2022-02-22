# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
1. Abstraction
2. Encapulation
3. Inheritace
4. Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.property
staff['property']
{property} = object

(They all work, but Ive used the staff.property the most so far)
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Its a method thats used to hide information so that the user has limited access to the properties and objects within the encapsuled window.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is essentially a Blueprint that can be used to create objects
An instance of a class is the relationship between the object and the class itself
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object allows you to create an object that can be used in the place of the original object
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
It is primarily used both to further organize projects, and to provide a level of security for the code to keep it from being manipulated
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is essentially a Coordinator between the View and the Model
It doesnt DO much except tell EVERYTHING else what to do
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The Service acts as a mediator between the controller and the repository.
The Controller calls upon the Service and tells it which tasks it needs accomplished, and the Service then delegates that work among all the other windows.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model in MVC does one thing: it exists as an item or an object. It has a few "functions" and getters, but all of thise are used in order to further define WHAT this object is.
```
