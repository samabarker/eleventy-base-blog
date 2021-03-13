---
layout: layouts/post.njk
title: Flask Portfolio/Blog Website
date: 2020-05-01T11:30:00.000Z
description: A website built using the Flask microframework
tags:
  - PROJECT
  - PYTHON
  - HTML
  - CSS
---
A portfolio/blog website built using the Flask microframework. The website has several features, including:

* DevBlog - Making use of the mysql-connector package to input, pull and edit data using a MySQL database. Displayed both in full on the DevBlog page, and in summary on the home page.
* Contact Form - Again, the contact form makes use of mysql-connector and a MySQL database to store information. The form is handled using the WTForms framework. The verification make use of RegEx to ensure only certain characters are permitted in certain fields.
* User Registration/Login - Again using the WTForms framework and mysql-connector to input and pull data from the database. The registration form requires a unique username that contain only certain characters (again using RegEx), a valid email address and a password over a certain length. Passwords are hashed prior to storage in the database to ensure security. The current login status makes use of sessions to control access.
* Microblog - Similar to the DevBlog but specific for each individual user. Fully manageable from the front end once a user is logged in, users can add and edit posts, deciding whether to make them public or private. The Microblog database pulls information from the user database to ensure users can only edit their own posts.
* To-Do - A simple to do list where users can add to-do's, and close/reopen when necessary.
* Admin Area - A front-end management area to manage the DevBlog, user registration and all contact form submissions. The Admin Area makes use of the above packages, along with Pythons smtplib and email packages to allow for contact form replies to be submitted from the front end.

Website can be viewed [here](http://sambarker.com).