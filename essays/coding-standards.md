---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2025-09-24
published: true
labels:
  - Coding
  - ESLint
  - Software Engineering
---

<img width="300px" class="rounded float-start pe-4" src="https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F6jevsi5g9xn10jkr3p1w.png">


## Coding Standards Beyond the Basics  

When I first heard the phrase “coding standards,” I thought it only referred to minor details such as how many spaces to indent, whether to put braces on a new line, or whether semicolons should always be included. At the time, those rules felt unimportant compared to simply writing a program that worked. Why should I spend energy making my code look a certain way when the computer only cares about whether the syntax is correct?  

After spending a week using ESLint in VSCode, my perspective began to change. Coding standards, I realized, are not just about style. They are about consistency, reliability, and even improving how I understand the language itself. ESLint forced me to look at my code more carefully, and at first this was frustrating. The constant red and yellow underlines made me feel like my work was always being criticized. I would finish writing a function only to be reminded that I had declared a variable without using it, or that I used `let` when `const` was the better choice. My first thought was often, “The code works, so why does this matter?” But as I kept fixing those errors, I started to see that they did matter, and they helped me become a more thoughtful programmer.  

## Lessons From ESLint  

The first lesson I learned from ESLint was that details add up. Declaring a variable with `const` instead of `let` may seem like a small change, but it makes the code more predictable and easier to reason about. Removing unused variables not only cleaned up my file, but it also forced me to think about whether I had overlooked part of my logic. Even style-related corrections like spacing and semicolons turned out to be valuable because they made the code more uniform and easier to read at a glance.  

Another lesson was patience. Fixing ESLint warnings slowed me down in the beginning, and there were times when I just wanted to move forward with my assignment. By slowing down and correcting issues as they came up, I noticed that my code became more polished and required fewer fixes later. ESLint was teaching me discipline, and though it felt inconvenient at first, it ultimately made me more efficient.  

## Thinking About Collaboration  

Right now, most of the projects I work on are individual assignments. Using ESLint helped me realize how important coding standards are in collaborative settings. If every programmer on a team wrote code in their own style, the result would be messy and confusing. One person might use camelCase while another prefers snake_case. One file might be indented with tabs while the next one uses spaces. Even if the logic worked, it would take extra effort just to interpret the code before making changes. That lack of consistency could easily slow down progress.  

Coding standards solve that problem. By setting shared expectations, they make the code feel recognizable no matter who wrote it. Standards remove distractions, letting programmers focus on solving problems instead of interpreting style. This consistency becomes especially important in long-term projects, where new people may join the team and need to understand the code quickly.  

## The Bigger Picture  

ESLint also helped me see how coding standards fit into the broader practice of software engineering. Tools like Git and GitHub keep track of what changes are made and who made them. Coding standards, enforced by ESLint, ensure that those changes are clear and consistent. Together, they create an environment where software development feels less chaotic and more organized.  

In some ways, ESLint reminded me of experiences I have had with coaches in sports. A coach will point out mistakes that may seem small or even unnecessary in the moment, but they do it because those details shape long-term habits. At first, it is frustrating to hear constant corrections. Over time, though, you realize that those details matter and that they are what separate good performance from great performance. ESLint played a similar role for me this past week. It kept me accountable, pushed me to focus on details, and helped me build consistency in my coding.  

## Conclusion  

All of this has led me to see coding standards in a new light. They are not just surface-level rules about indentation or brace placement. They are guidelines that make code clearer, more reliable, and easier to maintain. ESLint has shown me that while it can be annoying to fix constant warnings, those warnings are learning opportunities that push me to write better code.  

Yes, it was sometimes painful to deal with ESLint, but it was also useful. In the long run, I think the benefits outweigh the frustrations. Coding standards make my code more trustworthy and make me a more disciplined programmer. Even though I started out skeptical, I now believe that coding standards are one of the most important techniques for improving software quality, and ESLint has already helped me raise the standards I hold myself to.  

```This essay was grammar checked with ChatGPT.```
