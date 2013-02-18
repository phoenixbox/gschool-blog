---
title: Eloquent Ruby
date: 2013-02-18 08:04 -07:00
tags:
---

Eloquent Ruby

#### What’s something that really "clicked" for you? Why/how? (Ex: Symbols, Dynamic Typing, etc)

A common trend it seems for me when learning Ruby is that on the face of it everything makes sense, I can backtrack through code snippets and mostly see whats happening where and why things are happening the way they are. The problem comes when abstracting that logic from the given example an applying it to a new problem, Im not quite there yet. So I dont think reading the book provided any real "click" moments. Reading the chapter on regular expressions was kinda cool. Most of the regex stuff I had seen before looked like crazy code within code, but now that I understand the syntax of them more I can see how they would be quite useful in the future.

#### Was there something you thought you understood, but are now more confused about?

The idea of duck typing is a little strange to me. I know the whole, "if it looks like a duck and it quacks like a duck then its a duck" thing but its just a little weird. The book says that Ruby doesnt look at an object type to decide whether its the right object but that it assumes that if the object has the right methods then its the right kind of object. So an array is an array because the object in question can have methods like length,inspect, pop, replace etc. called on it.Hmmmmmmm.......

#### Chapter 5 focuses on Regular Expressions. Do you feel like they’re a tool you’ll reach for, or try to avoid?

Once I read about the unique syntax of regular expressions it made them alot more approachable. Now that I sort of understand what they do, and what common operations they can execute I can appreciate their power. I definitely think that if I had a more complex string mathcing problem I would know that regular expressions are the most suitable heavy lifter, right now I have little practice in implementing them but Im going to practice so that they are a legitimate part of my Ruby toolbox.

#### How would you explain Mocks and Stubs?

Stubs and Mocks relate to testing of Ruby code. An ideal test will exercise on class at a time so that when a test fails we know something is wrong with the class in quesiton and not some other class, BUT we know that most classes wont function without other classes so the problem we face is: how do we test one class when it may need another class? To solve this problem, and thus know for sure that if our test has an error that it relates only to the class in question, we use a stub.

The stub acts as a stand in for one of the supporting classes but returns canned answers when its methods are called. A stub means there are no classes to create and therefore no methods to code.

A mock is for when a stub needs to take a more active role in a test. A mock knows which methods should be called with what arguments. It will fail the test unless the right arguments are passed as opposed to a test passing just because there are the right methods & their respective canned answers provided by a stub. A mock is a more active participant in a test.  




