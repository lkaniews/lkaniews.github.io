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

	A hash and an array hold similar characteristics yet they are used at different times. You are probably thinking about hash browns and confused as to why we are comparing food to an array. Unfortunately, this is not about food, rather two types of commands used in programming languages. (I know, I wish it was about food) By definition, an array is a “data structure” where one can gain access to different elements by “indexing.” So an array in short, is a list. An array can look like this: food = [“tacos”, “pizza”, “pasta”] and to access one of the items we would put food[0] and in return we would get tacos. On the other hand a hash is a “data structure that stores items by associated keys.”  Entries in a hash are called “key value pairs.” Hashes are created using “symbols as keys and any data types as values”  A hash is a collection of pairs. And a ‘=>’ is used to separate them. An example of a hash is: 
main = {
	style: ["burrito", "bowl", "crispy corn tacos", "soft corn tacos", "soft flour tacos", "salad"],
	meat: ["steak", "carnitas", "chicken", "barbacoa", "sofritas"],
	rice_bean_veg: ["cilantro-lime brown rice", "cilantro-lime white rice", "black beans", "pinto    beans", "fajita veggies"],
	toppings: ["sour cream", "guacamole", "cheese", "romaine lettuce", "roasted chili-corn salsa", "tomatillo green-chilli salsa (medium hot)", "tomatillo red-chilli salsa (hot)", "fresh tomato salsa (mild)"]
}

As you can see, there are many sub categories in this hash which represents the menu at Chipotle. In order to access a value, say “guacamole”, you must put      main[:toppings][1]. So an array is a list while a hash is a collection of values and their pairs. Now, when do we know to use a hash or an array?  If you need data to be under a specific label then use a hash. What if order matters in the list? Then use an array. It would be more beneficial to use a hash when it comes to creating more complex lists where values need/can be stored under sub categories of the main category. So, while similar, hashes and arrays are different, a hash being a collection of information pairs and an array being a collection of data. 

 https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63
 https://launchschool.com/books/ruby/read/hashes
 https://apcswshs.wikispaces.com/Arrays