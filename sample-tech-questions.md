# Sample Technical Interview Questions

## General Programming

* Describe OOP
* Describe MVC
* What is scope?
* What is the DRY principle?
* Describe MVC.
* What are the similarities and differences between Ruby and JavaScript?
* What is recursion? Can you give an example of when recursion is useful?

## HTML

* What is the difference between an `HTML` document and the `DOM`?
* Why is the `DOM` sometimes called the `DOM Tree`?
* What is a DOM element and what is a DOM attribute? Can you give some examples?

## CSS

* What is a CSS Selector? Give some examples?
* What is CSS specificity?

## OOP Design

### Black Jack

* Design a Black Jack game using OOP. What classes would you use and what would be the attributes and methods for each class?

### Restaurant Reservation System

* Design a reservation system for a restaurant. What classes would you use and what would be the attributes and methods for each class?

## Ruby

* What is the difference between an Object and a Class?

* Write a Ruby class for creating Books. A Book should have the following attributes
  - title
  - year
  - author
  - description
  Make sure that each attribute is readable but not writable from code outside the class.

## Rails

* What is Rails?
* Describe how Rails does MVC.
* What is Active Record?
* What are routes?
* What would be a RESTful Route for creating a new recipe (give the HTTP operation and the URL)?
* List the typical 7 RESTful routes for a resource.

## SQL

* Describe what a Relational DB is.
* What are the SQL commands for doing CRUD operations?
* What is a Foreign Key?
* What is a join?
* What is the difference between an inner-join and an outer-join?

## JavaScript

* If you leave off the `var` keyword when introducing a new variable, what happens?
* What is the advantage of using the `forEach` method over the older `for` loop?
* What is JSON? What is it used for? What is _not_ allowed in JSON?
* Can you do Object-Oriented Programming in JavaScript? How is it different than doing OOP in Ruby?
* How are callbacks used in JavaScript to manage asynchronous operations?
* What are promises?
* What is a closure? When would you use one?
* What are constructor functions?
* What are prototypes?

## NoSQL

* Compare and contrast SQL and NoSQL Databases.
* What are `documents`, `collections`, `embedding`, and `linking`?
* When would you use `embedded` documents and when would you use `linking`?

---

## Easy Coding Exercises

### Average

Write a function that takes an array of numbers and returns the average of all the numbers in the array (write the logic, don't use a library function).

### Fizz Buzz

Write a function that plays the FizzBuzz game.

### Leap Year

Write a function that will take a year and report if it is a leap year - i.e. the function takes a year as input and returns `true` if the year is a leap year and `false` otherwise. Note that a leap year occurs:

```plain
on every year that is evenly divisible by 4
  except every year that is evenly divisible by 100
    except every year that is evenly divisible by 400.
```

For example:
* 1997 was *not* a leap year (not divisible by 4)
* 1996 was a leap year (divisible by 4)
* 1900 was *not* a leap (divisible by 4 but also divisible by 100)
* 2000 was a leap year (divisible by 4 and 100 but also divisible by 400).

### Temperature conversion

Write a function to convert Celsius to Fahrenheit.

### Pizza Party

Write a function to calculate how many pizzas to order. The function should take the following arguments: `number_of_people_eating`, `slices_per_person`. You can assume that the pizzas will have 8 slices each.

---

## Medium Coding Exercises

### Progressive Tax

Write a function that takes a single argument called "income" and calculates and returns the income tax due using a progressive tax:

    08% for the first 20,000 dollars
    10% for the next 20,000 dollars
    15% for the next 20,000 dollars
    20% for the rest

### Factorial

Use `recursion` to write a function that returns the factorial of a number.

### The Last Samurai

One hundred Samurai are standing in a circle each holding a sword. The first samurai kills the second, then the third kills the forth, and so on until there is only one Samurai left standing (remember they are standing in a circle and the circle is shrinking as they die off).

Write a function to determine which Samurai will be the last one alive? Assume that we have numbered the samurai from 1 to 100.

### Schedule Conflict

Write a function that takes 2 time segments and returns `true` if they overlap. A time segment consists of a `startTime` and an `endTime`.

### Traffic Light

Write a class for a Traffic Light. Each traffic light instance should have a `name` and a `color` and methods to change the traffic light color. Finally add a method for advancing the traffic light to the next color (red -> green, green -> yellow, yellow -> red).

## Hard Coding Exercises

### Shuffling Cards

Write a `Card` class for creating playing cards (each card should have a suit and a value). Then write a class for a `Deck` of cards. Have the `Deck` constructor initialize an instance variable with the classic 52 cards in the deck. Finally add a `shuffle` method to the `Deck` class to shuffle the cards. For shuffling you can assume a `random(min, max)` method that returns a random integer between `min` and `max`.

### Printing a Binary Tree

Write a function to print out the numbers in a sorted binary tree. The function should take a `node` as an argument and can assume that each node has `left` and a `right` child nodes (which may be null or nil).

