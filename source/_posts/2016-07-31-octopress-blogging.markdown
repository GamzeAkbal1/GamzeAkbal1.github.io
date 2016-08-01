---
layout: post
title: "WORKSHOP'S NOTES"
date: 2016-07-31 21:36:39 +0300
comments: true
categories: 
---

 




###WHAT IS RUBY ON RAILS?###

*Ruby on Rails (RoR) or Rails is an open source web application development framework written Ruby language which is based on Model-View-Controller(MVC),Dont Repeat Yourself(DRY) and Convention over Configuration  (CoC) approch.*

###Well What are these ?###

###Lets start with MVC!

*MVC is an architectural pattern which is used software engineering.*

**MODEL**

  * Represent the data used in practice and is part of the processing logic of the stored data.
  * To save the data in the database or get the records in the database.

**VIEW**

  * This part that users see.

**CONTROLLER**

  * Performs bring in taking action between Model and View.
  * Controller sends data to the Model received from the View or sends data to the View received from the Model.
  * Basically Controller is a bridge between Model and View.


![mvc](http://kodbas.com/wp-content/uploads/2014/04/Beh3a.png "mvc diagram")



###DRY

*According to DRY principle programmer should avoid writing again same code blog during the coding*

*  WITHOUT DRY;
```sh
	if ( repo.data( "currently" ) !== "showing" ) { repo.stop(); }

	if ( repo1.data( "currently" ) !== "showing" ) { repo1.stop(); }

	if ( repo2.data( "currently" ) !== "showing" ) { repo2.stop(); }
```

*  WITH DRY;
```sh
	var repos = [ repo, repo1, repo2 ];

	$.each( repos, function( i, rep )

	{ if ( rep.data( "currently" ) !== "showing" )

	{ rep.stop(); } });
```

###CoC

*Convention Over Configuration concept to reduce the time during configurations deal of developer and is used to reduce human-induced errors.*
*Ruby on Rails framework is an example of a framework that uses this concept.*
*Let's say that our application with a class map table in the database. single developer writing of that map which field which column in this class is a job that is error-prone and time costs*
*If the developer following naming rules the this class will be set  which field  mapping to which cloums*




