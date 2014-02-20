---
layout: post
title:  "Don’t be misled by your A/B testing - Part 1"
date:   2014-01-29 17:02:08
categories: jekyll update
comments: true
---

## Isn’t A/B testing just “40% is better than 30%”? ##
 
You have a product and want to encourage more people to complete a specific task. You have 2 ideas, you decide to A/B test them to see which is better. 

So, you put your users into two groups (A and B) where each group sees a different solution, and then measure which group is more successful at completing the task.

After 200 total tests, 30 out of 100 people in Group A completed the task, while 40 out of 100 people in Group B completed the task.
 
The answer is obvious: B is better than A, right? 
 
*Not necessarily.* 

## Why can’t I simply compare 40% with 30%? ##

Let’s take a look at group A. In this group, you observe 30 successful outcomes. However, it is just one observed number. If you run the experiment again, you may see 35 or 22. If you do it many times, the number of successful outcomes follows the Normal Distribution curve. 


See the shadowed part of the image above? 95.45% of the possibilities fall into an interval, which statisticians call the Confidence Interval. For our example, we can get the confidence interval for each group using a standard formula.

Group A: [21%, 39%]
Group B: [30%, 50%]

What does this mean? It means that although you observed 30% for group A, and 40% for group B, the possible result is [21% ~ 39%] for A and [30% ~ 50%] for B. Do you still think group B is definitely better than A?

*Maybe not.* 

