---
layout: essay
type: essay
title: Coding Style
date: 2016-09-21
labels:
  - Software Engineering
  - Learning
  - JavaScript
---
## Coding Standards

Messy code is a programmers worst nightmare when joining a new programming team. Messy code means the programmer must take time to refactor their code into something readable. Whereas, neat and clean code means the programmer can immediately start working on the project. There is nothing worse than taking on a large project with hundreds of source files, and finding out that you need to refactor most of the code to be able to read it. This wastes a company's time and money, as the programmer cannot contribute until they clean up and understand the code. Because of this companies started using coding standards, some of which are now widely accepted as best practice. A coding standard is nothing more than a list of rules on how to format your code. It does not change the content of your code, instead it just describes how to make the code you have more readable, more organized, and less confusing. Implementing a coding standard is not hard, in fact most of the time you are just adding extra white spaces to your files. However, it can become tedious when the project involves hundreds of files. Luckily for us, there are automated tools designed to help us with this daunting task.

## ESLint

ESLint is a tool designed help programmers enforce coding standards in their JavaScript programs. With ESLint you can either define your own coding standard, or if someone else already has one you like, you can use theirs. When used as a plugin for IntelliJ, ESLint will check your for format errors in your code, while you write it. Any infractions will be underlined in red, and you can then hover their cursor over the error, and ESLint will tell them what the mistake was. With this information the programmer can immediately rectify the situation and move on to the next thing. This allows the programmers to guarantee that their code is always clean. ESLint is a powerful tool that, when equipped with the appropriate coding standard, allows programmer's to quickly produce high quality code.
