---
layout: post
title:      "Sinatra Project"
date:       2020-10-04 16:37:48 +0000
permalink:  sinatra_project
---


My Sinatra project is task-manaegement website that lets users create tasks to help them with day to day organization and time/task-management. The user is first presented with the index page through the get method in the application controller. The are presented with an option to either login or sign up. The sign up page redirects them to a form to sign up, login page redirects them to a login page, and once user inputs username and password, they are redirected to a homepage, in which they can create, edit, read, and delete tasks. The applicatiton controller controls my routes depending on the links clicked in the view's .erb files. Sessions is implemented to know to keep track of each user's session, and I use helper methods to help to know when a user is logged in or not. 
