---
layout: essay
type: essay
title: "Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2026-09-10
published: true
labels:
  - Software Engineering
  - Cloud Engineering/Networking
  - Data Science
  - Artificial Intelligence
---

<img class="img-fluid" src="../img/artintlog.png">

## Intro


When you run into a roadblock in software engineering, your first instinct is usually to search online or ask someone for help. But there is a huge difference between asking a question that gets you an immediate, helpful answer and asking one that gets completely ignored or downvoted. In Eric Raymond’s essay, How To Ask Questions The Smart Way, he breaks down how open-source and developer communities actually operate. These forums are made up of busy people volunteering their own time so they want to help you. However to get good help, you have to show that you’ve done some leg work on your end.

Learning how to communicate problems clearly is just as important as writing good code. To see this in action, we can look at two contrasting examples on Stack Overflow: one that follows these principles and gets great results, and one that completely misses the target.

## Doing It Right: The Smart Way


The Smart Question:
[How to sort an array of custom objects by property value?](https://stackoverflow.com/questions/24130026/how-to-sort-an-array-of-custom-objects-by-property-value)

A great example of asking a question the smart way can be found on Stack Overflow in "How to sort an array of custom objects by property value?". In this post, the developer is trying to sort an array of custom ImageFile objects in Swift based on an integer fileID. Instead of pasting an entire messy project, they created a clean, small code snippet that isolates the exact problem and asked directly: “How can I sort the images array by ‘fileID’ in ascending or descending order?”

This post works because it hits all of Raymond’s guidelines. The title is clear and searchable, the code is self-contained so anyone can copy and run it in seconds, and the author makes their end goal obvious. Because the developer put in the effort to make the question easy to digest, the community responded with several detailed, high-quality solutions. The question has since helped thousands of other developers facing the same problem.

## What Not to Do


The Not So Smart Question:
[git push got stuck all of a sudden and not working](https://stackoverflow.com/questions/78832014/git-push-got-stuck-all-of-a-sudden-and-not-working)

On the flip side, we have questions that show what happens when you don’t follow these guidelines, such as git push got stuck all of a sudden and not working. In this post, the user actually titles their issue “git push got stuck all of a sudden and not working”. In the body, they don’t provide any meaningful reproduction steps or explain what they already tried. Instead, they just link their entire github repository, drop a terminal snippet, and ask “Please assist me on what I’m missing.”

This violates almost every rule in Raymond’s book. The title is vague, there is zero context about their environment or network, and expecting other developers to dig through an entire repository to figure out a basic git issue is unrealistic. As expected, the post received negative votes and was quickly closed by the community. The author walked away with no real answer because they didn’t provide enough useful information to help anyone help them.

## Smart Questions -> Better Engineering


Looking at these two examples makes it clear that the way you ask a question directly affects the quality of the answer you get back. Taking the time to isolate a problem and write a concise example often helps you find the bug on your own as well.

As I continue building my skills in software engineering, developing the habit of asking consice, thoughtful questions will make collaboration smoother and save a lot of wasted time for myself and for the teammates I work with.
