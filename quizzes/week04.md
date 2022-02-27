# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Asynchronous code VS Synchronous is the difference between what order a code will run in:
Asynchronous means all of your code runs immediately
Synchronous means your code will run one line at a time
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
ANd event listener is a special function that listens for something to arrive within the ProxyState (or similar) and then runs the delegated function.
Normally looks like this:
ProxyState.on('array', _doThing)
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-Closed Principle
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback is a function that is passed as an argument to another function in order to allow a function to call that particular function
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a special function that essentially promises a part of the code that it will bring it some kind of information from somewhere.
If the promise comes back and it doesnt have everything that it promised, a .catch() will run, and throw an error saying the promise was not successful.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
get()
post()
put()
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application Programming Interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
The Service
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation is essentially a security program that protects certain variables, functions, and values so that the user cannot tamper with them.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
2xx Status Code
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
This means the server encountered an unexpected condition that may have kept it from fulfilling the request
```