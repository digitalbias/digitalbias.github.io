---
title: What I Want From Atom
excerpt: Atom is a great editor, but I'm not quite ready to jump in with both feet just yet.
tags: [coding, text editor, atom editor, sublime text, markdown]
---

I really want [Atom][atom] to succeed as a mainstream text editor. I like the idea of an open sourced, powerful text editor that is extensible. I also like that it is something of a spiritual descendant of [Sublime Text][sublime]. The fact that it uses some of the most common technologies out there ([JavaScript][javascript] & [Chrome][chrome]) is also a great bonus.

There are only a couple problems that would need to be solved before I started working in it exclusively.

![Atom Image][atom_image]

## Dislikes

### 1. Markdown Support

If I'm not writing code, I'm doing quite a bit of [markdown][markdown]. I use markdown to write blog posts, journal entries, and documentation for things I've coded up. For an editor to be considered a contender for my full use, it has to do markdown well.

Unfortunately, while Atom does have some markdown support, it's not the best. One of the most essential things I do with markdown is use the "\_" character to emphasize text. I use a double \* to make text bold. However, when typing markdown in Atom, and I have selected a section of text and then type one of those characters, instead of surrounding it with the character, it replaces. In order to make something like that work, I'll have to customize the editor.

I don't have a problem with that, and in fact I'm interested in learning how to customize it anyway. Which leads me to the next thing:

### 2. The Tutorial

Atom has a tutorial, which walks you through the basics and even teaches you how to write themes and plugins. That's lightyears ahead of sublime, which is much more geared to letting you learn how to write and install plugins on your own.

So, +1 for Atom in that arena.

-1, however, for the fact that the tutorial is a bit off. I had to reach out to the developers when I went through the tutorial and it failed to run the plugin I wrote because of a namespace collision. The solution is an easy one, but not easy to find the answer based on the error message in the developer console. It's a young product and so I can understand that. I remember some of the early errors when Java was still maturing. They were very obtuse and difficult to understand at the time. So, I expect it to get better, it's just not there yet.

### 3. Speed

Some of the reviews I've read said the speed of the editor is not as good as some other editors they have used. Frankly, this is something I'm on the fence about. I haven't noticed any problems and I think some of the reviews may be based on some of the older versions of Atom before they rewrote the underlying engine from the ground up. Is the app based on Chrome and JavaScript? Yes. Do I think that could have a impact. Maybe. There are some amazing things being done in both those technologies now so it may be a non-issue.

## Likes

### 1. Plugins

I love the fact that the entire application is basically a very small core with everything else being built up using plugins. That makes it very extensible and flexible. Two things that are very important when looking to make a choice in editor. Everybody works just a little differently, and that kind of customization makes all the difference.

### 2. Community

I love the fact that the community is really engaged. People are willing to work on problems with you and are open to making Atom the best out there.

### 3. The Tutorial

I know this is also a dislike. The tutorial is well written and does its job well. It walks you quickly through the basics and even gives you a taste for the power that is under the covers. It's a great tutorial and the only real problem I had was when I got into the errors that were in the coding part. If all you are looking for is something to teach you how to use Atom to do your own thing, than the first couple sections are a great read. I feel like I have to go back and reread some parts because there were value bombs dropped all over the place in those first couple sections.

### 4. Git Integration

I like seeing, at a glance, what branch I'm on and what parts of the files I'm working on have changed. I loved them so much I started looking for something similar in Sublime and while there are some git plugins for Sublime, the ones in Atom are much better. Go figure, since Atom is sponsored by [Github][github].

## Conclusion

There are a number of good things with Atom and I'm really looking forward to seeing what is done with the editor in the future. I'm sure when I start using it on a more regular basis it will be as powerful as Sublime, but right now, some of the small things are what is keeping me from fully embracing it.

Of course, once I get through the tutorial I intend to see if I can't scratch that markdown annoyance I have. If I can lick that, then Atom may at least start being the only editor I use for Markdown. For now, I'll stick to Sublime while I learn more about Atom.

In the spirit of full disclosure: I wrote this entire post in Atom, just to give it something of a workout again for writing Markdown. Overall, not bad, but then I didn't do anything too off the wall with \_ or \*

[atom]: http://www.atom.io
[sublime]: http://www.sublimetext.com/
[atom_image]: /images/post_images/atom_logo.png
[github]: http://github.com
[javascript]: http://www.w3schools.com/js/
[chrome]: https://www.google.com/chrome/browser/desktop/
