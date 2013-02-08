---
title: Refelctions on Event Reporter
date: 2013-02-08 10:44 -07:00
tags:
---

#Event reporter

###Project Overview

This week we took on the Event Reporter project. The idea was that this project would build upon some of the skills we had hopefully picked up from our previous two projects MicroBlogger and EventManager, namely simple method and class creation as well as loading and parsing a csv file.

Event reporter's remit was to provide a CSV query tool where the user could enter a keyword command and then have the results of any queries performed stored in a 'queue'. This 'queue' could then be sorted, cleared and printed out to the user console. This was the jist of the basic expections for the project. There were some more extensive 'extra credit' expectations , such as an improved queue print format in the user console, a broader 'find' command scope within the CSV file whereby compound searches could be formed etc. Im new to programming, at the time of writiing this blog I have had about 10 days of actual practice so needless to say this project was quite a challenge for me! 

##Reflections

Up to the beginning of the project I was still quite hazy on many of the basics including variable scope and method creation, so even figuring out how to tackle the project was a challenge. I applied the old tried and trusted examinations methodolgy whereby I would read the whole project and see if there was anything that I didnt understand. This actually created a huge problem for me! The project outline talked about the use of a queue. I didnt know what this was so I used the google machine to pull up anything related to ruby + queue. I found info on the Ruby class queue which talked about syncing communication between threads. I then went on to waste alot of time looking into what threads were and what they did. Little did I know that the 'queue' referenced in the project outline was just an object where I would store query results, so it could effectively just be an empty array where I would dump the results of a query method. So one part eagerness and two parts novice programmer resulted in a ridiculous amount of time wasted and confusion. Lesson learned: change my approach to undertaking a project. Make sure I understand the context of the requirements before I start researching how to go about starting the project. Necessary teething pains it seems for acquiring my new programming skills.

##Time & methodology
I wasted alot of time in the land of confusion with this project. I didnt ask for much guidance or help at the start becasue I thought I needed the confidence of solving problems on my own. Alas, another mistake. The biggest one in fact, because I got pretty demoralised floundering with the basics when I should have just asked one of the group memebers whom had some more experience for guidance. Next time I will ask ALOT of questions, because even though I dont like to admit it, I need as much help as I can get.

Hours put into this project? +8hours * 3 days = 24hours, of which id say 8 were productive beacause I asked for help. I decided to only ask for help from one/two persons so that I wouldnt be presented with too many varyong perspectives on how to approach a problem. I didnt want to add fuel to the confusion.

###Conclusion
Was the project enjoyable? No not really! For me it was very tough, but I think if I had been given a lesser project I dont think I would have cut my teeth as much.

No doubt this will be a recurring process so bring on the next 5.5 months...


####Check it out!

###EventReporter Project

Clone my repo: git@github.com:phoenixbox/event_reporter_final.git
