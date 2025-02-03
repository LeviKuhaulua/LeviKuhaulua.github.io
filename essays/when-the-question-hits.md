---
layout: essay
type: essay
title: "When The Question Hits"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: true
labels:
  - Learning
  - Software Engineering
  - How-to
---

<img class="img-fluid" src="../img/asking_good_questions.gif" width="250px" height="250px">

## Communication Is Key

I remember back when I was working as an IT Technician at Hawaiʻi Pacific University, I would come across service tickets that had subject lines like *why can't I sign in* or *unable to connect to the internet*, once I opened and checked the description, I was met with the same text at the subject. This led to a back-and-forth. Question, then a reply, then another question, followed by another reply. All of this was done to zero in on what is the cause of the problem, then figure out an appropriate resolution method. What annoyed me was that for some of these problems, if the person had included an error message or some additional context, it would've been an easy fix to apply. 


This little anecdote highlights that if you don't include the right information, then you will not get the help that you're expecting. One way to provide some additional context is... to ask the right questions. When you ask the right questions, you will help others in understanding where you are confused and help them to find the right information to guide you closer to a solution. 

## Asking Questions Is A Process

In order to ask the ***right*** questions, we have to understand what makes a good question. Based on the guidelines outlined by Eric Raymond in [*How To Ask Questions The Smart Way*](http://www.catb.org/esr/faqs/smart-questions.html#asking), your question should have these traits: 

- It's specific, in other words, it doesn't beat around the bush and highlights what exactly you're confused about
- Includes relevant and specific information. Think of things such as:
    - Error logs
    - Code snippets
    - Output of code
- Include details on what you have tried and what happened when you tried those resolution methods

By following this, you help people with narrowing down the issue and coming up with advice/information that is much more specific to your problem. 

## When The Question Doesn't Hit

Let's take a look at a question that will not get the help that you are expecting: 
 
> My django server is not working properly. When I load my website it shows nothing. How can I fix this problem, I checked all my setting and views.py, and urls.py all are ok but when i save all these my server loads but when I go to the website and paste the url.. it shows nothing. 
>
> &#8212; <cite>[Stack Overflow Question](https://stackoverflow.com/questions/79396921/i-am-learning-django-the-server-was-working-fine-till-now-but-when-i-created-th)

This question **does not** provide us with enough meaningful information to find out the root cause of the issue. Because of that, we are left to speculate at *everything* that could be the potential cause of the error. At best, we can only provide a solution that is a shot in the dark. Worst case, nobody responds and the user is not getting any closer to working out a solution. 

## When The Question Hits

Here is a question that follows the basic structure for asking the right questions: 

> I am trying to plot a simple graph using pyplot, e.g: 
> ```python
> import matplotlib.pyplot as plt
> plt.plot([1,2,3],[5,7,4])
> plt.show()
>```
>
> but the figure does not appear and I get the following message:
> >`UserWarning: Matplotlib is currently using agg, which is a non-GUI backend, so cannot show the figure`
> 
> **...**
> 
> How can I make the Matplotlib display the graph?
> 
> &#8212; <cite>[Stack Overflow Question](https://stackoverflow.com/questions/56656777/userwarning-matplotlib-is-currently-using-agg-which-is-a-non-gui-backend-so/56675620#56675620)

Here, we are given relevant information as to what exactly the user wants to accomplish, which is making Matplotlib display the graph the user created / programmed. The error message attached help us to understand what exactly is happening and why the graph is not displaying. In this case, we can come up with a solution that is *guaranteed* to help the user get closer to solving their issue with pyplot. 

Overall, the difference between a good and bad question is the information we provide for it. If we look to adding relevant and meaningful information to our questions, we can exponentially increase the quality of help that we can receive. 
