---
layout: essay
type: essay
title: "Should You Use a CSS Framework?"
# All dates must be YYYY-MM-DD format!
date: 2025-02-25
published: true
labels:
  - Software Engineering
  - Frontend Kine Tingz
---

<img class="img-fluid" height="200px" src="../img/center-div.png">

# The Question

Throughout my Computer Science degree, I haven't had much exposure to the frontend tech that developers use in order to create their websites. We start off with: 

1. HTML &rarr; Markup language for the *web*
2. CSS &rarr; Making our webpage look *pretty* ✨
3. JavaScript &rarr; Making our webpage *dynamic and interactive* 

Not only is CSS & HTML a whole seperate challenge to tackle, it can be just as confusing as a programming language when it comes to styling and laying things out. 

In comes Bootstrap (or Tailwind / any other popular CSS frameworks and/or libraries) to add even more complexity - with it's utility classes, layouts, components - to an already confusing environment. This begs the questions, ***should you use a CSS framework or should you stick with plain old HTML, CSS, JS?***

## What does [INSERT FRAMEWORK HERE] do better at than HTML, CSS, & JS? 

I like to think that [INSERT FRAMEWORK HERE] as modular development for styling and structuring your HTML elements. Modular in the sense that you can pick and choose what styles (utility classes) apply to what elements. You don't have to worry about creating the class(es) and verifying it works; all you have to do is find the right utility class in [INSERT FRAMEWORK HERE] and apply that to your elements `class` attribute to achieve the same effect

There is also so much complexity in making your webpage look nice. You have to worry about colors, typography, spacing, layout, and consistency. With [INSERT FRAMEWORK HERE], they handle initial styling of elements. Attributes font family, font-size, letter-spacing, line-height, margins and padding, and so much more. On top of that, the utility classes can help you achieve the layout you want for your webpage or make it much easier to find / generate colors you can use for your headings, background colors, or gradients. 

[INSERT FRAMEWORK HERE] also can have tons of support / additional features such as icons that are readily available, or components already designed that look nice. 

What does all this mean? Essentially, it makes development of your webpages easier. It provides you the building blocks to implement your idea rather than you having to create the building blocks yourself. 

## What does HTML, CSS, & JS do better at than [INSERT FRAMEWORK HERE]? 

You might be thinking, there aren't that many benefits to using the plain tools rather than some framework. However, that isn't the case. 

First things first, HTML, CSS, & JS gives you **complete control** over how you layout and/or style your HTML elements. With [INSERT FRAMEWORK HERE], you are restricted to the styles that was decided by it. You can't really customize/alter the utility classes (you could, but, you would be throwing away the main benefits of a CSS framework in the first place if you end up doing a complete overhaul). With complete control comes complete freedom in how you want to tackle certain layouts and figure out how to make everything pixel perfect. 

Secondly, [INSERT FRAMEWORK HERE] makes your code so much more unreadable and complex. Bring up an example of a webpage built with Bootstrap or Tailwind -- you will notice so much utility classes for an HTML element that it makes it hard to find what you actually wanted to look for. For HTML, CSS, and JS, you can create a class that can achieve the functionality of however many utility classes of [INSERT FRAMEWORK HERE] that it takes to style just one element. With that class you created, you also can apply it to multiple HTML elements. 

Finally, with many of the CSS Frameworks and libraries, you have to install them. Whether that's through a package manager like `npm` or through a CDN, you're introducing a new layer of complexity, as you'll have to tackle the setup process, (possibly) edit configuration files, verify that styles are being applied to webpages, and make sure that everything in your project builds. With good file organization, you can skip this layer of complexity for set-up, and just do a good old `link rel="stylesheet" src="path/to/style"` or `script type="..." src="..."` to apply your styles or interactivity. 

## What should you choose? 

If you're confused on what to choose, then you are going to need to consider the scope of your project and what **you** want to achieve for this project. Questions like: 

- How big is this project? 
- What is the purpose of this project or what is this project trying to achieve? 
- Do I care about having complete control or am I okay with having pre-determined styles from [INSERT FRAMEWORK HERE]? 
- What's the setup process like for [INSERT FRAMEWORK HERE]? 
- Is there tons of support and guides for [INSERT FRAMEWORK HERE]? 

Will help you to consider if a framework like Bootstrap or Tailwind is really needed to help develop your project or if it just something that will be collecting dust. 