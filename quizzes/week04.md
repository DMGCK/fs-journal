# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous code cannot pause and wait for another function to complete before it runs, while async can.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
A function that waits for an event to occur.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
*Objects or entities should be open for extension but closed for modification*  -  if you can make your defined data do more without changing how it is structured or recovered from another source, awesome. You should not modify it if you can help it.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A higher order function is a function that calls another function during its runtime.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is a form async with 3 states. Pending, resolved, and rejected. If a promise fails, a .catch method will be able to grab the message it sends upon failure.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Requests as in data requests! GET, PUT, DELETE
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
the service makes calls to apis, it is the only part of that model allowed to make changes to the data.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
encapsulation, or separation of concern keeps code readable, editable and modular. If one peice breaks in a non encapsulated codebase, good luck. If it is encapsulated, it can be much easier to find and fix.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 - 206. 200: OK is probably the most used?
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
An error that a server can throw when an unexpected condition is thrown and it does not know what else to do.
```