# 7 Ways to Increase Performance of Python Applications

I've been thinking about what are the key points about making Python applications run faster. Performance is a huge topic and there are so many subtle issues, potential traps, conceptions and misconceptions.

IMHO, these are the key points to improve the performance of Python applications.

## 1. Measure performance
As the saying goes, you need to measure in order to improve. Otherwise, how would someone even know that any supposed improvement really worked or not? Without measuring, we can just do any placebo fix and declare it's an improvement.

True story: a few years ago, my car's engine was a bit noisy. The mechanic told me: '*look, I have this awesome engine oil which is going to make the engine run silently*'. I agreed to do it and I even measured the engine noise with one of those mobile apps that measure noise intensity. 
After changing the oil, the mechanic looks at me triumphantly and declares: '*Listen to the engine, it's so quiet now*'. Indeed, it almost sounded quieter. Just to be sure, I pull out my mobile and start measuring the noise. Guess what: it was the same noise level 😄.

Bottom line: measure performance or else I'll send you to that car mechanic.

## 2. Use the right data structures
Python has various data structures which work best in different scenarios. 

Remember the funky big O notation? Well, it's not just some theoretical BS, it really stings when performance matters. You just need to watch out for a few data structures and your Python applications are going to run faster.


## 3. Optimize Python code

This might sound a bit generic, since even using the right data structure is a form of optimization, right?
There is more to it. Think about caching: it's relatively easy to implement and it has a dramatic impact on performance.
The idea is to collect a bunch of concrete tactics that result in clear performance gains.

## 4. More threads
Sometimes your Python application might wait for something. Multithreading can improve performance. Still, multithreading has plenty of challenges.

## 5. Asyncio
Asyncio is friendlier than multithreading. It's a great choice for IO-bound workloads.

## 6. More processes
Using more processes enables significant performance improvements, if you can split your workload. 

## 7. More machines
One machine might not be enough, so then just scale from one to more machines. Google does it. For example, use something like Kubernetes which takes care of a lot of the serious issues that occur when working with distributed systems.





