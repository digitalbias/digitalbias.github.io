---
title: Markdown Scriptures
tags: [personal development, prpductivity]
image_path: post_images/bible.jpg
alt: "Markdown Scriptures"
excerpt: ""
btn_label: "Read now"
date: 2021-04-23T06:00:00-0700
---
![scriptures][image]

I've been using a number of different programs to help manage notes, thoughts and information over the years. I migrated from [Evernote][evernote] a couple years ago and have been using [Notion][notion] for a couple years, but it hasn't quite scratched that personal knowledge management system I have been needing. It does a number of things well and I will still keep it around for keeping track of my stock research notes. But when it comes to keeping track of topics I am interested in and making connections between thoughts, I have begun shifting over to [Obsidian][obsidian].

[Obsidian][obsidian] has been great for keeping track of ideas and just throwing ideas into. One of the bigger challenges I have experienced, however, is when I do my personal scripture study. Making the links to the [Gospel Library][gospel_library] app has been painful. For whatever reason, the links on the iPad do not work properly and copying text from the specific verses seems like a bit of overkill in some cases as well. As I was listening to a recent podcast, however, I heard an idea that sparked some interest for me. One of the people on the podcast said that he had a friend create a collection of markdown files which he then links to within his [Obsidian][obsidian] install. I thought that was brilliant, but when I went out there looking for them, I could not find anything like that.

Well, with a little bit of research I found a sqlite3 version of the [LDS Scriptures][lds_scriptures] and using that as a base I then wrote an [ugly elixir script][scripture_extractor] that connects to the database and extracts the data, creating a [collection of markdown pages][lds_markdown] I can reference within Obsidian without having to monkey around with the [Gospel Library][gospel_library] app.

As a note: I found [bomdb][bomdb] which was nice as a search app, and I still use it a bit, but overall, my markdown files are my primary sources right now.

---
Photo by <a href="https://unsplash.com/@aaronburden?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Aaron Burden</a> on <a href="https://unsplash.com/s/photos/bible?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

[image]: /images/post_images/bible.jpg

[lds_scriptures]: https://scriptures.nephi.org/sqlite
[gospel_library]: https://www.churchofjesuschrist.org/pages/mobileapps/gospellibrary?lang=eng
[evernote]: https://evernote.com/
[notion]: https://www.notion.so/
[obsidian]: https://obsidian.md/
[scripture_extractor]: https://github.com/digitalbias/scripture_extractor
[lds_markdown]: https://github.com/digitalbias/scripture_extractor/releases/tag/0.2
[bomdb]: https://github.com/wordtreefoundation/bomdb