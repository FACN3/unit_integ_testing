Research Topic - Unit Testing & Integration Testing

SO WHY TEST??
Testing prevents big re-writes of code down the line in a project and help ensure code and bug fixing is easier and picked up earlier


UNIT TESTING

- At a high-level, unit testing refers to the practice of testing certain functions and areas – or units – of our code.
- The presence of unit testing implies that the software is designed in a modular fashion.
- You divide your application into the smallest possible parts and test each one of them as a independent unit.
- Unit testing gives you the ability to verify that your functions work as expected. That is to say that for any function and given a set of inputs, we can determine if the function is returning the proper values and will gracefully handle failures during the course of execution should invalid input be provided.

Best practice is to start with Unit Testing from the very beginning of a project. In other circumstances and situations you may need to do ‘refactoring’ (the process of extracting code and putting it into a different form, without modifying its current behaviour).

What are the benefits?

- Helps us to identify failures in our algorithms and/or logic to help improve the quality of the code that composes a certain function.

- Approaching development from a unit testing perspective means you'll likely be writing code that is easy to test. .

- You can prevent future changes from breaking functionality. Since you're testing your code as you introduce your functionality, you're going to begin developing a suite of test cases that can be run each time you work on your logic.

INTEGRATION TESTING

In software testing, integration testing occurs after unit testing and before validation testing, in which individual software modules are combined and tested as a group.  There are also a number of different approaches to Integration testing which you will come across (top-down, bottom-up, ‘big-bang’ and sandwich testing)

There are a few types - summarised below but explained better in the youtube video link below:

1) Bottom-up - testing begins with unit testing at the lowest levels, followed by testing bigger and bigger combinations of code.
2) Top-down - first you test the highest level modules and the you go down to smaller and smaller part.`
3) Big-Bang - Testing everything at once - it is slow (and can mean a host of coders are not doing anything on a project whilst they wait for a section to be finished and it can be problematic

This is a really helpful introduction to Integration Testing and is only 3 mins!
https://www.youtube.com/watch?time_continue=2&v=QYCaaNz8emY

RELATED INFORMATION - Some current techniques used for integration testing:

Stub - override methods to return hard-coded values, also referred to as "state-based".
Example: Your test class depends on a method Calculate() taking 5 minutes to complete. Rather than wait for 5 minutes you can replace its real implementation with stub that returns hard-coded values; taking only a small fraction of the time.

Mock - very similar to Stub but interaction-based rather than state-based. This means you don't expect from Mock to return some value, but to assume that specific order of method calls are made.
Example: You're testing a user registration class. After calling Save, it should call SendConfirmationEmail.


Three Questions:
1) What is a benefit of Unit Testing?
2) When would you use a unit test, when would you use a integration test?
3) At what point in a project should you start integration testing?
