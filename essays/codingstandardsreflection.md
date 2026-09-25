---
layout: essay
type: essay
title: "ESLint: The Coding Drill Sergeant"
date: 2026-09-24
labels:
  - Software Engineering
  - TypeScript
  - ESLint
  - Coding Standards
---

<img class="img-fluid" src="../img/1fmj.png">

# Initial Overview

Hearing the words "coding standards" might sound like another burden to the young padawan programmer trying to find his way. It just sounds like another tedious thing you have to worry about. In reality, clean easy to read code saves everybody time. It saves the programmer time as having clean, easy to read, and organized code becomes paramount to troubleshooting/fixing errors in the code. Including notes in the code leaves a trail to follow so you don't get lost in the woods when trying to figure out what the heck is going on with your code. My first week experience of figuring out using ESLint and TypeScript inside VSCode has been one that initially started off as "what's the point of this" and progressed to a deeper appreciation for these formatting guardrails.

# The Process

My first week with ESLint and TypeScript inside VSCode was interesting. My OCD started going crazy seeing red squiggly lines everywhere. I'm just thinking to myself "the code is fine who are you to tell me otherwise ESLint". My egotistical attitude changed quickly as I began to accept the criticism of ESLint. Whether it be an issue with files not being imported correctly or realizing that a project was forcing the use of single quotes, I found that it was actually there to help me, not annoy me.

```typescript
// ESLint: Strings must use singlequote. (@typescript-eslint/quotes)
const message = "Aloha World";

// Corrected:
const message = 'Aloha World';
```

# Ultimately

ESLint is like a drill sergeant that constantly corrects your push-up form. Nobody likes being told "your back is not straight enough" while their arms are trembling. However the correction of bad habits before they compile into faint runtime bugs keeps your blades sharpened as you navigate the tall grasses of learning how to code. ESLint is an incredible tool that may be a little painful at first but we need to understand as coders that this world is comprised of more people than just ourselves. Collaboration, understanding code, and manipulating it become a lot easier when there is a shared standard in how we develop our code.
