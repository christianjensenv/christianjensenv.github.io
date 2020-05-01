---
layout: essay
type: essay
title: The Sandwich Shop of Code
date: 2020-04-30
labels:
  - Structure
  - Visual and Intuitive
---

## MVC, What is it?

First of MVC stands for Model View Controller, which is an architectural pattern of sorts. A simple way that I found to think about it is in a sandwich shop. The customer or the user thinks of what they want, then they tell the clerk or the CONTROLLER their order, (BLT, ham sandwich, etc), and then the clerk goes over to the sandwich station or MODEL to make your sandwich. Then Boom your sandwich is done and it is presented to you and this is the VIEW. So it went from the user -> controller -> model -> view. Now we can apply this to how something like Youtube works. You have a lot of subscriptions so you think, "Hey I want to see my subscriptions," and you click subscriptions, you then see all of your subscriptions. sounds simple right? The controller is the request made by the click to see your subscriptions. Then the request pokes YouTubes 'clerk' or controller and it tries to make the 'sandwich'. It searches the database on the servers and collects all your subscriptions, just like ingredients; this is the model. Then all the subscriptions are presented to you like a 'sandwich', and this is the view. In a web framework, the controller can handle the incoming requests which are specific URLs invoked by users. The model is how the back end sees that request to then push to get resolved if it is successful, the page the user requested will show, if not the 404 pages most likely will show. This same concept is used when Creating, Retreiving, Updating, or Deleting objects, also known as CRUD. The ability to modify data in the database which is attached to the users request to the controller. 

## Design patterns? Why we use them?

Just as in nature many creatures exhibit similar traits that over the eons have evolved to have the best attributes to survive. There are many unique traits, but some are more prevalent than others, these are the most optimal, and through natural selection are the most suitable for the given circumstances. Design patterns are a development process that uses tested, and proven design and development patterns. Why reinvent the wheel when it's already in front of you. The same reason humans copy and often reflect upon nature is the same reason we use design patterns. The pattern above is mostly an architectural pattern but also inflects different layers dependent on specific needs. We use patterns to essentially skip the testing and trial and error that comes with finding a successful method for development. And using the same patterns decreases issues that come with writing code, increases readability, and can be read by anyone who learns these patterns. Especially in big companies, many developers can go in and out, they write code, and if no patterns are set in stone when new developers come by they are mostly confused by the code. And in fear of breaking the system, they likely don't mess with it. 

## What patterns I have used in this class

When developing web apps we have an MVC design pattern in mind, for the most part. We have layers in which we store specific pieces to our program. By doing this it is well organized and anyone looking into our code can see what is going on if debugging/ aid is needed. This is especially important in the development team. In our final project, it is paramount that we have a design pattern in mind as multiple developers are working on the same website application. This avoids a lot of key problems mentioned above and is noticeably faster to understand what other developers are doing with their issues. Specifically, we use the MongoDB collection for the Model. The view is what the user sees, the user interface, how the user interacts with the database. And the controller is react-router which is a centralized request hander mechanism which is a front controller design pattern and has the ability to handle request from the client which can do authentication, authorization, and login in, then passes that request on to a handler
