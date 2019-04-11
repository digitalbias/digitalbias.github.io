---
title: Measuring a good programmer
tags: [measurement, productivity, programming]
image_path: post_images/programmers.jpg
alt: "Measuring a good programmer"
excerpt: "There is no good way to measure a good programmer that I know of"
btn_label: "Read now"
---
![programmers][image]

I’ve vacillated between measuring personal coding performance and the feeling that anything created to measure that activity is flawed. Years ago people thought that measuring lines of code (LOC) would be a good measure.

The problem is that a good programmer cannot be measured by LOC and in some cases a good programmer is actually the one with fewer lines of code than the poor programmer. Also, it doesn’t take a lot of brain power to create nested loops, but a well designed delegation paradigm can beat the pants off a loop and if done correctly can be much faster. Finally, if you start rewarding people based on LOC, they they are not going to write tighter, cleaner code. They will be rewarded for spaghetti code that jumps all over the place and is difficult to maintain. No, LOC as a productivity metric for coding is a terrible metric.

Another thought was that measuring people based on the number of bugs in their code would be a good metric as well. That even morphed into rewarding people for the number of bugs they fixed. Programmers had a quick way to earn extra cash that they could control. After all, they were the ones writing the code so they could even be the ones writing the bugs they would eventually fix. The challenge is that in some cases a person can write clean code, but because of side effects and undocumented behaviors, code that was written today could break something written months or even years ago. Add to that the fact that code could react differently depending on the environment it was placed in, and the programmers had a difficult time tracking down and eliminating any chance for possible bugs in their code. So number of bugs in the code was not a viable metric either.

There is some thought around giving some algorithms a score (something like the Big O notation) and rewarding programmers based on that kind of score. Again, the problem is that while it may a great algorithm, it may not be that readable or appropriate for the problem being solved.

My belief is, that instead of a single score, we should consider a number of metrics which when combined together give an unbiased score of a programmers code. We could then baseline the programmer over a specific timeframe and say that their code is, on average, at this level. We could then work with that programmer to either help others come up to their level of software development or we could help them come up to the level of others in their group. What those metrics are, I’m not sure. But lines of code and number of bugs are not the metrics we should be looking at. Ever.

---
The image, titled "Práce", was taken by "Irena Safarova". You can find it on [flickr][flickr].

[image]: /images/post_images/programmers.jpg
[flickr]: https://www.flickr.com/photos/irena-safarova/5758543173/
