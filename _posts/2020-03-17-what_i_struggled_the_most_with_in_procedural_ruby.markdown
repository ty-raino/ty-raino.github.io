---
layout: post
title:      "What I struggled the most with in Procedural Ruby"
date:       2020-03-17 02:53:27 -0400
permalink:  what_i_struggled_the_most_with_in_procedural_ruby
---


The one thing I struggled the most with was While Loops and Until Loops. While learning a little on this topic in Javascript, loops has always been a method that I couldn't quite grasp. With the help of my cohort lead, I understand a little on how While and Until loops operate. My current understanding of a While loop is that the loop will keep looping until it's false, meanwhile an Until loop is the exact opposite logic. It will run until it's true. I've also made an document breaking down the two loops. 

```i = 0
while i < 5
puts "hello"
i += 1
end```

In the code snippet above about a While loop,  `i` is set to `0`,  While evaluates if `i` is less than `5`.  `i` is in fact less than `5` which is "true", so it will run our string. Then increment the variable by 1, so that it goes from 0 to 1. 1 is less than `5` so it will jump back to the beginning and loop over until it's false, which is `5 < 5`. 5 is not less than 5 (it is equal to 5) so this is "false" and the loop will end.

```i = 0
until i >= 5
puts "hello"
i += 1
end```

A Until loop is the opposite logic. The loop evaluates if `i` is GREATER than or equal to `5`.  `i` is NOT greater than `5`, which is considered "false" so this will run the loop. Then increment the variable by 1. 1 is not greater than `5` so it will jump back to the beginning and loop over until it's true, which is `5 >= 5`. 5 is not greater than, but it is equal to 5, which is "true" so this will end the loop. 
