---
layout: post
title:      "Sinatra CRUD App"
date:       2018-08-24 00:41:47 +0000
permalink:  sinatra_crud_app
---


I have titled my CMS App Assessment project DBCA; short for Database California.  This app includes an MVC framework that uses the ActiveRecord ORM.  This app includes full CRUD capabilities and to facilitate this capability I have created three basic models: User, Organization and Category.  Likewise, I have created three controllers: UsersController, OrgsController and CatsControllers.  Additionally, I have organized the views to include forms to create/edit objects.  Together they are presented with restful routes.  

The intent of this app is to allow users to create an account, add organizations and assign a category to their organization. The home or index page displays a table of existing organizations as well as a list of existing categories.  The organization is sorted based on a simple algorithm that factors the user account level and the number of times the organization has been viewed.

The app is rudementry whose intent is to offer simple CRUD functionalities.
