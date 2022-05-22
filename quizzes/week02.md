# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Let, Var, and const.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a first class object (that is also data????) that performs a task or calculates a value.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```

S: Single responsibility. Each thing has *only one responsibility.* If one thing does 20 things, then if you edit the 1 everything breaks!

O: Open for extension, Closed for modification.

L: If you reference something, you should be able to use something that is structured the same without being the same object.

I: many smaller *interfaces* are better than one general purpose interface

D: depend upon functions that can take any of its inputs, not just one.


```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Index 2, 0: apple, 1:banana, 2:pineapple. 0 is the beginning.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (this == conditional) {
  return true;
}
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++, possibly an iterator.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
The DOM stands for Document Object Model. Everything begins with the document, then each other piece can be accessed through the document.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Primitives: Bools, Null, Undefined, Number, BigInt, String, and symbol.

Objects: Object.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
a parameter is the alias for data in a function, whereas the argument is the actual data passed from somewhere else.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
a primitive represents a single value, whereas a reference... uhh, references a value from another source. Sometimes these references can edit the original value that was referenced.
```