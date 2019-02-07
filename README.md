# Java IV

## Stack

### Introduction

A "stack" is an abstract data type. It is a LIFO construct: Last In, First Out. Think of a stack of plates in a dining 
hall or restaurant's plate dispenser. The first plate gets a bunch of plates put on top of it. The last plate you put on 
the stack of plates is the first one you could remove.

### Instructions

Implement the Stack data structure.

#### 1. Create Stack class

Make a class called "Stack" and give it LIFO functionality. Our Stack class's storage will be an Array with a maximum of 
1000 elements of type string. It should have the following methods:

- `print()` - print the items in the order they were added to the stack. Should be in the form of `[‘item1’, ‘item2’]`
- `pop()` - Remove the last item from the stack and return the item
- `push()` - Put the item on top of the stack
- `numOfItems()` - No items in on the stack, return the message “There are no items in your Stack, otherwise, return the 
  number of items.

#### 2. Test Stack class

After creating the classes, have the program do the following

- Make a new stack
- Report number of items on the stack
- Push first
- Push second
- Push third
- Report number of items on the stack
- Print the stack
- Pop the stack
- Print the stack
- Pop the stack
- Print the stack
- Pop the stack
- Print the stack
- Report number of items on the stack

Your output should look like this:

````
There are no items in your Stack.

3

[ 'first', 'second', 'third' ]

[ 'first', 'second' ]

[ 'first' ]

[]

There are no items in your Stack.
````
