# Lab: Play with React State
Let's do something more advanced with React

## In this lab you will accomplish the following:
 - Understand how to nest components
 - Learn how to manipulate state
 - Learn how to build lists of components

## Set up your environment
 - Run `npm install` to install the node packages
 - Run `npm start` to start your webserver

## You are tasked with the following:
1. Create a component called NumberControl that contains a button (Add1) and a NumberList. The NumberList code is here for your convenience.

2. When someone presses the Add1 button, the next number should appear in the number list. For example, if you currently had:

 - 1
 - 2
 - 3
 - 4
 - 5

 Then when you press the Add1 button, the result should be

 - 1
 - 2
 - 3
 - 4
 - 5
 - 6

 Hint: The NumberControl component could have as part of it's state an array of numbers, and it can pass on that state in its render function to the NumberList component.
