---
layout: post
title: "Class Inheritance"
date: 2016-04-14 16:39:18
comments: true
description: "Class Inheritance"
keywords: "Class, Inheritance, super, umbrella, sub-class"
categories:
- Class Inheritance
tags:
- welcome
- done

---

Class Inheritance
James Melonides

class Automobiles

	attr_accessor :gas_tank, :color, :horsepower
	
	def put_gas_in_car(gas)
		@gas += gallons

	end
end

class Jeep < Automobiles

	attr_accessor :tire_on_the_back, :four_wheel_drive
	def tire_on_the_back
		puts "Your jeep has a tire on the back."
	end

	def four_wheel_drive
		puts "Your car is capable of providing power to all wheel ends of a two-axled vehicle simultaneously."
	end
end

Class inheritance is very useful to shorten code and cut down on redundancies. By using class inheritance we can make an umbrella class with its own attributes, and all of those attributes apply to the classes that are put under the first class. By doing this, you don’t have to include the same attributes into every class. Also all methods will be inherited from the umbrella class. For example, in the code above, the attributes :gas_tank, :color, :horsepower are all inherited by the Jeep. Therefore, we do not need to include those attributes again in the Jeep class. Also, the method put gas in car works for the Jeep as well because it is under the Automobiles class. You may also include new more specific attributes and methods under your subclass that don’t apply to the umbrella class. For example, the attributes :tire on the back and :four wheel drive, don’t necessarily apply to all automobiles, but they apply to almost every Jeep. This saves time and writing and is almost necessary when writing longer code with classes that are related to each other. You can keep nesting classes as long as you want, so if have a lot of related classes you can cut down on time. There are times when a sub-class may not fit under the umbrella class exactly. For example, an electric car does not have a gas tank and won’t have all the attributes of the automobile umbrella class. To override that attribute, you can write a method that says def put_gas_in_car(gas) and then puts “Sorry, I don’t have a gas tank. The only thing that can’t be inherited by sub classes are instance variables. If a subclass uses an instance variable with the same name as a variable used by one of its ancestors, it will overwrite the value of its ancestor's variable. Overall, class inheritance is a useful tool when used correctly.




