---
title: Metaprogramming
<!-- date: 2013-03-03 19:31 -07:00 -->
tags:
---

# Metaprogramming

### Does the idea of Metaprogramming make you say "Hell yeah!" or "Hell no!"? Why?

Plain and simple, right now the techniques under the Metaprogramming are beyond me at +4 weeks of experience in the Ruby world. I can definitely appreciate the benefits of much of which was being discussed, but in terms of implementation, it seems unlikely that when I am writing code now that I will be able to bridge the gap between aprreciation and implementation to code that is in another context. Possibly one of the things that I could implement in the not too distant future may be Ruby hooks. I definitely think that a barrier to my progression is error tracing. Currently I am not too sure how to back track when somethhing goes wrong. Couple this with a not so solid grasp on testing methodlogies gets me quite stuck. An immediate goal of mine is to refine my testing understanding and evolve past a reliance on the puts debiugging technique I have grown accustomed to. No doubt the Metaprpgramming techniques will improve my workflow in the future but you gotta crawl before you run a marathon.

### Explain how method missing works, when it's wisely used, and what cost it has.

The central idea of method_missing seems to be that of delegation, whereby one object uses another to get part of its job done. It can be used to deal with error messages when the method lookup cannot find the method with the same name as the one provided. Usaully we get the all too familiar code blowup with a NoMethod error and this is where the method_missing method can come in handy. It gets oassed the symbol of the method that was not found along with the block and an array of the arguments passed in the orginal call. A good descrition from a blog post is that it deals with errors 'gracefully'.

The book mentioned too that method_missing can allow us to effectively create an infinite number of vitual methods in an effort to create more flexible API's but that part escaped me. Insert explanation here...

### Why would you use Monkey Patching?

Monkey-patching it seems is for an iterative approach to changing code at runtime. It is used for on the fly modification of existing classes appears to be a workaround technique to getting something to just work. It can be used to

* Add new methods to an existing class
* Change already existing methods in a class
* Alias or delete methods
* Fix broken classes
* Enhance working classes
* or for assembling large classes bit by bit

A good quote to describe why monkey patching can be seen below:

> ...if it walks like a duck and talks like a duck, it’s a duck, right? So if this duck is not giving you the noise that you want, you’ve got to just punch that duck until it returns what you expect. - Patrick Ewing - RailsConf 2007

### What's the most confusing of all these techniques? Why?

The logic behind the techniques presented all seems sound. I can appreciate that they will be useful for me personally in the future but right now at my inexperienced level, dipping the toe in the metaprogramming pool is about as much use as I will or can expect to get. It would be useless for me to get deeper into the content right now because it would drown my efforts to build a solid foundational understanding of the Ruby language. Exposure to new ideas is always good though

### How has Eloquent Ruby affected your understanding of Ruby? Would you recommend it to someone else learning Ruby? Why / why not?

I dont think Eloquent Ruby is the kind of book you read just once over a 2 week period. I think its one of those stock reference books that you keep on your desk or somewhere that you have it easily to hand so that when the appropriate time comes to implement something and you remember that there was a good descriptive soilution in the book you can call upon it. Its more or a developmental book, something that you would have during your formative years as a programmer that will get use from time to time. There is little point in expecting to read the book as a novice and expect to be an exponentially better programmer as a result. For me it serves as good exposure to the material which will become second nature as I get better as a programmer. Its the type of book whereby its value and relevance increases with your experience. I would recommend it becasue it is writen in quite a novice friendly way, and its likely to be one of those books that you refer to when you are increasingly getting to grips with new concepts