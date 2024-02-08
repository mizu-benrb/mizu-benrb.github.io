---
layout: essay
type: essay
title: "Standard, yet Stylish Code!"
# All dates must be YYYY-MM-DD format!
date: 2024-02-08
published: true
labels:
  - Software Engineering
  - Programming
  - Coding Standards
---

<img width="200px" class="rounded float-start pe-4" src="../img/standard-stylish-code.png">

## Enforcing a Style of Code

"Pretty" is a word I rarely use when I am looking at code. Particularly when looking at other people's code, it often starts out as a mess of letters and symbols that only resolves into something legible after many minutes of inspection and thought. Peoplpe have many different ways of writing the same function or procedure, and it gets harder when the code does not have the correct output. Thus, the idea of a coding standard, the idea of making people code in the same format is intriguing, and perhaps even attractive. Ideally, such a standard would make code look homogeneous and easy to follow. Communicating between coders would be better facilitated, and learning through peers would be simpler and more efficient. It could even make code look aesthetically pleasing, given it forces more elegant approaches to various problems. And so, diving into ESLint for my Software Engineering I class through IntelliJ, I remained open to the idea of an enforced coding standard.

## First, a lot of ugly...

The first few assignments I did using ESLint were, to put it lightly, awful. The objectives of the assignments were in-line with the previous topics of the class, that being functional programming. However, having to learn both the intricacies of a brand new integrated development environment (IDE) and the whims of ESLint was rough. I spent more time trying to get the whole hodgepodge of tools and frameworks to work than solving the problem, which resulted in quite a few DNFs. When ESLint did decide to speak up, it was often very annoying. Just when I'm in at the end of a sprint to finish up a function or algorithm, ESLint would walk up and list a bunch of red flags everywhere. It really does break up the flow of programming, and its fixes often resulted in major structural changes to my code which would require me having to re-inspect everything. It uses up time, of which there is not a lot of during the class' workout of the day (WOD). All in all, it really was an annoyance to work with at times.

## However, quite a bit of good...

At the same time, it was easy to see the positive impact ESLint had on my code. A lot of functions that previously took 3 lines, I realized could be turned into one-liners via arrow functions. Many of the curly braces and semicolons that I instinctually included due to my experience with C and C++ were apparently unnecessary in JS, and ESLint pointed out many of those unnecessary inclusions and automatically fixed them for me. Oh, did I mention that fixes are automatic? With just a simple shortcut (or a hover and click with a mouse), I could turn all the red flags into code fit for the standards imposed by ESLint. There's also something a tad satisfying seeing the green arrow in the upper right corner appear as I finish up implementing all the fixes to my code, although IntelliJ still sometimes shouts at me for various weird "issues" that do not amount to anything but are still annoying. Taking into account my inexperience with ESLint and IntelliJ though, using them was still overall pleasant and I do think that I learned a bit about Javascript as I went through fixing my code and looking at the recommended fixes. Over time, I think I will come to fully like the use of coding standards, and I will remain open to them as I continue on my journey through computer science.
