---
title: Blog Poster
tags: [notes, code, blogging, jekyll, github pages]
image_path: post_images/blog_post.jpg
alt: "Blog Post"
excerpt: "Making future posts work on github pages is...complicated."
btn_label: "Read Now"
---
![blog post][image]

This site runs on something called [Github Pages][ghpages]. For those of you not familiar with Github Pages, it lets me post the content of my site to a place that hosts the code. They then take that code and convert it into a website. Once the initial setup is done, the process of posting new content is pretty straight forward.

I decided to go this way because I didn't care if people saw the content of my site (that is what it's for after all) and I wanted something that was secure (it's as secure as my code repository), inexpensive (it's free), and fast (once the site is generated the pages don't change and are served up as fast as github can serve them up). Overall, it hits all the requirements, but there is is a problem.

Scheduling future posts.

There are times when I may be out of town, without access to a computer. I like to have consistancy in when my writing goes out and because of that, I want to be able to write something, edit it, and then have it go out on a specific day. The problem is that [Github Pages][ghpages] doesn't support that functionality. When you push the code to the site it generates it, but if there are future posts in there, it will hide them.

I've tired a number of different solutions over the years but nothing has stuck. For one reason or another I've had challenges getting the code to work, or the solutions I've found have cost too much for something as simple as 'schedule my posts'. I just can't justify paying a lot of money for a single feature.

So, this week I felt like I have had enough of this rigmarole and, wanting to post on a more consistent schedule, I've decided to scratch this lingering itch. I read up on the [Github Api][ghapi] and created a [project][project] that solves this problem for me. There is a bit of setup but for people who are a bit more techy, but should be a decent solution nonetheless.

In fact, if you are reading this on January 28th 2017, chances are this entire process worked!

If you decide to use it, let me know. I'd love to hear about it. You can leave a comment below or mention me in a tweet.

---
The image is 'How to optimize your blog post' by SEOPlanter. You can find it on [flickr][flickr]

[flickr]: https://www.flickr.com/photos/seoplanter/7460433282
[image]: /images/post_images/blog_post.jpg

[project]: https://github.com/digitalbias/blog_poster
[ghpages]: https://pages.github.com/
[ghapi]: https://developer.github.com/v3/

