---
layout: essay
type: essay
title: "Git Good with TypeScript"
# All dates must be YYYY-MM-DD format!
date: 2025-01-22
published: true
labels:
  - TypeScript
  - Learning
---

There are a lot of courses out there that market and advertise the use of JavaScript in one's projects for frontend and/or backend development. For example, a quick search on YouTube and you can see a lot of videos that incorporate JavaScript as the language of choice for projects in web development. However, I want to market the use of TypeScript as a language that one *should* learn as a viable option for their projects. 

As described by the official [TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html#learning-javascript-and-typescript) website, "TypeScript is JavaScript's runtime with a compile-time type checker." In other words, you still need to learn JavaScript in order to begin to use and understand TypeScript. I get it though. When I started learning TypeScript, it felt entirely alien to me, the syntax felt weird when attempting to add types to a function or variable. Oftentimes, I would scratch my head wondering why a certain error was occurring in TypeScript, but if I used plain JS, it would be totally fine. The point is: TypeScript is hard to pickup and learn. 

Once you get used to TypeScript though, I feel like you can never live without it. The whole point of introducing types to JavaScript is to give clarity as to what a function or segment of code is doing. You can guarantee you'll know what is the expected output of a function and what is the expected input to be entered into a function. Not only that, but because it's compiled, you can also guarantee that it will catch any errors at compile-time instead of at run-time (looking at you JavaScript...). 

The last thing I want to mention is that TypeScript is also flexible. With a `tsconfig.json` file, you can specify how exactly TypeScript will compile the code into JavaScript. For example, you can specify what version of JavaScript the code should be converted to or if there is certain file paths that the compiler should ignore. With TypeScript, it's flexibility allows you to make configurations that are specific to your project. 