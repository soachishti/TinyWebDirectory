TinyWebDirectory
==============

TinyWebDirectory is lightweight  
web directory with builtin 316 
categories.

Requirements:
------------
* PHP > 5
* mySQL

Features:
------------
* Packed with 316 Categories.
* Support Reciprocal Link.
* Unlimited sub categories of Categories.

Screen Shot:
------------
Front Page

![Front Page](http://i.imgur.com/KRFQJjt.jpg)

Category page

![Category page](http://i.imgur.com/weqkIkH.jpg)

Database Structure:
------------

category
	|
	|-	id
	|-	name
link
	|
	|-	id
	|-	link
	|-	name
	|-	desc
	|-	rel_id
	|-	email
	|-	approve
	|-	time
relation
	|
	|-	id
	|-	cat_id
	|-	child_id