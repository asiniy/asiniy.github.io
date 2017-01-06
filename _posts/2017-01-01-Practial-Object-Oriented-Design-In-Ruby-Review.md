---
layout: post
title: Book Review - “Practical Object Oriented Design in Ruby”
comments: true
tags:
  - ruby
  - book reviews
---

I'm a self-taught programmer. I found myself to write relatively dirty, difficult to maintain code even couple of years ago. But yeah, it's a common self-taught programmers problem: we don't have a timeframe to learn Computer Science basics. We just register to upwork and start to work immediately (after just couple of books and courses, of course). And it's good!

I'm happy with my salary but definitely not with the code quality I produce. I decided 2017 to be the first year when I learn Computer Science basics. The first thing to start with - is not algorithms or data structures. The most important thing to start with - is the software design, because in our days the bottleneck is placed inside the developer performance, not in the machine performance itself. Hopefully, I'll grow hard algorhytmic codebase in 2018.

The first book I've read on software design and software patterns - is the Sandi Metz bestseller [Practical Object Oriented Design in Ruby](http://www.poodr.com/). Let me go through chapters briefly.

The first chapter gives the basics of OOP: it's history, prerequisites for creation and so on.

Second chapter started to unload good code principles to my head. The main question Sandi asks reader here: "How to make everything in ruby" (class, object, method) work like it has a single responsibility? And she also reveals the main benefit of SRP by practical (even a little contrived) example.

Third chapter was a good explanation on how ruby classes are relies on each other. It was wonderful, but extremely brain-melting journey to the dependencies land. The thing I was not happy in this paragraph was lack of `Abstract` and `Concrete` classes definitions, so some googling was necessary there. Main quote from this chapter - *Depend on things that change less often than you do*

Fourth chapter is the comprehensive description of Law of Demeter - a prompt how to design your codebase in a good way.

Fifth has an introduction to Duck Typing - a technic to invent and create interface for different classes to make code less coupled.

The next chapter is about inheritance - the essential concept of the OOP. It tells how does class hierarchy works, and how could it help us to build a better design in our application.

Seventh was about sharing behaviour with modules (I was the most familiar with it). Just simple stuff - how could I create modules, why do I need to create it et.c.

Eight described how to combine objects with composition. Composition is another (instead of inheritance) way of building application design. Its main idea lies on passing one class instance to another to get an awesome structured and maintained design.

The final, chapter nine is about how to properly test code in design techniques covered in this book.

My verdict: MUST READ. The book is more about programming overall than only ruby. It gives better understanding how does OOP works and helps to programmer.
