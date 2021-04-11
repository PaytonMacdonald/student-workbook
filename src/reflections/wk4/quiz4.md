# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
asynchronous will skip over a 'paused' function but when the awaited function 'returns' it will immediatly run and then pick up where it left off before the 'returned' function re-interupted 

synchronous the way javascript normally runs... in a single thread sequence
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
an event listener will bring a observer pattern to the DOM, it waits for that final movement I think? Honestly I'm really not sure Google wasn't very clear on this one.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open-closed Principle: basically new code added should never change old code that is already being used.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
callback is a function that passes as an argument to another function so that it can be "called back" at a different time. It's not really the same as a higher-order function, those are functions that accept others as arguments except it contains the callback function logic for when it returns.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
from MDN = The Promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting value.
basically it makes an attempt but if the attempt fails the failure has code built in. i think TRY and CATCH are a promise???
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
.get .post .put .delete, BOOM that's four
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
okay so we've been using MVC"S" and the APIs are called from a "S"ervice we label as axios... so I'm not totally sure the correct answer here... 
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
what isn't the purpose? It helps organize things for a single coder as well as a team, it allows for so much more functionality not to mention more secure code. encapsulation just feels like a no brainer on the corperate coding scale.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
it's a code any computer can read, it translates data for use to use.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
that is an internal server error, i don't remember if that's their fault or out fault though
```