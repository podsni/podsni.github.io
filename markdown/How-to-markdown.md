---
date: 2019-10-18
---

# How to Markdown.

Markdown is an easy to use Mark-up language that "looks" how it will render/format. It was first released in 2004 to be a simplified way to create thingsthat would be easily converted into HTML. Since that time its become quite a standard and has been adopted by Reddit, forums, a million applications, your Nan and the Gods themselves. It's not only a good formatting system but its supernaturally easy. Once you get good at it (in about 10 mins) you can write notes, webpages, presentations, forum/reddit posts and shopping lists in it, as well as anything else you care to think of. You can even use Markdown in Discord messages if you want.

At this point Markdown is a sort of idea that gets bolted onto things. Because of this the rendered output maybe different depending what service you are using. When compiling/rendering it out to LaTex, Groff or HTML you should be fine because pandoc is forgiving and smart (and if you are not converting using pandoc, I need you to take a good long think about your life and… just, I don’t know… read a damned book or something because computers are not for you.) Odd website implementations on the other hand are a total crap shoot. If you are using a GUI tool for markdown, stop it right now and write an appology email to me.

Heres the [Wikipedia page](https://en.wikipedia.org/wiki/Markdown) about Markdown. Good page that.

Anyway, here are the basics…

---

### The Basics:

`# heading`

looks like

# heading

or

`## heading 2`

looks like

## heading 2

You can go up to about 4 `#### headings`  until it all looks the same but you CAN add more.

Below are more basics, these are inside a table. We talk about tables at the bottom of this document.

|You write                    | You get                   |
|-----------------------------|---------------------------|
|`**BOLD**`                   | **BOLD**                  |
|`*ITALIC*`                   | *ITALIC*                  |
|`***BOLD ITALIC**`           | ***bold italic***         |
|`**bold** then *italic*`     | **bold** then *italic*    |
|`**bold *bolditalic* bold**` |**bold *bold italic* bold**|
|`[LINK TEXT](URL)`           |[LINK TEXT](http://hexdsl.co.uk/) |
|`![](url.png)`               |![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/64px-Markdown-mark.svg.png) |
|`![ALT TEXT](url.png)`       |![ALT TEXT](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/64px-Markdown-mark.svg.png) |

---

Horizontal Rule: `---` as above, and below

---

### LISTS

    1. a list
    2. a list
    3. a list

looks like this

1. a list
2. a list
3. a list

---

### BULLETS

    * item
    * item
    * item

looks like this

* Item
* Item
* Item

---

### Quoting and code:

`>BLOCK QUOTE` looks like...
>Block Quote

To wrote CODE inline you can use `a back tick, thats the little tick next to the '1' key` its hard to give an example in rendered markdown because it screws with the rendering thingy.

Another way to write code is to add a TAB or 4 spaces at the start of a line

    like this
    its easy
    its 4 spaces

Remember that maybe a Tab OR 4 spaces depending on the implementation of markdown you are using. Both work fine in Pandoc and the website hackmd.io (I use that a lot when shaing show notes for my podcast [.XPenguin](http://xpenguin.club)) but may not work on reddit or forums.

Most renderers alway allow three back ticks at the start then code, then three back ticks at the end. I think the Backtick is called a"grave" but not sure enough to argue...

```
That would be SiLlY!
its good for copy pasta though!
Also good for large code chuncks.
I use it for ASCII art headers in my Blog posts.
```

Remember to use three back ticks to close the section at the end or it will keep going to the end of the document.

### Tables

```
| Header | header |
|--------|--------|
|item    | item   |
|item    | item   |
|item    | item   |
|item    | item   |
```
Looks like

| Header | header |
|--------|--------|
|item    | item   |
|item    | item   |
|item    | item   |
|item    | item   |

Thats a table! - I feel like the visuals are enough of an explinations for this to be honest.

## Page breaks

If you are using pandoc, you can use `\pagebreak` on a new line to tell if you want a new page, this is a LaTex command that Pandoc applies universally. Dont expect it to work all over the palce like some kind of hippy!

### Please sir, can I have some more...

No! - This little document has covered most of the markdown things you will need. If I think of anything I missed or want to add later, I'll update this document. If you have any feedback on it please do email/tweet/tag or toot me. As it stands, I think I did okay.

If you are looking for advice, I have none. I use markdown wherever I am ABLE to use markdown as it allows me to express my formatting in a very precise way. Its not as precise as Groff, Troff or LaTex but its way better than a nasty GUI!

I write everything I do in markdown where possible. You can write a whole book in it if you like, just convert to whatever your publisher wants after.
As for tools, you don’t need converters, or GUI things for markdown. Take the time to learn it. I don’t even need a preview at this point. I think I have somehow started Compiling it with my eyes.
Personally I write everything in a Mardown aware VIM setup. I convert with Pandoc (as that’s the correct way to do it) and I have had good experiences.

Hope this document and the accompanying video helped. Don’t forget, I have a Patreon


