---
date: 2016-07-17
Title: Golang interview questions
Description: 
Section: golang
Keywords:
- job
- interview
- question
- golang
Tags:
Topics:
---

Even if it's not like in the USA, more and more companies in France don't hesitate any more to ask technical questions during an interview for a job offer.

To be prepared for this kind of situation, this is a list of questions about Go, and their answers, found on the Web.



# Who are known as the fathers of Go programming language?

Go programming language was designed by Robert Griesemer, [Rob Pike](https://en.wikipedia.org/wiki/Rob_Pike), and [Ken Thompson](https://en.wikipedia.org/wiki/Ken_Thompson).  
It is developed at Google in 2009.

# What is workspace in Go?

A workspace is a directory hierarchy with three directories at its root.

 - "src" directory contains GO source files organized into packages
 - "pkg" directory contains package objects
 - "bin" directory contains executable commands

# Does Go supports generic?

In 2016, Go still not supports generic.


# What is the difference between the functions `cap()` and `len()`?

`cap()` gives the capacity of a variable according to its type (array, pointer, slice, string, channel).

`len()` gives the length of a variable according to its type of the slice.