---
layout: post
title:      "Technical blog"
date:       2020-08-10 01:42:26 +0000
permalink:  technical_blog
---


My CLI project is essentially a Jeopardy practice command line, which utilizies the jservice api and helps the user who potentially would like to be on the game show,  to practice. The user is first greeted and then shown a list of questions which is generated from the response given back from the api class. The user then must pick which question they would like to learn more about from a series of questions, or they may pick a random question to pratice. The questions and answers are pulled from the Jeopardy class, and inorder to get that information, I use a loop to iterate through my @@all array in my Jeopardy class and return that instance, and it's accessors such as questions, answer, title, etc. To get the random question, i added a second api method using a different url to pull a random question. The whole command line loops through with a series of if/else statements until the user specifies they would like to "exit"
