---
layout: post
title:      "Looping... A Newbie Approach"
date:       2020-01-25 06:27:24 +0000
permalink:  looping_a_newbie_approach
---


So... Looping is incredibly easy to understand... but if you're not paying attention to your code, well - you're gonna have some trouble. 

Looping essentially is every coder's way of streamlining and making things easy for us. Instead of writing:

```
def say_hello_10_times
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
     puts "Hello!"
end
```

which can be incredibly tedius... we can write it easier by writing something like:

```
def say_hello_10_times
     10.times do
     puts "Hello!"
end
```

which results in the same output. 

There are several types of loops: `while` which repeats the loop as long as the expression is true; `repeat until` which repeats until expression becomes false; infinite or endless loop that will only end by using `break`.

Using these types of loops in your code is incredibly important in undersanding programming. I know that I will continue to use loops within iterations. Can't wait to learn more!
