---
tags: while_loops, todo
languages: objc
---

# While-yCoyote

## Instructions

As long as While-y Coyote is following us, we'd like to make sure we keep one step in front of him. And the thing is, While-y is wiley! And all we know is that the anvil we setup to flatten him into the ground won't hit him until he has run 50 steps. That means, we need to run 51 steps to ensure we don't get hit by the anvil and also stay ahead of While-y. For each step we take, let's output "Meep Meep."

In order to stay ahead of while-y, we'll need a new type of loop called a do-while loop. A do-while loop runs until a certain condition is met, and the key is, it is always run once, because the code inside the brackets comes before the logic (after the word while). The syntax for a while loop looks like this:


```
do
{
	
	//whatever you want to do goes here.

} while (/*some condition has not been met*/)
```

Additionally, While-y will hold up a sign that says "YOU'RE CUCKOO." every 10 steps he takes (because as we all know a road runner is actually a type of long legged cuckoo bird.) Let's add these into our output log.

So in summary, your output should be 51 "Meep Meeps." in the debugger log with "YOU'RE CUCKOO" interrupting those "Meep Meep"s every 10 steps While-y takes (which, if you think about it, is actually after the 11th Meep Meep since While-y is always a step behind.)

That means you'll need to:

1) Write a do-while loop to make sure all 51 Meep Meeps get written in the log.

2) Use an if statement to ensure that While-y's "YOU'RE CUCKOO" messages gets written to the log after every 10 MEEP MEEPs (but starting after the 11th Meep Meep!)


Note: All of your code belongs in the AppDelegate's `application:didFinishLaunchingWithOptions:` method, before `return YES`.

## Advanced

- While-y has really become quite clever and we don't always manage to flatten him the first time that anvil falls. Let's reflect this in our program by making the number of steps he takes a random number before the anvil hits him. He is allowed to take no more than 100 steps, and the road runner must always take one more step than While-y to keep from getting caught (aka an extra Meep Meep). 
