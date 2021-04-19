# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
they are the four API thingys... create, read, update, deeeeestroy
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
C = .post | R = .get | U = .put | D = .delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object relational mapping, it lets us read data from MongoDB even though that one is written in a non-javascript language
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
post and put... and maybe delete, but definitely not a get
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronous, then asynchronous
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
mongoose then mongoose
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
it exists between and the port and the request hallway (the gray drawbridge thingy) also kind of sort of where the portal is, every request must go through it.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
It's late... i can't find the keyword "pipeline" anywhere in the readings so i'm not sure what you're asking for... i suppose it's the two hallways in the castle but I'm not sure what we're calling those.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
I'm confused... do you want one of these functions here?
////////////////////////////////////
 async getAll(req, res, next) {
    try {
      let data = await thingService.getAll(req.query)
      return res.send(data)
    } catch (error) {
      next(error)
    }
  }
  ///////////////////////////////////
```