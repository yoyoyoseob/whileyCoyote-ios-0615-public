---
tags: while_loops, todo
languages: objc
---

# While-yCoyote

## Instructions

As long as While-y Coyote is following us, we'd like to make sure we keep one step in front of him. And the thing is, While-y is wiley! And all we know is that the anvil we setup to flatten him into the ground won't hit him until he has run 50 steps. Let's keep saying "Meep Meep" until we hit that number.

In order to stay ahead of while-y, we'll need a new type of loop called a do-while loop. A do-while loop runs until a certain condition is met. The syntax for a do-while loop looks like this:

```
do
{
	
	//whatever you want to do goes here.

} while (/*some condition has not been met*/)
```

Additionally, While-y will hold up a sign that says "YOU'RE CUCKOO." every 10 steps he takes (because as we all know a road runner is actually a type of long legged cuckoo bird.) Let's add these into our output log.

So in summary, your output should be 50 "Meep Meeps." in the debugger log with "YOU'RE CUCKOO" interrupting those "Meep Meep"s every 10 steps While-y takes (which, if you think about it, is actually after the 11th Meep Meep since While-y is always a step behind.)

That means you'll need to:

1) Write a do-while loop to make sure all 50 Meep Meeps get written in the log.
2) Use an if statement to ensure that While-y's "YOU'RE CUCKOO" messages happen after every 10 MEEP MEEPs (but starting after the 11th Meep Meep!)

Note: All of your code belongs in the AppDelegate's `application:didFinishLaunchingWithOptions:` method, before `return YES`.

## Advanced

- While-y has really become quite clever and we don't always manage to flatten him the first time that anvil falls. Let's reflect this in our program by making the number of steps he takes a random number before the anvil hits him. He is allowed to take no more than 100 steps, and the road runner must always take one more step (an extra Meep Meep) than While-y does. (In other words, if While-y takes 100 steps, there should be 101 Meep Meeps to ensure the road runner doesn't get caught.)
