# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
1: abstraction: taking a complex question or problem, and putting into simple actions. Multiple simple actions can solve many more complicated problems.

2: encapsulation: keeping logic organized. If there is a lot of logic changing data, it stays with the changing data logic. If there is a lot of logic controlling how the data is displayed, keep it separate.

3: inheritance: A hierarchy of data that keeps properties passed down through parents. It keeps processes organized.

4: Polymorphism: Making conditions or methods that work with similar but different objects. If all of these methods work across data types, then changing the code base will become easier.

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
staff[property]
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Repeating above answer:

2: encapsulation: keeping logic organized. If there is a lot of logic changing data, it stays with the changing data logic. If there is a lot of logic controlling how the data is displayed, keep it separate.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility!
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the definition of the class, an instance of a class is an actual object that exists.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy is an object that can represent other data while having rules or conditions attached to modifying it.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Model - controls how data looks and feels.
View - the way the user can interact
controller - controls how the user interacts with the data and moderates the user.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
controller - controls how the user interacts with the data and moderates the user.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is in charge of actually changing the data, where the controller just tells the service to actually do its job.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
the model is a way to define how data should look and make sure that other data that isn't constructed like the model should be rejected.
```
