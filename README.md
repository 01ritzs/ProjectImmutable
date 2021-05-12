# ProjectImmutable
Example of Immutable class.
Created Employee immutable class, so no changes in data can be make from outside.
Fetched in main class to make a list of all the employees and there details 

To Create a immutable class, there are five steps we need to keep in mind 

First :- Make the class final, so no overriding of methods is possible.
Second :- Make all the fields final and private so its value will remain same throughout its life cycle.
Thrid :- Initialize all the fields in constructor
Fourth :- Don't provide setter method, as immutable class does not let its fields or method chagned. Only provide getter method.
Fifth :- In case any of the fields of the class holds reference to a mutable object any change to those objects should also not be allowed.
