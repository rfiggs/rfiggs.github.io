---
layout: essay
type: essay
title: MeteorJS
date: 2016-10-20
labels:
  - Software Engineering
  - Learning
  - JavaScript
  - Web Development
  - MeteorJs
---

Meteor is a new modern full stack developing platform.
Previously in web development, you need separate software for the server, the database, and the browser.
All three of these would generally be in different languages.
In Meteor everything is in JavaScript, from the database all the way to the front end.
This makes developing apps much quicker and easier to understand.
What really makes Meteor unique however, is how the client interacts with the server.

According to web standards, the process to load a website starts with the client sending a request to the server, and then the server sends back the webpage that the client requested.
This is how websites have loaded for a long time now, and it works well until you have multiple users looking at and editing the same piece of data.
When one person makes an edit, it needs to be reflected on the other users screen.
Since a client needs to make a request before the server can send information, how can the server notify the client it needs updating?
The current method is something called AJAX, asynchronous JavaScript and XML.
Basically in the background of the web app the client is constantly sending requests to the server and checking for changes.
Meteor was designed with this issues in mind, so it is much easier to make pages with live updates in Meteor, than it is in other frameworks.

To accomplish this, Meteor uses a system of MongoDB databases, one on the server, and one for every client.
The database on the server contains all of the information that the app needs.
The database on the client is more like a mini database.
This mini database is simply a small subset of the data that is on the server.
The mini database only contains information that that client needs.
The magic of Meteor is that it keeps these databases up to date with each other without much effort from the developer.
If there is an update on one of the clients Meteor will update the server's database.
If there is a change to the server's database, it will push the update to any other clients that are viewing that data.

I have enjoyed learning and using Meteor.
Meteor has been much easier to learn and use than the other web development technologies I have learned, like JavaEE.
The fact that everything is in one language, JavaScript, has made it much easier to develop and trouble shoot code.
I also appreciate that by default a Meteor project will work without any security measures.
You can easily remove the insecure packages and slowly secure your app.
Meteor is truly the future of web development.
