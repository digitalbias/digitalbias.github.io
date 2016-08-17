---
layout: single
title: Disappointed
tags: [disappointed, github, jekyll]
---
I tried a bit of an experiment this last week. I wrote a post two weeks ago and marked it for publication on the 9th, while I was out of town. Not only was I going to be out of town, but I was going to be somewhere with no internet or cell service. There was no possible way to see on the day of or later if the experiment was successful.

The post never showed.

I admit, I was disappointed, but given the technologies I'm using, it really is not that big of a surprise.

Many people use something like [WordPress][wordpress] or [Blogger][blogger] or some other blogging software for their sites. I went a bit more techie and cheap. I decided to host all my sites on [github]. Using a technology called jekyll, you can just write your posts in [markdown], publish them to the [github] repository and they are converted to html and hosted for you for free. Perfect for a techno geek like myself.

No hosting fees, no server maintenance, no problem.

Except there are a couple limitations.

There are some [jekyll plugins][plugins] you can't use, some code you cannot run, and, apparently, scheduling posts is a bit of a challenge. I've never found a use for many plugins, so I'm okay with that. I'm not really interested in running code on this site either. If there is something I really need done on the backend, I'll redirect to heroku or some other service like that. What I really want is to just write and post thoughts here, so doing something extra ordinary is not really in the cards for me. But I really do want to schedule posts.

I am a task person by temperament. I like to be involved in doing something and checking things off my list. Being scheduled is also something I do, so my preference is to set up an editorial calendar, write to that calendar, increase the buffer of articles I have ready to publish and then schedule them and sit back and write some more.

More than anything, I don't want to have to babysit my blog publishing process.

At one point I was using [zapier] to detect when there were changes in my repo and the publish at a certain time, but the solution turned out to be too clunky problematic. I was always getting errors when I did something just a little different and I could never remember what I had to put into the commit messages in order for it to work.

Before I left last week ran across an article that described how to schedule posts. It sounded like the perfect solution and so after a bit of poking around and fiddling with config options I thought I had it solved. It wasn't until I came back that I saw this [issue] about scheduling future posts on github. So, it's back to the drawing board.

I've found a service called [zammu], which looks interesting, but I'm not sure if it's exactly what I want. I'm going to give it a try anyway and see how it works, but I'm not optimistic. So, if you know of another solution besides [zapier] or [zammu] I'd love to hear about it.

[wordpress]: http://www.wordpress.com
[blogger]: http://www.blogger.com
[github]: http://www.github.com
[jekyll]: https://jekyllrb.com
[plugins]: https://jekyllrb.com/docs/plugins/
[markdown]: https://daringfireball.net/projects/markdown/
[zapier]: https://zapier.com/
[issue]: https://github.com/jekyll/jekyll/issues/3174
[zammu]: https://zammu.in
