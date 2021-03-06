---
layout: essay
type: essay
title: A Standard to Uphold
date: 2016-09-22
labels:
  - Software Engineering
  - Learning
---

<img class="ui large right floated rounded image" src="../images/management.png">
<H2>People should be able to read code.</H2>

When coding, it is always important to make readable code. Not just for your own sake, but for the others who might read your code as well. Small technicalities like alignment of braces and spacing out your code may seem insignificant as long as the code outputs correctly, but if you ever want to make changes(and you will) you may find yourself lost in the code. It gets even worse when you try to read someone else's code; someone who doesn't space out his code the way you do, someone who adds additional "if" statements when not necessary. This is why coding standards exist, and more importantly, why utilities like ESLint exist to enforce these standards. 

<H2>Is using ESLint even worth it?</H2>

Below is an example code that will run when compiled, but will not work when ESLint is enabled.

```
function test(){console.log("notice the blank line before this function?");}
```

Here is the code, after being revised.

```
function test() {
console.log("notice the blank line before this function?");
}
```

After using ESLint for about a week now, I can say that I remain uninhibited by its format keeping. It's not hard to finish a block of code and then go back in order to correct any errors ESLint notifies you about. In fact, I was taught to revise my code like this from the beginning. Still, even I forget to space my code out every now and then, so ESLint aids me by reminding me to do so. I can understand how some may find it irksome to have to change their code to fit a standard that's different than their own. However, keeping to the standard that everyone else uses is very important in making code readable to others and should be one of the highest priorities when writing code.


