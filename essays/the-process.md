---
layout: essay
type: essay
title: "Software Engineering: A Process"
# All dates must be YYYY-MM-DD format!
date: 2025-05-11
published: true
labels:
  - Software Engineering
  - Review of Software Engineering
---

What separates a developer from a Software Engineer? They both appear to do the same thing: develop applications by writing code. However, what separates a software engineer and a developer is the process at which they develop an application. Software engineering is a process. One that's carefully thought of: from gathering information of the project, to deciding the tech stack, to finally implementing the software; software engineering is important because the decisions you make help to create better applications.

# Coding Standards

What's the importance of coding standards? They seem to just slow us down as it requires us to conform our code to a specific style. **But conforming to a specific style is the point!** Coding standards dictate a format for all code to follow, what they ensure is to help the project maintain a consistent manner. Say an organization hires new developers, if they were to take a look at the code, which would they prefer: files with code that's all over the place, doesn't follow a particular formatting, and looks chaotic, ***or***, a file that's nicely formatted, is orderly, and visually appealing. Chances are, the nicely formatted file. 

Some tools to help enforce coding standards is `ESLint`. The program is a tool to help lint (fancy for check if code adheres to coding standards) your code to ensure consistency. You can easily configure which rules are important and which rules to discard by defining a `eslint.config.js` configuration file.Another tool is `Prettier`. This is a tool that does less linting and actually just formats your code. It makes sure that the file can look as visually appealing as possible to people. Just like `ESLint`, you can also define a configuration file named `.prettierrc`. 

By ensuring coding standards, you improve the quality of your code. By improving the quality of your code, you make sure that it's concise, clear, and contains less bugs. This doesn't have to apply to web applications, you can easily include these types of checking to other kinds of software development like mobile apps and make sure that your app follows standard conventions for languages. 

# Development Environments 

The real question is, what are development environments? To break it down, an environment in software engineering is a group of things with a specific configuration that allows people to play around with the code. For example, a production environment of a company, would be there website where users can do things like order and pay for items. A development environment then, is one that allows developers to implement, test, and debug upcoming features for a web application. 

Common items associated with your development environment is an IDE or Integrated Development Environment, like `VSCode`, that gives you all the useful tools needed to start and run your project. Another item might be your data. You might not want to **change the production database** because that could lead to errors. Instead you have a test database to make sure that your changes don't make anything already existing break. 

Outside of web applications, development environments can be applied to a whole host of software applications. Like mobile apps. Systems and servers. Databases. Game development. All of them have the same issue / idea. How do we develop new features without affecting our already existing code? The answer, development environments. By using them we keep production and testing separated, making sure that our product is usable and enjoyable, while working out the kinks and bugs associated with the new feature. 
