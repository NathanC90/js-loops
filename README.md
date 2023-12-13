# js-loops

This is a 3-task exercise to test my Javascript skills regarding Loops.

## Loop 1

In the first task, it is required to start by creating a simple loop that goes through all the items in the provided myArray
and prints them out on the screen inside list items (i.e., li elements), which are appended to the provided list.

Since we only need to print out all the items and don't need access to the index position of each item, I use `for...of` for the best practice according to [this article from MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code#which_loop_type_should_you_use).

To ensure the items are shown as list items, I use innerHTML instead of textContent and add li tags around the texts.

## Loop 2

In the second task, we are asked to write a simple program that, given a name, searches an array of objects containing names and phone numbers (`phonebook`).
If it finds the name, outputs the name and phone number into the paragraph (`para`), and then exits the loop beofre it has run its course.

Regarding objects, we are given a tutorial [here (JavaScript object basics)](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics).

To begin with the task, the following information is provided:

* `name`-- contains a name to search for

* `para`-- contains a reference to a paragraph, which will be used to report the results

* `phonebook`-- contains the phonebook entries to search.

We are also asked to use another type of loop that we have not used in Loop 1.
Therefore, I decide to use `while` loop at this time.

## Loop 3
