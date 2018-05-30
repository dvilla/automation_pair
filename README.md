# Automation pair programming

## Requirements

- User shuold know already how to start and develop a selenium project
- Basic understaing of at least 1 programming language
- Known one assertion library from you programming language of choice
- Understanding of page objects pattern

## Instructions

1. You can use whatever material you want, stack overflow, google, wolframalpha, books, etc.
2. Communicate what you are doing, don't be shy, ask questions, explain your solutions
3. Read carefully and if in doubt ask questions

## Time
- 1:30

## Exercise 1

Create a method that takes one array as an input and returns the same array sorted, after that create 3 test cases (or more if you want) to assert that array is sorted

## Exercise 2

Do a curl to www.google.com to only get the headers and save it to a file "results.txt", if you don't have curl installed, check this same repo /results directory, the file is already there 

Once you have results.txt create a test to make sure that it contains a "200 OK"

That's it

## Exercise 3 

Use selenium to automate a task that goes to your favourite flights site (expedia.com, kayak.com, cheapflights.com) and search for a flight from your city (or any city) to cancún, any dates, just one week of difference between departure and arrival, then create a test that passes when the price is $1000MXN or $50USD lower (depending on your currency) from the current price

Yup, the test should fail at first, but use a task scheduler that runs the test everyday (at any time you want) so we get noticed when the flight is cheaper

