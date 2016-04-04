---
layout: post
title: "When to Use Array's vs. Hash's"
date: 2016-02-04 09:12:00
comments: true
description: "Array's and Hash's"
keywords: "statements"
categories:
- welcome
- Third Post: 
tags:
- array
- hash
- programmer
---
Ruby is an Object Orientated Programming Language. But, what does that mean? In object oriented programming, the objects are floats, integers and strings (nouns) and the methods are verbs they are actions or events that happen to objects. In app building the components are the objects (buttons, sounds etc) and the methods are the events that happen to the object. In Object Orientated Programming in Ruby, there are classes and objects. Think of it as a box of penne pasta where the class is the box of penne where the individual pasta meals are “instances of the class of objects known as”  pasta. The pasta is the outcome of the class and can be manipulated many ways depending on what sauce and toppings are added to it such as cheese, butter, tomato sauce, vegetables and meat once the action of cooking the pasta is applied. Here is an example of a class: 
class Penne
	def cook_time=(time)
		@time = time
	end

	def cook_time
		return @time
	end 
end 
	The highlighted purple is the class and the purple end is ending the class. And the attributes to penne pasta are in the class. The class is setting up for all of the attributes that can be individualized to create a unique bowl of pasta. You can store variables under the class such as amount, sauce, cook time and more. An object is an instance of some type of class. The object being a string, array, hash or numbers. In classes, we use instance variables. The instance variable is defined the same way for each bowl of penne and is used the same way but the value it holds is unique for each bowl. For example, serving is an instance variable, it can be manipulated for each unique bowl of pasta. Classes are efficient and an instance where they have and can be used is in storing user data for a profile of maybe Facebook or another form of social media. The class would be User and then the instance variables could be manipulated to personalize the profile for each person. Other attributes for a User profile could be email, username, and password. For each attribute, there is a reader and writer method. 
class User
	def name=(name) 
		@name = name
	end
	def name
		return @name
	end
			
	def location=(location) 
		@location = location
	end

	def location 
		return @location
	end

	def username=(username)
		@username =username
	end

	def username 
		return @username
	end
end

Here, the underlined portion is the reader method while the bold portion is the writer method. The writer method ‘writes’ and sets the attribute while the reader method is the getter, getting what we want from the class. One thing to know about classes is that when defining them, make sure that the first letter of it is alway capitalized. See above, the ‘P’ in “Penne” is capitalized. So overall, a ruby “class is the blueprint from which individual objects are created.” (tutorialspoint.com)

http://www.eriktrautman.com/posts/ruby-explained-classes
http://www.tutorialspoint.com/ruby/ruby_classes.htm
http://searchsoa.techtarget.com/definition/object-oriented-programming

