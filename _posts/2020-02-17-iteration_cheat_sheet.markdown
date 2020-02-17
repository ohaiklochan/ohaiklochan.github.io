---
layout: post
title:      "iteration: cheat sheet"
date:       2020-02-17 05:18:23 +0000
permalink:  iteration_cheat_sheet
---

Let's talk about some iterators for ruby.
 ```.each
 .map or .collect
 .select
 .find```
 
 # .each
 
 `.each` is probably one of the most used iterations I use in my code to make the code work 'with' something instead of 'to.'
 
 ```[1, 2, 3, 4, 5].each do |element|
            puts element
			end
			
			
			#=> 1
			         2
							 3
							 4
							 5```
 
 # .map or .collect
 
 `.map` or `.collect` essentially do the same things - can return a new array with the same length as the original array given.
 
 ``` [1, 2, 3, 4, 5].map do |element|
               element + 1
				end
					
					
					#=> [2, 3, 4, 5, 6]```
					
# .select
`.select` is based off your stipulations. For example:

```[1, 2, 3, 4, 5].select do |element|
             element < 3
			end
			
			#=> [1, 2]```
			
			
# .find
`.find` returns the first element in the array that meets the criteria

```[1, 2, 3, 4, 5].find do |element|
           element.even?
		 end
		 
		 
		 #=> 2```

