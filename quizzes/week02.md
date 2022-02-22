# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var (dont use it)
let
const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a function is a set of statements that performs a task or calculates something
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
1. Single-repository principles
2. Open-closed principle
3. Linkskov substitution principle
4. Interface segrigation principle
5. Dependancy inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
index: 2
it is TECHNICALLY places third, but arrays start at 0, then go to 1, 2, 3, etc
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
{friends ? 'joy' : 'pain'}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the _____ is called the Increment Expression

the besat way to increase this would be to just put: i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM: Document Object Model
The HTML
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
1. Primitive Values
2. Boolean Type
3. Null Type
4. Undefined Type
5. Number Type
6. BigInt Type
7. String Type
8. Symbol Type
9. Object Type
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A functions parameter is the name listed in the functions definition
A functions argument is the real value passed into the function:

function doThing(parameter){
  console.log(parameter)
}

const argument = 'stuff'

doThing(parameter)
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are things like: number, 'string', etc
Reference values are things like: {objects}, [arrays], functions()
```