---
layout: essay
type: essay
title: "Design Patterns in Our Final Project"
date: 2025-12-03
published: true
labels:
  - Software Engineering
  - Design Patterns
  - ICS 314
---

<img width="300px" class="rounded float-start pe-4" src="https://graphicdesignjunction.com/wp-content/uploads/2014/09/free-pattern-design-1.jpg">

## How I Stopped Thinking In Files And Started Thinking In Patterns

### Starting the Project

When my group first started building our roommate matching website for ICS 314, I treated every part of the project like its own little island. If something broke, I went straight to that file and tried to fix it. If a feature needed to be added, I added it without really thinking about how it connected to everything else. At that point, I did not think in terms of architecture or structure. I was just trying to get things working.

As the semester went on, I began to notice something interesting. Even though the features we were building were different, our ways of solving the problems kept looking strangely similar. It felt almost like patterns were naturally forming in the project. I did not know it at the time, but these recurring habits were essentially design patterns.

### Discovering What Design Patterns Are

When we later covered design patterns in class, the concept made everything fall into place. A design pattern is basically a shared solution that developers figured out after running into the same problem many times. It is not a specific chunk of code, but more like a guide for how to structure your logic so the project stays clean and understandable. Once I understood that idea, I started recognizing patterns in our own code that I had never thought about before.

### Patterns I Noticed

One example came from how React handled updates. Whenever a user edited their profile, the parts of the UI that depended on that information refreshed automatically. We never wrote anything that manually notified every component. React just handled it. This behavior fits the Observer pattern. Something changes, and anything watching that change reacts to it.

Another pattern showed up when we created new profile objects for the database. Instead of rewriting the same structure every time, we made one helper function that generated a clean, consistent object. It filled in defaults and kept everything formatted correctly. This lined up with the Factory pattern, even though we did it simply because it made our lives easier.

We also realized our project had a structure that felt similar to MVC. Our data and state acted as the Model, our React components were the View, and the functions that handled user actions acted like Controllers. We never officially labeled it as MVC, but the separation happened naturally because it made the code easier to read and maintain.

### Reflection

Looking back, I realized I had been using design patterns before I even knew what they were called. They showed up because they made the code easier to maintain and prevented everything from becoming overwhelming. Now I understand why interviewers ask about design patterns. They want to know if a programmer can think about code as a system instead of a collection of random files.

By the time our roommate matching project came together, I could clearly see how these patterns shaped the structure. The Observer-style updates kept the UI in sync, the Factory-like helper function kept data organized, and the MVC-style layout helped us separate responsibilities across the project.

I did not start the semester thinking about any of these ideas, but I ended up relying on them anyway. Now, if someone asks me what design patterns are and which ones I have used, I can explain them through experiences instead of definitions.

```This essay was grammar checked with ChatGPT.```
