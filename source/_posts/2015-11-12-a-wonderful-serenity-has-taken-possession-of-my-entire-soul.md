---
layout: post
title: "Hashes vs Array"
date: 2016-02-16 16:39:18
comments: true
description: "The difference between hashes and arrays"
keywords: "hashes, arrays, differences, values, keys"
categories:
- Hashes and Arrays
tags:
- welcome
---

Hashes vs. Arrays
James Melonides
CS 2nd blog post

Hashes and arrays are very similar, but are used very differently. An array can be thought of as just a list, or a collection of data in a random order. Numbers are assigned to the items in the array, based on the order that they are listed in. For example, if I had donuts = [“boston crème”, “glazed”, “old fashioned”], to call up chocolate glazed, I would say donuts(1), because glazed is the second term in the array, which including zero, is number one in the array. The key in the array is the integer that you use to access it, and the value is what is returned. A hash is different because it is a list of pairs of information, with a pair consisting of a key and a value. You can use this key to access the value that it is paired to. For example I could input donut as my key, and return glazed as my value. A hash looks more like, food = {“donuts” => “boston crème”, “soup”  => “chicken noodle”, “pizza” => “sausage”} Each of the values (the more specific foods are assigned to the keys, which are the broader foods. When trying to access the values for the hash, you have to type, food[“soup”] which will return chicken noodle. There are many different situations in which to use either hashes or arrays. The main difference is that with hashes you can use specific names to call up values, where as in arrays you have to use an integer. Arrays are usually quicker to use if they are short enough. With hashes it is easier to keep track of the key that you want to use to access a value. There are also many specific things you can do with hashes that you cannot with arrays and vice versa.

















https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63
https://teamtreehouse.com/community/when-do-you-use-an-array-versus-a-hash-in-ruby


http://www.sitepoint.com/guide-ruby-collections-ii-hashes-sets-ranges/





