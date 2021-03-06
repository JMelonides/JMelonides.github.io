---
layout: post
title: "If vs. Case Statements"
date: 2016-02-16 16:39:18
comments: true
description: "The difference between case and if statements"
keywords: "case, if, statments"
categories:
- Case vs. If statements
tags:
- welcome
- done

---

In Ruby, there are if statements and case statements. Both of these statements serve essentially the same purpose; but can be used differently. If statements are conditional, meaning if one thing happens, the code will return something, but if something else happens, the code will return a different value using the elsif and else commands. What happens depends on if the conditional is true or false. Case statements are when use the when command and compares the expression specified by case and that specified by when using the === operator and executes the code of the when clause that matches. These two statements serve the exact same purpose, but there are some differences. It is much quicker to type case statements, and they are often more concise if the value you want falls in a range of values. However, it uses the operator ===, which if used too much, can make your program slower and less efficient. If statements take more time to write and don’t look as pretty, but it allows you to execute your code faster that a case statement would. However, in shorter codes, the nanoseconds this saves when running your code is meaningless, and only matter you need to repeat these statements a lot as the time it would take to run the program gets a lot greater. Also, ruby is not designed to be a fast language, it is designed to easily read which is why I would recommend using case statements. They are easier to read, faster to type, and save time. There are certain times where if, else, and elsif statements work better, but they are few and you don’t find yourself in the situation where you need to use them a lot.



http://midwire.github.io/blog/2011/08/26/ruby-performance-case-vs-if-elsif/
https://www.ruby-forum.com/topic/4404937
https://teamtreehouse.com/community/if-elsif-else-statements-vs-case-statements

