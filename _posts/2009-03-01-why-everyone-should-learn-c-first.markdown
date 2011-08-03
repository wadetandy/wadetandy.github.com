--- 
wordpress_id: 34
layout: post
title: Why Everyone Should Learn C++ First
tags: 
- slug: c
  title: c++
  autoslug: c++
- slug: programming
  title: programming
  autoslug: programming
- slug: newbie
  title: newbie
  autoslug: newbie
- slug: learning
  title: learning
  autoslug: learning
categories: 
- slug: opinion
  title: Opinion
  autoslug: opinion
wordpress_url: http://wadetandy.com/?p=34
---
About two weeks ago, an [article](http://regulargeek.com/2009/02/11/what-programming-language-should-i-learn/ "What Programming Language Should I Learn?") from a blog I read fairly regularly made its way on to the Digg frontpage.  It was the opinions of an experienced software developer about what programming languages someone who is just getting started in software development should learn.  Many comments on this post questioned the omission of c/c++ from this list, which the author addressed earlier this week in [this post.](http://regulargeek.com/2009/02/21/explaining-my-list-of-programming-languages/ "Explaining My List of Programming Languages") He argues that with the original post he was targeting people new to software development, and that he was of the opinion that programmers should get experience with a simpler language before diving into c++.  There has been talk in the Georgetown Computer Science Dept. recently about making this same change, and starting with a much simpler language like Python, and a professor I know at another university is writing a book about Ruby aimed at beginning programmers.I strongly disagree with this trend toward pushing beginning programmers toward "simpler" languages when they are starting out.  I think learning c++ teaches certain programming concepts that many (and in some cases almost all) programming languages cannot:**Strongly Typed**C++ requires every declared variable to have a declared type, which brings with it several advantages.  First, any type errors caused by things like trying to implicitly convert from one type to another or by calling invalid methods on a function are caught at compile time.  This allows a developer to have much finer control over program flow, and reduces the number of possible run time exceptions dramatically.**Object Oriented**Anyone seriously interested in entering the world of modern software development must absolutely be familiar with the object oriented programming paradigm.  This means that data can easily be represented in more complex ways, allowing a program to abstract data into more manageable forms.  A program could for example, perform a series of functions specific to all pets, functions specific to dogs, and then functions even more specific to golden retrievers. C++ features support for all of the major aspects of object oriented programming, including public, private, and protected methods and variables, polymorphism (and even multiple inheritance, allowing a student employee to be both a subtype of student and a subtype of employee), and generic templates.**Procedural**C++ is also very well suited to procedural programming.  Procedural programming replaces the objects, attributes, and class methods of object oriented programming and instead breaks tasks into data structures, variables, and functions (subroutines). By eliminating objects and their associated memory and processing overhead, well written procedural code is generally much faster than equally well written object oriented code.  This functionality is particularly well geared to writing low-level applications like device drivers that need to be as fast as possible.  Procedural programming is also excellent for quickly prototyping applications.**Unmanaged**Most modern programming languages have a feature referred to as "managed code," which means that the compiler or interpreter automatically handles the allocation and deallocation of memory when a program runs using so-called "garbage collectors."  This eliminates memory leaks in a program, which is an excellent and useful feature.As useful as garbage collection is, when someone is learning to program for the first time, any obfuscation of the way things work is not in that programmer's long term interest.  A C programmer (and c++ programmers to a lesser extent) knows the ins and outs of a computer's memory system, and can pass pointers and pointers to pointers around with ease.  This translates to being able to develop software that is fast, efficient, and that features well designed data structures.
