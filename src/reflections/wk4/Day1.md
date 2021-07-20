# Uno Dia - INTRO TO ASYNCHRONOUS CODE

Today's Reflection: I was able to complete the practice assignment today with the exception of checking to see which answer the user chose and if they were right or wrong.  I need some help on these comparisons - now that we are using so many files, where does the if statement go to compare these - the template, the controller, the service?  

## What are some of the signs and causes of Callback Hell?
### Pyramid shape of brackets at the bottom of code.  Sloppy code and unnamed functions can cause callback hell.

## What does the asynchronous mean and how are callbacks involved?
### asynchronous means that a function might take longer to complete than the one below it, but the program can still move on with the code while waiting for the first function to complete.  Callbacks are functions that are written with async/await and they will complete a function or return an error.

## Summarize the 3 ways to avoid / fix Callback Hell
### Name functions, if you name the functions, when there are errors, they will be referenced more easily. Modularize your code so that you can keep it short and easily readable. Make your code stable by handling every error.

Afternoon Code: https://sherenec.github.io/TriviaApiRequests/