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

## Design patterns? Whats that?

Just as in nature many creature exhibit simular traits that over the eons have evolved to have the best atributes to survive. They're are many unique traits, but some are more prevalent than others, these are the most optimal and through natural selection are the most sutible for the given circumastances. Design patterns is a development process that uses tested, and proven design and development patterns. Why renvent the wheel when it's already infront of you. The same reason humans copy and often reflect upon nature, is the same reason we use design patterns. 
