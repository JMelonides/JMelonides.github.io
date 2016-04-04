---
layout: post
title: "Ruby Classes"
date: 2016-04-04 16:39:18
comments: true
description: "How classes work in Ruby"
keywords: "Ruby, classes, methods, instance variables"
categories:
- Ruby Classes
tags:
- welcome
- done

---

James Melonides
Computer Science
Ruby Classes

class User
	
	def initialize(email, password, birthdate, username)
		@email = email
		@password = password
		@birthdate = birthdate
		@username = username
	end

	def change_password(new_password)
		@password = new_password
	end

	def password
		@password
	end

	def login(email, password)
		if @username == username && @password == password 
			puts "access confirmed"
		else 
			puts "denied"
end

james = User.new("email", "password", "birthdate", "username")
puts james.password

	In this program displayed above, we created a ruby class. We defined this class as User, and it can be used to create a profile, and login to it. Classes are a way to store information, like Hashes or Arrays. Creating a class is helpful to programmers as it helps you to manage all your variables and methods. Classes make your life a lot easier, and they are used to combine methods. You can write methods independently of each other, but using a class combines them together. You could just store your data in hashers or even arrays, but that would be incredibly inefficient if you want to move the data around, or if you have store a large number of instances. If you store your data in an Array, you can’t really do anything, but with a class you can do a lot more with your data. In the program above I created a class called User. The next step for me was defining the initialize method. This method allows us to skip a few steps and incorporate all of these steps into one. Under the initialize method are things called instance variables, which is the @email = email. You designate an instance variable using the @variable_name notation, and you'll be able to use it the same way for every instance of the User but it will have a unique value for each. There are also to types of methods, reader and writer. These differ in a couple ways an you usually need both when creating a class.  As seen in my code, you can do a lot with these variables. Things to avoid when trying to use classes is spelling initialize wrong. If you do this, your code won’t work at all. Another thing to be mindful of is your placement of the end. You have to be careful to end every method, and don’t forget to end the class itself.



http://www.tutorialspoint.com/ruby/ruby_classes.htm
http://www.eriktrautman.com/posts/ruby-explained-classes
http://stackoverflow.com/questions/5046831/why-use-rubys-attr-accessor-attr-reader-and-attr-writer



