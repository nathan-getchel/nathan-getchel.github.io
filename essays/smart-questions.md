---
layout: essay
type: essay
title: "Better Questions Yield Better Answers"
# All dates must be YYYY-MM-DD format!
date: 2023-01-26
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

## Where can we go to ask questions?

Stack Overflow is primarily a Q&A website for developers to ask questions and seek input from other developers about problems in their code. But are all questions created equal? Depending on how a question is asked, a user might receive multiple helpful and insightful comments from other users. On the other hand, they may receive nothing but downvotes if the community thinks that the question is unclear, not descriptive enough, or (sorry) just plain silly.

## A Less Than Stellar Example

For an example, let’s take a look at [this question about for loops in Java.](https://stackoverflow.com/questions/75196945/java-for-loop-loops-infinitely-but-there-seems-to-be-no-reason-why) The user is trying to write a basic nested for loop, and they say that their code is looping infinitely. In order to not seem too harsh, I will note that they at least provided the actual code so that others can see it. However, after reading on a bit, it immediately becomes clear that the user asking this question has not even attempted the most basic troubleshooting steps on their own, or they would have noticed the glaringly obvious error on line 3 that is causing the infinite loop. I would hazard to guess that they copied and pasted line 1 down to line 3 and forgot to change one of the “y”s to an “x.” Answers from other users are short and reflect their annoyance. To be fair, the responses did point out the issue, but it’s such a simple fix that it didn’t exactly cost anyone much effort to help out. The user could have simply read their code a bit more carefully to solve this problem, or even asked a classmate for help if necessary, but instead they went through the time and effort to make a post about it and forever enshrine their shame on the internet.

## A Fascinating Question and a Satisfying Answer

As a counterexample, take a look at the effort that went into [this question about processing arrays.](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array) This user has noticed that processing a sorted array takes much less time than an array of the same data, but unsorted. They first noticed the phenomenon in C++, and then went ahead and wrote a Java program to do the same exact thing in order to compare. With Java they experienced a similar result. This does seem to beg the question as to what is causing this behavior, and after expending the effort to write it over again in another language it seems reasonable to turn to a public forum for answers. In fact, this question is the most highly upvoted question currently on Stack Overflow, with a quality answer to match. The response that this user received was an extremely detailed and well formatted description of branch prediction.

## The Bottom Line

We’ve all heard the phrase “there are no stupid questions”, and while we certainly wouldn’t want to discourage learners with gatekeeping, it is clear that well thought out, descriptive questions yield better and more insightful answers, and part of the process of asking a good question is first trying to solve the problem yourself. In this way you will be able to narrow down the issue, learn more about the topic you’re struggling with, and you may even just solve it yourself along the way.
