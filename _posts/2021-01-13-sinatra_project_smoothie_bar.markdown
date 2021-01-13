---
layout: post
title:      "Sinatra Project/Smoothie Bar"
date:       2021-01-13 18:28:49 +0000
permalink:  sinatra_project_smoothie_bar
---


My Sinatra project is a smoothie bar website that lets users create smoothie entires, edit, and delete. The user is first presented with the index page through the get method in the application controller. They are presented with an option to either login or sign up. The sign up page redirects them to a form to sign up with their name, password, and email. If already signed up, can click to login, and once user inputs username and password, they are redirected to a welcome page, in which they can create, edit, read, and delete tasks. The applicatiton controller controls my routes depending on the links clicked in the view's .erb files. Sessions is implemented to know to keep track of each user's session, and I use helper methods to help to know when a user is logged in or not. 
