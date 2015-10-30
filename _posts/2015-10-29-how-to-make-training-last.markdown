---
layout: post
title: How to make a training class last
modified:
categories: development
excerpt: A reflection on the training O.C. Tanner received from Sandi Metz
tags: [development, ruby, training]
comments: true
image:
  feature: deer_creek_mountains.jpg
date: 2015-10-29T21:37:07-06:00
---

O.C. Tanner had [Sandi Metz][sandi_site] come in and train twelve of us for three days. I must admit, before the training I had never heard of Sandi, but then I'm not that plugged into the Ruby world. I've been more of a heads down kind of guy. I try and get my code working without consulting very many books, listening to conferences or anything like that, and honestly, that has been to my detriment. My skills with Ruby are not nearly as good as they could have been had I done so. And this training with Sandi opened my eyes to that lack.

Sandi came in and lead us through what I would call her 99-Bottles course. Officially it's called ["Practical Object-Oriented Design"][pood] and you can see the syllabus [here][pood_sylabus]. The class itself involves a series of exercises where you make gradual changes in the code, making it cleaner, following which you discuss the changes, problems and possible solutions. It's a very interactive course with the entire group working together to solve the problems both as a class and as smaller pairs. Basically I'd say the course is a guided class in refactoring and well worth the time and money O.C. Tanner invested in it.

The class was good and it's hard to convey the understanding obtained by attending, however I came away with a couple things I want to talk about:

1. The skills are great and useful, but if not taken and applied will reduce the intent of the class
2. In order to continue the effectiveness of the class, a knowledge of the following is necessary
    1. Design Patterns
    2. Refactoring Recipes
    3. Recognition of code smells and which refactoring recipes to apply is specific situations

Some of this knowledge can come from experience, but if you are on your own doing work, there really isn't a good place to get that kind of exposure.

A class is a good start, but other things such as reading books, attending local meet ups, and conferences can also help ingrain/train some of the principles necessary in order to be successful.

Training classes are good. Especially if they are like the one Sandi provided this week. The challenge is that you wish the instructor were at your side when you had a question for the next couple months, just so you could have their help as you struggle to obtain some modicum of experience doing the same thing you just did for the last couple days.

Conferences are very much the same as classes, only even less focused. You only have an hour at most to grasp the concepts and then have to figure out how to apply it (if you decide it even applies) to your problem(s).

Meet ups are another way to get some experience, but can suffer from crowd mentality and you could go for months and not get your specific questions solved.

Reading books is a good way to get exposure to ideas, but, I've found books like the Design Patterns book to be a bit dry reading, and so I don't apply them as well as I could. Martin Fowler's [Refactoring book][refactoring] is good for the first half, but the second is also difficult to get through. 

I'm sure there are some good books out there, but I've yet to find one that helps me get the skills I need to make these principles stick. Reading is great, but it doesn't help one practice for any long term without applying other methods.

One other possible way to obtain the necessary skills is to pair program. Pairing is good if you are in a company whose culture is open to it, but if you are on your own, a remote programmer, or are just uncomfortable with the idea of pair programming, it can be a little off putting. The other downside is that if both of the members of the pair are junior, learning the skills will involve a lot of thrashing. But then, I still believe the code would be better than if the two of them were on their own.

In addition to the last five methods of acquiring a skill or specialized knowledge, I did think of a possible sixth alternative which I've decided to follow: The self study program. Using some resources Sandi suggested on the last day, I've decided to follow a self improvement program where I'm going through the [refactoring book][refactoring] and using some of the problems he outlines and trying to solve them on my own, with as little reference to the book as possible and then going back and seeing how he did the problems. 

It's a different approach from just reading the book, but still lacks some of the real world application or feedback which could come from pairing or a conference.

One thing to note, however. I've already found some places where I disagree with the approach Martin took in the refactoring, and I'm not even through the first chapter yet. I don't know if that is a good thing or not. It could be he sees something down the road that I haven't yet, or it could be that he is intentionally going down a specific path in order to teach another principle which I could miss out on by doing it my way.

The code I'm working through is in this [github repo][repo] with various branches for each of the various sections or logical breaks in the code.

Before finishing this post I want to leave with some questions: 

- Between this and pairing, can you think of any other practical way to getting a new skill to stick? 
- What is your experience with trying to acquire a new skill? (it could be any skill).
- How successful was it? 
- Did you have a coach? 
- How did that affect your ability to learn the new skill?


[sandi_site]: http://www.sandimetz.com/
[pood]: http://www.sandimetz.com/courses/
[pood_sylabus]: http://static1.squarespace.com/static/537c0374e4b0f52ed92942e6/t/53f48c2ee4b08efca8cfc116/1408535598852/PracticalOODCourseOutline_v2a.pdf
[refactoring]: http://www.amazon.com/dp/0201485672/?tag=digitalbias-20
[repo]: https://github.com/digitalbias/refactoring-practice
