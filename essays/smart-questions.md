---
layout: essay
type: essay
title: "Smart Questions, Good Answers"
# All dates must be YYYY-MM-DD format!
date: 2015-09-08
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="https://cdn.theatlantic.com/thumbor/YkbWqaBwhGNnrY6cAjSCQB105fI=/0x102:4792x2598/1200x625/media/img/mt/2023/01/Dumb_Questions_02/original.jpg">



## Why Smart Questions Matter

In software engineering, communication is just as critical as technical skill. Eric Raymond’s essay How to Ask Questions the Smart Way explains how to engage communities like StackOverflow effectively. A well-formed question respects the reader’s time, demonstrates effort, and clearly defines the problem. Such questions tend to attract high-quality answers, while vague or off-topic questions are often ignored, downvoted, or closed.

By examining two StackOverflow questions, one “smart” and one “not so smart”, we can see how these principles play out in real-world interactions.

## What Defines a "Smart Question"?
A "Smart Question" is one that provides background information/context while also showing prior effort to solve the issue. Rather than asking broad and vague questions, "Smart Questions" effectively make it as easy to answer as possible for whoever has the proper knowledge. 

## Example of a "Not Smart" Question
```
Q: “Is there a way to alter Chrome's dropdown bookmarks folder list when you press bookmark icon (star) on the address bar or press Ctrl+D and open the dropdown folder list there? Thanks”
```

This is a great example of a poor question. This question was downvoted several times and closed within the hour as it breaks several guidelines. For one, this is a question that lacks relevance to programming, which is entirely outside of StackOverflow's scope. Additionally. the user did not provide any information on their prior attempts to fix their issue. The question comes off as vague and lacks context that would make it easier for someone to help.


## Example of a "Smart" Question
```
I am trying to print an integer in JavaScript with commas as thousands separators. For example, I want to show the number 1234567 as "1,234,567". How would I go about doing this?

Here is how I am doing it:

>>> function numberWithCommas(x) {
>>>     x = x.toString();
>>>     var pattern = /(-?\d+)(\d{3})/;
>>>     while (pattern.test(x))
>>>         x = x.replace(pattern, "$1,$2");
>>>     return x;
>>> }
>>>
>>> console.log(numberWithCommas(1000))

Is there a simpler or more elegant way to do it? It would be nice if it works with floats also, but that is not necessary. It does not need to be locale-specific to decide between periods and commas.
```
 
The post received 52 responses with the top response receiving thousands of upvotes, proving that this was a a great answer to a great question that was helpful to many others. The question is worded clearly and specifically, and defines the desired result. The user also demonstrated previous effort and attempts to solve the issue on their own. The user is looking for improvements to a specific part of their provided code, rather than asking an open-ended question that might be difficult to understand.



## Conclusion

Understanding how to ask smart questions is essential for anyone interested in Software Engineering as it increases the likelihood of receiving an effective response, while also contributing to the overall knowledge base which may help others with a similar question. The "Not Smart" question was vague, irrelevant, and likely a question they could have found the answer to by using Google. On the contrary, the "Smart" question was clear, specific, and demonstrated attempts to find the answer, encouraging more thoughtful answers. This post received thousands of upvotes and proved to be a helpful resource to many in the community who had a similar question. 

