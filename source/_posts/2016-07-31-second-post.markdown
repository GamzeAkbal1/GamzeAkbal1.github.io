---
layout: post
title: "WORKSHOP'S NOTES"
date: 2016-07-31 21:48:10 +0300
comments: true
categories: 
---
*To be honest i didn't understand many things because im starting late and i had no prior knowledge about rails Generally i try to catch up the others when i try to errors they  move on the another topic but it was a great opportunity and exprience for me.Thanks to workshop i believe i can learn easily ruby on rails in the linux camp.*

###ORM

*ORM  for every object in the database generates an object in the code side*
*These programs use code generation technique produces automatic code we need to write.*

Lets try ActiveRecord

First step  we're going to install;

```sh
	
	$gem install activerecord

```

Than lets use

```sh

	require 'rubygems'
	require 'activerecord'
	ActiveRecord::Base.establish_connection(
	:adapter=> "mysql",
	:host => "localhost",
	:database=> "articles"
	)

	class Article < ActiveRecord::Base
	end

	#Creating a new article
	Article.create(title:'ORM', author:'Manu')

	#Fetching an article
	article = Article.find(:first)

	#Destroy an article
	Article.find(:first).destroy \\find takes id u can write "txt" 

```
