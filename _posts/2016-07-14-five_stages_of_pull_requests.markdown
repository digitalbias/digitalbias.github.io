---
layout: single
title: The Five Stages of Pull Requests
tags: [coding, github]
---
I've been back in the coding circuit for almost a year now, but I've never really been in a company that did pull requests as well as the team I'm currently on. Other places I've been in have had code reviews, but eventually those devolved into either tacit acceptance of whatever you put in, or else they were grueling trials where you had to justify every `if` and `case` statement in your code. I think the team I'm now on has a good handle on how things should work, but I still find myself going through what I'd like to term "The Five Stages of Pull Requests".

For those of you who already know what a PR is or are just interested in the five stages, you can just [jump ahead][jump]. For those of you who are not coders let me explain what a "Pull Request" (or PR) is.

When a programmer has written some code they want to put into the current project, they submit something called a Pull Request. What that means is that they have written their code and put it into a specific place where another programmer can look at it, make comments and then if things look good, approve it. Once it is approved it will be merged in to the current project and be scheduled for release at some point. In essence, a PR is a request for a review of the code and possible acceptance into the project as a whole.

The challenge is that it doesn't always go as the programmer initially planned and there is usually some back and forth discussion that happens between the developers before it is accepted. If it goes on for too long, one can quickly go through what I've decided to call the Five Stages of Pull Requests.



## The Five Stages
<a name='jump'></a>

### Denial

Yes! This PR is going to be great. I did a lot of good things here. Tests are all passing and the code looks good. This should be a breeze.

### Anger

What?! That class is LISKOV! I followed the other patterns in the code and did exactly what was already there with a few tweaks for this scenario. How can this be so bad?

### Bargaining

The method is written this way because the API we are calling doesn't have any callback actions and could take forever to give us the data we need or even fail. I need to have a thread here because otherwise the request would block.

### Depression

He's right. That code really should change. Man, what was I thinking when I submitted this? I'm an idiot. I should just become a pro gamer instead...Nawh, that could never happen. I suck at DOTA 2 too much to make it. Besides, [RapidStar][rapidstar] would kill me in DOTA and he doesn't even play it.

### Acceptance

Sheesh. I might as well just make the changes and move on. Maybe I'll do better next time.

[jump]: #jump
[rapidstar]: http://www.esportsearnings.com/players/2754-rapidstar-jung-min-sung
