---
tags: ['']
category: ''
title: Colophon
description: null
layout: post
---
% Colophon  
% Frank Colcord (frank@colcord.net)  
% 2014-08-08  

Introduction
============
I have written this document to be able to test the workflow for my own writing.

<!--more-->

I want this to be a long document to see how all the software discussed handles such a long document. Sorry if it seems too wordy.

I want to write in a way that I can use the same text in many ways. Perhaps this is a hopeless goal, but I'd like to try. Some of these pages will remain personal, other pages I'd like to share with others. This means that this document will link to other documents. Some output formats will leave the documents separate, others will combine them.

I'd like to write a book or several papers on github, like the book @HOTT, which friends or interested people could make comments or changes. I'd like to write one on InterLocutor, one on CuiBono, an introduction to logic and type theory, as I figure it out. 

this document is the first in a test suite of documents to see if I can write and produce in the formats I want.

I have been writing a lot of plain text documents, and want to start showing them to other people.

I am very grateful to the open source community for writing all these tools. I am contributing to their efforts by writing this documentation and testing their tools at the same time.

One amusing feature of this document is that I'm hoping it will become mostly redundant. As I point out features that don't work in the different softwares, I'm hoping those authors will reprogramme them so that the features work. Then I will need to update this document to remove the comments. I will try to update this document with notes on bugreports and dates of emails sent to the developers. 

I have always tried new technologies for writing.

I want a flexible way to write, that allows me to focus on the one idea or lets me connect many ideas together. I don't like it when I lose track of what I'm working on, or feel as if my writing is disconnected. I don't like to repeat myself. I'd like an easy way to write hypertext, with buttons linking between documents. I'd like a Hyper Text Markup Language :)

I may be making things too complicated for myself. Perhaps I should stick with Google Docs or Word Docs.
^[todo: bring in other colophon documents into this one.]

I want a way to keep my writing private until I feel ready to share it with friends, and then the general public. I don't want to do a lot of work managing the transitions between those three levels. 

Writing out this document has let me see some of the contradictions in what I want, and to also let me see the concrete steps I can take to resolve apparent contradictions or fallacies.

I'd like to be able to take each document and have it be either a blog post, or academic paper, or chapters in a book or eBook.

Sometimes I write to be able to figure something out. Sometimes I write to show other people what I'm thinking. Sometimes I write to explain something to someone else.

I want an easy way to write

I want this file to be a place to write it all up both the good and the bad about all the options I have right now, so that I can file reviews for all components and see how to improve them, but also write out what I want to be able to do with each app, to look at the documentation a different way.

* a place to capture all my thoughts as I have themand then edit them later
* to be able to cope with the creative and critical modes and moods
* able to write on my android phone or Ubuntu laptop or windows machine
have my files always available and backed up

able to print from any computer I'm writing from, probably if markup rendered inside browser

I want to write in a way that I can use the same text in many ways. Perhaps this is a hopeless goal, but I'd like to try. Some of these pages will remain personal, other pages I'd like to share with others. 

I'd like to write a book or several papers on github, like the book @HOTT, which friends or interested people could make comments or changes. I'd like to write one on InterLocutor, one on CuiBono, an introduction to logic and type theory, as I figure it out. 

this document is the first in a test suite of documents to see if I can write and produce in the formats I want.

Short term online
----------------------------
Speech to text

short term offline commuting
-----------------------------------------
writing at night
picking up the writing in the morning while commuting
printing out from work
binding into a book

long term off line
-------------------------------
I still have this fantasy of traveling the world by container ship, being offline for weeks at a time. reading and writing, going through my Zotero database and linking everything up
learning how to programme
or in a mountain hut powered by solar power
or by fireplace power generation



Other people on Markdown
---------------------------------------
[My academic book in plain text](http://www.owlnet.rice.edu/~wcm1/my-academic-book-in-plain-text.html)

[Markdown for the humanities](http://www.davidsmith.name/2014/05/22/markdown-for-the-humanities/)

Input: Software packages and Features
==============================
I have written about some of the topics in sections below in separate files. I am looking for an easy way to link to them. In particular [Pandoc](#pandoc) in [PanDoc](PanDoc.txt), [Ema](#ema) in [EmaPersonalWiki](EmaPersonalWiki.txt), [StackEdit](#stackedit) in [StackEdit](StackEdit.txt), [MarkDawn](MarkDawn.txt), [LightPaper](LightPaper.txt)

##Formats

###Markdown
>The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions. @MarkdownIntro

These are the basic Markdown pages: [here](http://daringfireball.net/projects/markdown/basics) @MarkdownBasics and [here](http://daringfireball.net/projects/markdown/syntax) @MarkdownSyntax.

I write text files in a markdown format, because I think they will be most future proof. Some don't agree, and [suggest](http://www.codinghorror.com/blog/2012/10/the-future-of-markdown.html) a spec @MarkdownFuture. I will continue to work with pandoc, assuming that it will adhere to a clear spec and will be future proof.

[MultiMarkdown](http://fletcherpenney.net/multimarkdown/) was one of the first variants of Markdown. [Pandoc](#pandoc) has incorporated most of its improvements.

###literate programming

so I can draft my text and programmes at the same time

writing both haskell, erlang, python, javascript

or writing in natural language and having the parsers translate

perhaps have a way of drafting JavaScript so the pages don't have to be static

so, have a way to do both: 
a) to have programming language embedded in the text I'm writing
b) to have natural language processing which takes my text and looks at it formally, and even turn it into a programme, if possible

####Haskell Literate

Each page could be a haskell literate programme.
There could be a separate build file which copies the .txt file to a separate directory, and renames the extension to the extension that the haskell compiler expects, and then the haskell compiler could compile it. 

Or that process could happen whenever a file changes in the PersonalWiki directory, either through editing the files on my linux laptop, or through sync from my phone.


####Haskell or Python or Go

A language that I can learn and think through
a language I can use to develop the apps I want to scratch my own itch

###Framework (DOS)
I used Framework in the late 80s for writing a long philosophy paper.
It had a very flexible tree structure. 
Linking between leaves on the tree was more difficult.
Each leaf could be any kind of document, word processing, spreadsheet, database table. 
^[todo: links to Framework, would there be a way to translate my old Framework documents into Markdown etc?]

##Ubuntu Operating System
[Ubuntu](http://www.ubuntu.com/) lets me use an up-to-date secure operating system on old machines.

###Meld
Ubuntu software to show differences between text files

###Instiki
I first started using [Instiki](http://instiki.org/show/HomePage).

It uses plain text pages, and all the pages I wrote on there are available somewhere. It gave me a choice between [Markdown](#markdown) and Textile. I think I went with Textile. Looks like pandoc can translate from Textile to Markdown.

Instiki hasn't completely died. Some mathematical bloggers still use it. [But development doesn't look heavy.](https://github.com/parasew/instiki/pulse/monthly) 
^[todo: look for current live branch of instiki for maths and logic] 
^[todo: find all the instiki pages and bring them into my current system.] 

Should I go back to using Instiki. I think it uses files with the extension txt. I think it linked camelcase the same way. I don't know whether it uses curly brackets the same way to link to other pages. One benefit is that Instiki is compatible with MathJax.

I wonder how Instiki handles literate haskell files. Does it separate the programming language from the english text the same way that Instiki does?

###Wikidpad
I started in [Wikidpad](http://wikidpad.sourceforge.net/), also seen [here](http://trac.wikidpad2.webfactional.com/). 

I haven't really got started with this on my nexus.
used it a bit on Ubuntu, but still had installation issues, problems keeping it up to date
I wish it saved files in markdown in Dropbox
that would allow versioning and diff

I liked the idea that there was a version for Windows, Mac and Linux.

I have a lot of text files written in that format.

I love some of the user interface capabilities of Wikidpad, but other parts are frustrating. 

todo: wikidpad works on my nexus
I should still try to get it to work on Android. I can't figure out how to get the android version to store its files in dropbox. 


I became nervous when I realized the text formatting wasn't in [Markdown](#markdown). If I keep using it, all my files will be in a format which is out of date.

I notice that [development seems to have stopped](http://trac.wikidpad2.webfactional.com/report/1?asc=0&sort=created&USER=anonymous).
^[todo: find all my Wikidpad pages and bring them into my current system.] 
^[todo: look at wikidpad and see if it has changed internal format.] 

###Gedit
I am currently using Gedit to edit the text files on my Ubuntu laptop. The files are stored in my Dropbox folder. 


##Zotero citation manager
(Write a simple paragraph here and link to full chapter on [Zotero](#zotero) below.)

Zotero works on Windows, Linux, Chrome.
It stores data on its own cloud. It can also store attachments.


See [below](#citations-and-references) for more information.

###Citekeys

The important feature which links Zotero to Pandoc through markdown is called Citekey. A citekey is the text I type into the markdown document, and that Pandoc converts into a citation in the correct format, using the bibtex file exported from Zotero.

See [below](#citations-and-references) for more information.

From what I can see, Zotero won't help me check that the citekeys are unique.

Dropbox
----------------
I currently store documents on Dropbox and Google Documents.
I used to store documents on the Ubuntu Cloud, Ubuntu One. This has been discontinued.

I worry about privacy and security on both Dropbox and Google Docs.

Reliable
all platforms
takes so long to open a file
unable to undo if I make a mistake with my Bluetooth keyboard

Google Documents
----------------
I'm not sure if this can be used as a matching platform to Dropbox.
I like the apps that use this as storage.
I'm concerned that they will lead to lock in if I start to use them.

Android Operating System
----------------
I have had a lot of trouble finding the right writing application for my phone. I want an app which allows me to write and edit anywhere, and is compatible with the rest of the workflow described here.
^[todo: test dictation of my notes using Google's voice to text ability.]

I love the table of contents feature in [StackEdit](#stackedit). It would be great if it could be a third pane for a widescreen monitor. This feature would also be great for Android. It would be great to be able to swipe left or right and get the outline one way and the html view the other, with the main view being markdown. It would be great if all three would synchronize.


Draft doesn't create blank documents from links. Draft requires the link have a file extension. 
^[todo: write email to suggest that Draft should be able to link to another Draft document if the file extension is missing.]

I wish Draft could let me set a default page, so that I could then use document links to let me navigate between my documents, as I can with Ema.

The user interface could be similar to stack edit. One could swipe between different views of the same document:
* markdown
* preview
* outline or table of contents. I could click on TOC entry to go to that.
* list of other documents which link into this one
* list of documents this one links to
* dot graph diagram of local links
All views would be synchronised so that I could swipe between markdown and preview.


###Ema

Ema Personal Wiki

When I got an Android phone, I looked hard for [Wikidpad](#wikidpad) or anything like it.

When I started to write on my phone, I wrote most of my text files in [Ema Personal Wiki](https://play.google.com/store/apps/details?id=com.janwillemboer.ema&hl=en_GB). 

I loved the way it would create a new file for me with the correct title when I clicked on a link I had written. Draft doesn't do this. 

I love the way Ema lets me build my own home page from which I can navigate my notes. I wish Draft would do that using the new internote navigation.

However, some of the link formats Ema uses, such as CamelCase and {link} don't work in pandoc. I emailed Ema to find out if it would support markdown type links, but those weren't seen as important.

I didn't want to spend a lot of time writing pages in one plain text format and have to change to another. I have a feeling [Pandoc](#pandoc) will be around for a while.

I've noticed recently (way before August 2014) that [Ema hasn't been updated much](https://github.com/janwillemb/Ema-Personal-Wiki).

Unfortunately Ema doesn't understand markdown links, so as I migrate to Draft, or other markdown software, I won't be able to go back. As I migrate, I will need to find a way to search for CamelCaseWords and {curly brackets}, since those are the current link markers in Ema, and I will need to replace those with Markdown links.


###Dropsync
-----------
Keeps all files uptodate on both Android and Dropbox


##Draft

I have started to use the [android app](https://play.google.com/store/apps/details?id=com.mvilla.draft&hl=en) ["Draft"](http://www.mvilla.it/draft/).

I prefer to not repeat myself, and to put a link to a document which explains something, rather than explaining it again. This is one reason why [links to another document](#links-to-another-document) are important. 

If I'm scrolling down, reading my document, and I see an error, then I'd expect to click the edit symbol and be at the markdown view scrolled down as far. Instead I'm back at the beginning.

[Instiki](#instiki), [Wikidpad](#wikidpad) and [Ema](#ema), all did a good job with this. If I specified a link, and the document didn't exist, Ema created a blank document with that title.

I wish I could find text within a document. I use control-F then hash word to get around this long document, when I am in another editor.

###Colophon in Draft

This particular Colophon is specifically to test [Draft](#draft) and [Pandoc](#pandoc).

I want to make sure that documents that I create and edit in Draft will be processed correctly by Pandoc to create the outputs I want.

###Draft data loss Bug Report

Date: 9 August 2014 14:55
Subject: Draft lost my changes and my document.
To: Matteo Villa <info@mvilla.it>


Writing underground, editing a long document. Turned off phone when changing trains with document open because I didn't want to lose my place.

Turned on phone. Draft running but showed me list of documents. Opened document I was working on. Completely blank. Zero characters.

So, I lost all the changes I made in my first train, and unable to make changes on my second train.

Synced when I got cell service again. Document blank.

Here are my current settings for Draft:

* File sort alphabetical
* close note editor on save checked
    * (perhaps I should have that off)
* show quick bar unchecked
* ms Windows compatible unchecked
* linked to Dropbox
* remote folder: draft
* show images unchecked
* sync on file open checked
* sync on saved checked
* background sync never
* show sync notifications checked

Perhaps my mistake was that I didn't save the document before turning off the phone.  That's a bitter lesson to learn.

Perhaps Draft should automatically save documents that are unsaved when screen goes off for any reason.

Dropbox kept a copy of my last known good version, so I could revert to that using Dropbox in my web browser.

Please respond somehow so that I know that this is a useful way to file a bug report.

Thanks for your work on Draft.

kind regards,

Frank


##Directory Structures and Searching

I currently have my files in a fairly disorganized directory structure.
Searching on my laptop has some hurdles. This is why I like the link structure within documents.

##StackEdit

This is a Chrome browser app.
^[todo: set up links to StackEdit.]
It syncs to dropbox folder. 
It stores local versions in profile folder, not referencing dropbox folder. 
I found it hard to figure out how to reference an entire dropbox folder, not individual files.

I'd rather use Stackedit than Gedit, since it gives me instant formatting responses, but I don't trust the Dropbox integration.

One of the great things that StackEdit does is help you navigate easily in a long document by rendering the table of contents live. 

It also keeps the markdown scrolling in sync with the html rendering. This means that when I'm reading my test in preview, the markdown is scrolling at the same time, so when I see an error, I can edit it right away.

One problem with Stackedit is that it doesn't understand backticks. So headers within backticks are rendered into the table of contents.

[In Firefox](https://write-box.appspot.com/)

In Chrome: 

* [SourceKit](https://chrome.google.com/webstore/detail/sourcekit/iieeldjdihkpoapgipfkeoddjckopgjg/details) or 
* [TextDropApp](http://www.makeuseof.com/tag/edit-text-files-dropbox-browser-textdropapp/)
NB TextDropApp transmits data unencrypted between browser and their server.

[Textdrop](https://www.textdropapp.com/home/Home) with multimarkdown support

One problem with Stackedit I run into is when I zoom in and out of the page. The table of contents window and the messages don't reframe automatically. I have to refresh the page.

I love the table of contents feature in StackEdit. It would be great if it could be a third pane for a widescreen monitor. 

###Stackedit reference function.

##Org Mode

My first computer editing was done using Emacs. Apparently there is an enhancement of Emacs called Org Mode which helps one keep track of all the things one needs to do. Apparently Pandoc can translate to org mode. I'm not sure I am prepared to switch my to do list work flow to org mode.

I've tried to keep track of all the things I need to do within this document. I used to have the todo: in the text, but I've moved them into footnotes. I'd like them to stand out more clearly in the text by having a blank line before the caret and square bracket, but if I do that then the footnote number appears on a line by itself.

I currently keep my todo list in Trello because I like the user interface. I wish there were a way to integrate Trello with this text writing as well as sorting out importance and scheduling.
^[todo: look at using Haskell to connect Trello to 'todo:']

is this a good way to parse text files for json or yaml type data?
or should I just use stack edit to edit the text files and some other programming language to parse the text files?
or should I just build tables and queries and forms?




Output
======
##Pandoc

TLDR; Pandoc is a suite of tools which convert files from one format to another. 

For documentation, look at [the markdown](http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html) @PandocMarkdown and [the comprehensive instructions](http://johnmacfarlane.net/pandoc/README.html) @PandocGuide.

I've written [below](#pandoc-testing) on my own testing of Pandoc.


Markdown
---------
I need to make sure that the pages are well behaved markdown which is going to render  properly into:

* html/mathjax 
* latex
* pdf with internal and external hyperlinks
[Help with Markdown](http://support.mashery.com/docs/customizing_your_portal/Markdown_Cheat_Sheet)


Latex
--------
Since I want to write academic papers, I think I will want to output them as latex. 

Book Reviews
-----------------
One thing I could do with pandoc is to write book reviews of the books I have found important.
This would let me build up an annotated bibliography.
It would let me build up writing on Amazon and Goodreads.
I could put the reviews on Less Wrong and other related sites.
I could tie this all together with the Google Author stuff below.

xArchiv and PhilPapers
------------------------
If my papers ever get interesting enough to publish, after I have shown them to my friends, I would like to put them up on some archive websites. I wonder whether those allow for comments. How did the HOTT book handle that? Did they put their book on xarchiv?

(Distributed Open Access Academic Work)
--------------------------------------
todo: Find that web page I sent to Kathleen which described an open format using twitter hashtags and @ symbols to connect into the academic universe. 


JSON
----------
I like the idea that the text pages can include JSON tags that a script can harvest and link back to the including pages, like my old favourite wiki programme would do. Wikidpad.


IF JSON doesn't work with PanDoc, perhaps the thing to use instead of JSON is [Haskell Literate](#haskell-literate) format, and to include information in a Haskell friendly format. 

For example, to keep track of things I want to do, one thing I could do is to write todo: at the start of a new line and hope that it would be picked up as JSON. Or the other thing I could do would be to write it in Haskell and have it be a chunk of information to be processed.



##Building Scripts
The building script would take a list of web pages and render those only into the platforms above:

* xarchiv
* philpapers
* google plus


books
---------
Electronic books sold through Google Play and Amazon
Physical books, for example of photographs
Printed on scroll and folded
Printed on A4 laser black and white and colour

Academic papers 
--------------------------------
Place to put my papers and find a discussion
Become part of the community.

* Xarchiv 
* SSRN
* Philosophical Papers web site

high ranking in Google Scholar searches

frank.colcord.net
-----------------
My writing as pages on my web site.
I could point that url to my github pages.
Website of static pages
with a place for comments
Website of dynamic pages using javascript

[Authorship markup and web search](http://googlewebmastercentral.blogspot.co.uk/2011/06/authorship-markup-and-web-search.html)

##Blogging

I'd like to be able to use the same files for blog entries as for papers.
This is one reason why [links to another document](#links-to-another-document) are important. 

These files could also be rendered as static html on a blog with a separate commenting system, whether that is google plus, or something else. That could be done through a Dropbox app. 

It would be great to be able to change articles, and have the web host keep track of changes, in case previous viewers want to see what has changed. (Which websites I read handle this well?)

Dropbox itself?
> Use Dropbox as a web server: put your site in the public directory, and copy the public link to the homepage (index.html or whatever). You will then be able to browse around the site normally from this URL.

So, theoretically, I could use pandoc to publish html to my public folder.

[Scriptogr.am](http://scriptogr.am/about/)
* claims to be for writers
* variables (need to see if this is pandoc compatible)

> Scriptogram will soon support custom variables. This will probably not be used by the majority of you, while I think this will open up endless possibilities for designers & developers when creating blogs on Scriptogram. For example, let's say you want to use a thumbnail for each post in the archive instead of the post links, or you want custom CSS for each post, or you want some sort of text to appear dynamically on each page but not in posts etc etc.

* last activity on blog Sept 2012 :(
* homepage (c) 2012 :(

[DropPages](http://droppages.com/getting+started) 
* seems good
* Seems to handle page titles and sections in a non-pandoc [way](http://droppages.com/getting+started/formatting+content)

[Pancake.io](https://pancake.io/)
* very simple, not clear it is being maintained



###Gitpages

These PersonalWiki files could sync to github, where github would handle the versioning and the rendering as web pages, as well as the interlinking. I wonder whether github will draw clickable maps the way that Instiki used to.

I think the program is called Jekyll which renders github pages into static html.

Stackedit has a [discussion](https://github.com/benweet/stackedit/issues/27) which explains how to post the markdown to github.

github wiki compatible
in case I want to put my projects there

? what is the form of mark up that it uses?


Less Wrong
------------
my writing as posts for Less Wrong
other websites 
a partially examined life
less wrong
hacker news


###Google Plus

[Google Plus Authorship](https://plus.google.com/authorship)


Activities
==========

Twitter
-------
sending out tweets with links to my pages




Test More
==========
I like blogs where you see a title and the first paragraph, and then a link to "continue reading". There is a standard markdown format for this feature. 

For some renderers, having the following text in the markdown document accomplishes this:

`<!--more-->`

I was thinking that if I used Google Plus and Twitter, the text before the More would be sent out. So the characters should be less than 140.

Test Internal Anchor
====================

This test links within the same document.

[This link](#tables) should take you down to header Tables near the end of this document.

This works in Draft, as long as there is no capitalization in link's anchor text.
It also works in Pandoc pdf and html. 
Works in Stackedit.

See the [Introduction](#introduction).  
Stackedit url generated: https:/stackedit.io/#introduction

See the [Introduction].  
[Introduction]: #introduction  
Stackedit url generated: https:/stackedit.io/#introduction


Links to another document
==========================
I think most of my confusion, contradiction and fallacies come up in my expectations around linked atomic documents being compounded in different ways in different formats.

Some website pages don't have htm or html extensions, so hypertext links with no extensions are completely valid.

Editors should open the linked document in a new tab so user can jump between tabs through clicking on [hypertext](#links-to-another-document). The files should be saved at each jump. It should be easy to see what has changed in each version of the file. Links should also be able to point to headers within the other document, not just opening at the top.

But I realize that I want Pandoc to have those links go either outside a document to an external web site, or within a document to a different section of the document, or to another document in the same directory. 

This may get complicated when the epub is constructed from multiple documents through a build document.

I want the same behavior with links in all the formats: epub or PDF or web pages or web editor or android app.

But I don't want it to have the extension there. I want the renderer to put whatever the extension is likely to be, eg txt or html. 





Assuming there is a page called test.txt with the following contents:

````

#this is a test

Lots of text so you can see whether link takes you to anchor or just opens file.

##footer

[Link to Colophon linking tests ](Colophon.txt#tables)

````

Links that work in Draft
---------------------------
<http://google.com>  
<sam@green.eggs.ham>  

"and here's [one with a title](http://fsf.org "click here for a good time!")."

Bug: pandoc pdf links-as-notes doesn't show title in footnote

###have to specify extension

The is the only link format I can get to work in Draft is: [test](test.txt)  

`[test](test.txt)`

This works in Draft.
It also works in Pandoc pdf, to the extent that it opens the txt file in gedit. Not really what I want.
It also works in Pandoc html, but opens the txt file in the browser. "file:///home/frank/Dropbox/Draft/Colophon/test.txt"

###anchors in external documents

Since I expect my documents to get quite large, it would be great to be able to point to a particular header within an external document. I expect to be able to do this in .html, less hopeful for .pdf and not hopeful for .txt files.

####txt extension
Anchor text doesn't work when pointing to separate document:
[test](test.txt#footer)  

    [test](test.txt#footer)  

This almost works in Draft: it doesn't go to anchor.  
It also works in Pandoc pdf, to the extent that it opens the txt file in gedit.  
It also works in Pandoc html, but opens the txt file in the browser.
Pandoc doesn't change the extension from .txt to .html.  
This works great in Stackedit without the custom extension.  
EMA personal wiki: doesn't work (this gets can't find app to open file)  


####html extension
This works well work in pandoc html:
[test](test.html#footer)  

    [test](test.html#footer)  

Pandoc pdf links-as-notes doesn't open anything.
Pandoc pdf links don't open either. Could be my pdf/browser set up.
Maybe I need to give the directory structure: [test](/test.html#footer)  

    [test](/test.html#footer)  

That didn't work in Pandoc pdf. 

####pdf extension

There is a pdf plug in for Zotero which is able to take you to the particular page in a pdf. I'm not sure if there is an html formatted link which will do this. 
^[todo: google html formatted link to pdf page] 
^[todo: research Zotero plugins for pdfs] 

##Links that work in Pandoc pdf but not Pandoc Html or Draft

###no extension
This is the link format I would like to use when I'm writing, since the file extension isn't required:  
single word in round brackets:

Test of no extension plus anchor: [test](test#header)  

    [test](test#header)  

EMA personal wiki: doesn't work (this gets can't find app to open file)  
Stackedit says page not found

Does this work in Draft?
This link works in Pandoc pdf, opens the test.pdf file, but doesn't go to anchor.
[Pandoc pdf links-as-notes](#pandoc-pdf-links-as-notes) doesn't append the pdf extension, so the links don't open anything.
No, this doesn't work in Pandoc html. the browser is looking for a file with no extension: `file:///home/frank/Dropbox/Draft/Colophon/test#header`
^[todo: figure out why Pandoc html doesn't generate link with html extension, since it does create pdf extension.]

###one forward slash
This is an [inline link](/test)

In Pandoc pdf: The inline link works well. But pandoc pdf doesn't show a title.
In Pandoc html the inline link is looking for a file with no extension. The title shows up.
^[todo: set up internal links so that it is clear what the following mean:'Pandoc pdf' and 'Pandoc html' and 'Pandoc pdf links as notes']

One forward slash no extension: [test](/test)  

    [test](/test)  

The above works in pandoc pdf. Opens external pdf file.
Doesn't work in Pandoc html, since it is looking for a file with no extension: `file:///test`  
Stackedit says page not found


##test absolute and relative links

Draft says:
    Both absolute ( [Absolute ref](/folder/subfolder/note.txt) ) and relative ( [Relative ref](subfolder/note.txt) ) paths are supported.

* [Absolute ref](/testfolder/subtest)
* [Relative ref](testfolder/subtest)

`````
[Absolute ref](/testfolder/subtest)  
[Relative ref](testfolder/subtest)  
`````

Will Pandoc see the same absolute and relative links?
Yes, Pandoc generates both type of links. Relative link works. Absolute does as well. 
Perhaps that distinction is more important in Draft than in Pandoc.
In Pandoc html the absolute and relative links seem to be inverted. 
If I swap the slash in front of testfolder, I get the results I expect:

* [Absolute ref](testfolder/subtest) generates "file:///home/frank/Dropbox/Draft/Colophon/testfolder/subtest"
* [Relative ref](/testfolder/subtest) generates "file:///testfolder/subtest"

Perhaps the above inversion is a bug in the implementation in Draft.

This kind of absolute reference doesn't work in pandoc. Pandoc seems to generate references from the current document location.

`
[Absolute ref](~/Dropbox/Draft/Colophon/testfolder/subtest)
`

Absolute doesn't work but Relative does. Need to make sure Absolute reference is accurate. Not sure that absolute paths will match up between Android and Ubuntu. So relative is not from document but from Draft document folder.


##Links that don't work in Draft or Pandoc

The following tests don't work in Draft though they are legitimate links in markdown, and much easier to write, and avoid ambiguity in file extensions.^[todo: find citations which explain these are legitimate links]

[Test]() of empty round brackets:

`[test]()`  

This doesn't render into a link in Pandoc pdf.
In Pandoc html the empty brackets create a link back to the same document: `file:///home/frank/Dropbox/Draft/Colophon/Colophon.html`.

EMA personal wiki: doesn't work.  
Stackedit returns to same page.

###double square brackets
single word in double square brackets:
[[test]]  

This doesn't even render in Draft, nor Pandoc pdf.  
EMA personal wiki: doesn't work  
Stackedit: doesn't format to link  


###surrounding forward slashes
Forward slashes round word in brackets. This uses [syntax on daring fireball](http://daringfireball.net/projects/markdown/syntax#link) for resources on same server: [test](/test/)  

    [test](/test/)  

The above doesn't work in Pandoc pdf since the link generated is to "/test/.pdf".  
Doesn't work in Pandoc html, since it is looking for a file with no extension: `file:///test/`  
Stackedit says page not found.  


##Kludge work around

One thing I could do would be to:

* write all my links using the file extension ".txt". This would mean that the links worked in Draft.
* preprocess the markup files to delete the .txt file extension when running pandoc to create pdf files, this would turn the links to .txt files into links to .pdf files.
* or replace the file extension with *.html when generating pdf files and html files. Since the user might only have that one pdf file. I can't assume the user has the other pdf files. this would turn all links to .txt files into links to .html files. But those would need to have the full URL not just the html page.

[Stackedit](#stackedit) got around this because the developer wrote me an extension which did this automatically.


#Footnotes Testing

Here is a footnote reference, [^1] and another.[^longnote]

[^1]: Here is the footnote.

[^longnote]: Here's one with multiple blocks. Not really. Don't know what happened to the other blocks.

    Subsequent paragraphs are indented to show that they
belong to the previous footnote.

        { some.code }

    The whole paragraph can be indented, or just the first
    line.  In this way, multi-paragraph footnotes work like
    multi-paragraph list items.

This paragraph won't be part of the note, because it isn't indented.

The above two formats work in Draft, Pandoc pdf and html.
The first footnote format works in StackEdit.
The second format, longnote, doesn't work in StackEdit, since Stackedit doesn't realize that the subsequent paragraphs are still part of the footnote.

Here is an inline note (with space, square bracket, caret, text) [^Inline notes are easier to write, since you don't have to pick an identifier and move down to type the note.]  
The above format doesn't work in pandoc. Works in Draft. 
 ^[todo: test whether this format works well in StackEdit.]

Here is another format for inline note (with space, square bracket, caret, space, text) [^ Inline notes are easier to write, since you don't have to pick an identifier and move down to type the note.]  
The above format doesn't work in pandoc.Works in Draft.
^[todo: test whether this format works well in StackEdit.]

Here is another format for inline note (with space, caret, square bracket, text) ^[Inline notes are easier to write, since you don't have to pick an identifier and move down to type the note.]  
This last format above works in pandoc pdf and html.  
This doesn't work on Draft or [stackedit.io](https://stackedit.io)  


In pandoc pdf footnotes don't have link back to the main text, while they do in Draft and pandoc html. ^[todo: test whether StackEdit footnotes link back to main text.]

###double round brackets
this sentence has a footnote ((here is the text of the footnote))

In pandoc pdf or html, the double round brackets don't work.  
This doesn't work on [stackedit.io](https://stackedit.io))  

###Mangled multiple footnotes
I've started to put my todo: items in foot note format. 
They look fine in pdf, but not in html.
I like having them left aligned against the left hand column.
This lets me see them easily.
If I have several in a row, then they can cascade and not be rendered correctly. I think this problem has to do with the blank spaces following the right square bracket. If there aren't any spaces, then it causes problems. 

If I put just one space (including after the colon at the end of this paragraph) then it works:  If I put two spaces it doesn't work. 
^[todo: write out several todos here.] 
^[todo: One space follows this] 
^[todo: one space follows this] 
^[todo: one space follows this] 

#Tables

[This link](#test-internal-anchor) should take you back to the part holding the testing of anchors.

In pandoc pdf, the above link works, it takes you back to the introduction anchor.

This Format works in Draft and pandoc pdf:

| testTitle1 | testTitle2 |
|----|----|
| text one | text two |

Not sure how to get vertical lines in the tables.
^[todo: research css and see if it can make footnotes and tables more helpful]

Not sure if this following table format is still not working in Draft. I may have fixed it for Draft when I fixed it for pandoc pdf and html.
I made the following work in pandoc pdf by making sure the text aligned with the dotted lines.

test test  yet
---- ----- ----
test tray  test 

Tables will probably look better in pandoc html with proper css references.

#Title portion

Pandoc likes for each text document to have a part at the top to hold data. However, it looks like Stackedit and Draft don't hide that when rendering html.

##Reasons to do it

[Introducing schema.org: Search engines come together for a richer web](http://googlewebmastercentral.blogspot.co.uk/2011/06/introducing-schemaorg-search-engines.html)

[Author rank](http://www.blindfiveyearold.com/author-rank)

[Google's Agent Rank patent](http://appft.uspto.gov/netacgi/nph-Parser?Sect1=PTO1&Sect2=HITOFF&d=PG01&p=1&u=%2Fnetahtml%2FPTO%2Fsrchnum.html&r=1&f=G&l=50&s1=%2220110213770%22.PGNR.&OS=DN/20110213770&RS=DN/20110213770)

[How to do it](https://support.google.com/webmasters/answer/1408986?hl=en) and [here](https://plus.google.com/authorship)


##pandoc simple header
% Colophon  
% Frank Colcord (frank@colcord.net)  
% 2014-08-08  

The above doesn't work in Draft, nor in Stackedit. But it looks least bad. Perhaps I should keep it.

##pdf header
I love the way this can work with Pandoc in either book or paper format to show the title and the author. I haven't figure out how to get the abstract to show. I think that needs me to learn more about latex templates. I'd like to figure out how to generate papers in the standard latex format which includes the abstract. 
^[todo: google latex and documentclass]

NB: Stackedit has formats the backticks in bold as if they were second level headers if they are followed by a line of underlines. So I have put spaces below.

###simple pdf header

````````````````

---
title: Colophon
author: Frank Colcord 
date: 2014-08-08
...

````````````````

###more complex pdf header

````````````````

---
title: Colophon
author: Frank Colcord 
	(frank@colcord.net)
affiliation: Independent
abstract: |
  This document explains the open source components I use to write

  1. It provides links to each component
  2. It also allows me to test that the components work together 
     and *produce what I want*

tags: [useful, wiki]
...
````````````````

##epub header:
It looks as if I am going to need different YAML depending on whether I want to generate an epub or pdf.

the above came from http://johnmacfarlane.net/pandoc/README.html#epub-metadata

These headers causes problems to stackedit: large portions of the text are hidden from the table of contents.

These header are not properly rendered or hidden by Draft.

maybe the epub headers should be separate documents prepended to the documents through a separate file.

###Plain epub header

````````````````

---
title:
- type: main
  text: Colophon
- type: subtitle
  text: An investigation of methods of writing
subject: open source software
description:  |
  This document explains the open source components I use to write

  1. It provides links to each component
  2. It also allows me to test that the components work together 
     and *produce what I want*
creator:
- role: author
  text: Frank Colcord 
- role: editor
  text: Not Yet
identifier:
- scheme: DOI
  text: doi:10.234234.234/33
publisher:  Not Yet
rights:  (c) 2014 Frank Colcord, CC BY-NC
date: 2014-08-07
...
````````````````

the above should work. It doesn't contain the nocite: field.

###Epub with nocite

````````````````

---
title: Colophon
author: Frank Colcord 
	(frank@colcord.net)
affiliation: Independent
abstract: |
  This document explains the open source components I use to write

  1. It provides links to each component
  2. It also allows me to test that the components work together 
     and *produce what I want*

tags: [useful, wiki]
nocite: |
   @MarkdownIntro, @MarkdownBasics, @MarkdownSyntax, @MarkdownFuture, @GithubMarkdown, @ZoteroMarkdown, @PandocGuide, @PandocMarkdown
...

``````````````````

#Table of Contents

TOC
----
##Stackedit TOC

[TOC]

this works in [StackEdit](#stackedit) with a space above and below it. It doesn't work in Pandoc.

##Pandoc TOC

If I use the switch "--toc" on the command line, then it generates the TOC at the beginning of the document, both pdf and html. However the TOC in pdf doesn't have hyperlinks to the chapters. Not sure how to do that. He [admits](http://johnmacfarlane.net/pandoc/demo/example9/pandocs-markdown.html) it doesn't work in pdfs:
>Note, however, that this method of providing links to sections works only in HTML, LaTeX, and ConTeXt formats.
^[todo: figure out how to have hyperlinks in the table of contents of pdfs]

##neither Stackedit nor Pandoc

This is meant to generate a table of contents for the current page:

{{ TOC max-depth="3" }}

OK, try again:

TOC max-depth="3"

    TOC max-depth="3"



Multiple Documents
------------------
As I have said elsewhere in this document, I would like to be able to keep my writing modular, and have separate text documents for each concept, and link between the documents.

I would like to be able to combine these several documents into one large document, and have the links still work without any manual intervention. I don't mind running an automated script that could change the links.

I expect to be always changing the modular text documents, and so would be updating the related compound documents.

I see this problem as being quite similar to writing software.

Since I tell pandoc in the commandline argument the different documents that are going into the compound document, I would think that pandoc could handle this well. 

^[todo: Figure out, since anchor links work so well in Pandoc, and extensionless document links don't work in Draft, how can I work easily with multiple documents in Draft and bring them together in Pandoc?] 
^[todo: put another way: can pandoc convert links to external documents into links to internal headers? Perhaps the way to do this is to append the different documents together, and see whether the same links that navigate from one document to another in Draft will navigate within the same pdf. test [here](#test-internal-external-navigation). Perhaps there needs to be a pre-pandoc script which turns links that work for Draft into links that work for Pandoc.] 
^[todo: does pandoc have a switch so that the pdf's table of contents has internal anchor links to the headers within the pdf?] 


Mathjax testing
=================
I like the idea that Mathjax will render the complicated logical text in a clear way. I can't remember the connection between Mathjax and Tex. 
[Pancake.io claims to support Mathjax](http://blog.pancake.io/experiments/mathjax)
I assume they translate easily. 

[good source for Tex shortcuts](http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html)
Don't forget to wrap the Tex in dollar signs.


$\psi \cup \phi$ should render as psi union phi   

The above works in stackedit.
The above works in pandoc html if I use the -s switch.

$\left [ - \frac{\hbar^2}{2 m} \frac{\partial^2}{\partial x^2} + V \right ] \Psi
= i \hbar \frac{\partial}{\partial t} \Psi$

Pandoc pdf handles both of the above well. Pandoc html has trouble, at least with the last one without an internet connection.

#Music notation

I seem to remember reading somewhere that there was a markdown way of writing music. 
^[todo: google music pandoc]

#Zotero

Before Zotero I was using Furl to take snapshots of web pages I found interesting. I exceeded the service storage limit of 2GB. I downloaded the 2GB files, but haven't figured out how to parse them. I was going to do that as a way of learning Haskell. 
^[todo: parse 2 GB web logs.] 
^[todo: google for furl parsers.] 

I have been using Zotero since 2008 to hold web snapshots and book references. This colophon is the first time I have used the data for anything else than a sophisticated bookmark editor.

I used to use Zotero in the Mozilla Firefox browser. Now I use the standalone version, and shove in there web pages from my Chrome browser.

Unfortunately, there doesn't seem to be a good way to use Zotero on my Android phone.

I want to use Zotero to store all my references, web page snaphots and pdfs, as a good database. 
I want to use Zotero as a way to figure out what to read next.
I want to use Zotero as a way to use references in all my written work, so that people can see where I get my ideas from.

I would like my references to show up in different ways. 
In academic papers, I want the references to show up as the latex style sheet requires, or the academic format requires.
I'd like to have the choice to have references shown either with tiny numbers next to words, or as instantly recognizable abbreviations, eg [Winograd79] or [Wittgenstein27] (years???)
But I'd also like to have the choice to have references work in a way I have seen in several great books, where the reading text is clear, but at the end there are footnotes which show the page number, and then crucial parts of the text, followed by the reference text for the reader to know where to look for further information. This would be like a hyperlink if the same text was on html. 

I'd also like to use Zotero to keep track of all my notes on different books and web sites. 

I want everything I write to be fully referenced
through Zotero
cf monbiot fully ref

I want a place to write notes on everything I read. a lot but not everything comes through hacker news. sometimes the guardian, email, etc. I want an easy way to record what I find interesting, and to have a place to write notes on what I find interesting.

Zandy doesn't seem to do everything I want.

Zotero web app looks interesting but limited.

Zotero compatible
so I can record my sources and write notes on them, but then easily reference my sources on my writing
looks like Zotero mobile web pages are good.
zandy mobile app doesn't look so useful as offline database

I want to use Zotero to store all my references, web page snaphots and pdfs, as a good database. 
I want to use Zotero as a way to figure out what to read next.
I want to use Zotero as a way to use references in all my written work, so that people can see where I get my ideas from.

I would like my references to show up in different ways. 
In academic papers, I want the references to show up as the latex style sheet requires, or the academic format requires.
I'd like to have the choice to have references shown either with tiny numbers next to words, or as instantly recognizable abbreviations, eg [Winograd79] or [Wittgenstein27] (years???)
But I'd also like to have the choice to have references work in a way I have seen in several great books, where the reading text is clear, but at the end there are footnotes which show the page number, and then crucial parts of the text, followed by the reference text for the reader to know where to look for further information. This would be like a hyperlink if the same text was on html. 

I'd also like to use Zotero to keep track of all my notes on different books and web sites. 




##zotero better bibtex

Looks like [this](https://github.com/ZotPlus/zotero-better-bibtex) is a good plugin. This [Citekey explanation](https://github.com/ZotPlus/zotero-better-bibtex/wiki/Citation-Keys) explains how to put "bibtex:citekey" without quotes in Extra field in Zotero to specify the citekey. NB that the bibtex is in all lowercase.

##Zotero related links


* Zotero supports plug ins, for example [Citation Stylist](http://citationstylist.org/tools/) but that seems mainly for lawyers.
* [manual](http://zotero-manual.github.io/zotero-manual/citations).
* [Discussion of importance of citations](http://blog.martinfenner.org/2013/06/19/citations-in-scholarly-markdown/)
* [Other way to do it](http://www.carlboettiger.info/2012/05/30/knitcitations.html)
* [Google groups discussion](https://groups.google.com/forum/#!topic/pandoc-discuss/5e4hLtZShmU)
* [Zotero discussion](https://forums.zotero.org/discussion/25611/multimarkdown--bibtex-citekey/)
* [blog](http://zoteromusings.wordpress.com/)
* [AutoZotBib](http://www.rtwilson.com/academic/autozotbib)
* [Zotfile](http://zotfile.com/) is a Zotero plugin to manage your attachments: automatically rename, move, and attach PDFs (or other files) to Zotero items, sync PDFs from your Zotero library to your (mobile) PDF reader (e.g. an iPad, Android tablet, etc.) and extract annotations from PDF files.


##Generate Bib file

I am using [Zotero](#zotero) with the [zotero-better-bibtex](#zotero-better-bibtex) add on.

I found this worked for this Colphon document:

* Select Zotero entries (you can put them in a collection first, or tags, etc.)
* Make sure each entry has an entry in Extra which starts "bibtex:" and followed by your citekey
* right click and choose "Export Items...."
* Choose format "Better Bibtex" (installed through addon)
  (I havent tested the other checkboxes there, "Export Notes", "Export Files", "Use Journal Abbreviations".)
* After you choose OK, you will be given a choice of the file name to use and the directory to save the file in. Keep the .bib file extension, because pandoc will need it. Save the .bib file in the same directory as your main file. I have saved it as BetterBibTexFormat.bib in the same directory as this colophon.txt file.

[Here](http://blog.yoavram.com/citations-in-markdown-using-pandoc/) is someone who has had trouble using citations in pandoc. I don't see in there how he gets the citation abbreviations automatically.

##Citations and References

I'm not sure what the switch `--citation-abbreviations=FILE` is for.
I think I have got around using it through my steps of generating a bibliography. I have taken this out of my testing.

##citation formatting:

http://citationstyles.org/downloads/primer.html

##Link Rot
One reason I have used Zotero is to be able to store snapshots of web pages I find interesting, so that if the pages stop being hosted I can still read them. Zotero has a paid option to store snapshots on their own cloud. I wonder if there is a citation style which gives the page URL, title, but also the zotero URL. 
^[todo: add to citations zotero URLs to anticipate link rot.]

##Mac only software notes on citation

> For those who are interested, I've found that pandoc works extremely well with bibdesk (bibliographic management), zotero/zot2bib (for webscraping), and pocket bib (for ipad reading/editing). Pocket bib is particularly cool becuase it lets you easily navigate your bibdesk bibliography and download any pdf you're interested in. It doesn't have a native pdf editor, but it easily sends the pdf to an external editor (e.g. Goodreader) which can then send the edited pdf back to pocket bib for uploading to the server. This eliminates having to navigate a file full of PDFs on dropbox. [discussion](https://groups.google.com/d/msg/pandoc-discuss/5e4hLtZShmU/xOuZy6tJdgwJ)

then just following that last message:

> Apropos of this, I finally got around to configuring my copy of BibDesk to support dragging and dropping pandoc-style [ `@citekey` ] citations instead of the default BibTeX-style \cite{citekey} citations. Here is the BibDesk template:

> https://github.com/dsanson/bibdesk-pandoc-citation-template

> It should also be possible to set up BibDesk to option-drag and drop a markdown formatted bibliography, using a simple template to feed pandoc as a post-processing script, but my initial attempts at this were not successful. 
^[todo: sort out citation for that quote]

[Bibdesk](http://bibdesk.sourceforge.net/) is [Mac only software](http://en.wikipedia.org/wiki/BibDesk), so I can't use it.

#Cascading Style Sheets (CSS)

##blog formatting

###table formatting



###print listing of internal links

From [documentation](http://johnmacfarlane.net/pandoc/README.html#templates): 

> links-as-notes
> causes links to be printed as footnotes in LaTeX documents

and 

> For pdf output, customize the default.latex template.

NB: From [documentation](http://johnmacfarlane.net/pandoc/README.html#templates): 

> links-as-notes
> causes links to be printed as footnotes in LaTeX documents


Some people will either print out pages or print out the pdfs, so the neatly formatted links will just show the link text and not the web pages. I'd like to give them the web pages as well. Proper citations print out the links well, but inline links don't. This might be a CSS issue.
^[todo: figure out how to print out a listing of all the links in this document.]

I know some web pages have the text of the links hidden, but if you print out that page, the formatting is quite different, and the links are explicity listed at the end so one can hand type the link into a browser.
^[todo: google css print link]
^[todo: once you have decided on css then put path in YAML under stylesheet: 
[documentation](http://johnmacfarlane.net/pandoc/README.html#epub-metadata)]

I have this figured out for [pdfs](#test-links-as-notes) but not yet for html.

#Pandoc Testing

Citation doesn't like long path names, so cd to the right directory.
^[todo: can pandoc generate a list of links which don't work, both internal to the document, internal to the directory structure, and external on the web? This would be an important way of checking the document, that the links haven't rotted.]

##installation of pandoc

Make sure your operating system has the following installed (together with all dependencies):
* pandoc
* pandoc-citeproc

using [above steps to generate bib file](#generate-bib-file)

###Pandoc pdf links-as-notes 

`
cd ~/Dropbox/Draft/Colophon/
pandoc Colophon.txt --toc -N --bibliography=BetterBibTexFormat.bib  -o ColophonLinksAsNotes.pdf -V links-as-notes
`
This works great.

###For html: 

`
cd ~/Dropbox/Draft/Colophon/
pandoc Colophon.txt --toc -N --bibliography=BetterBibTexFormat.bib  -o ColophonLinksAsNotes.html -V links-as-notes -S -s
`
This doesn't show the links as notes.
Don't forget the -s and -S above because otherwise your html will have a lot of strange characters inside.


#### this generates a pdf in a book format with numbered chapters.

`
cd ~/Dropbox/Draft/Colophon/
pandoc Colophon.txt --toc --chapters -N --bibliography=BetterBibTexFormat.bib  -o ColophonLinksAsNotes.pdf -V links-as-notes
`

I notice that the abstract (that I have put in the YAML in the begining of the text) doesn't show up.

## test for html

`
pandoc ~/Dropbox/Draft/Colophon/Colophon.txt -o ~/Dropbox/Draft/Colophon/Colophon.html -s
pandoc ~/Dropbox/Draft/Colophon/test.txt -o ~/Dropbox/Draft/Colophon/test.html -s
`

### this adds a table of contents to the html files
`
pandoc ~/Dropbox/Draft/Colophon/Colophon.txt -o ~/Dropbox/Draft/Colophon/Colophon.html -s --toc
`

### test html with bibliography

## test for epub (electronic book)
`
pandoc ~/Dropbox/Draft/Colophon/Colophon.txt ~/Dropbox/Draft/Colophon/test.txt -o ~/Dropbox/Draft/Colophon/ColophonTest.epub3 --toc
`

### test epub with bibliography

##test to generate word document

##test to generate open format document

##test org mode export 
`
pandoc ~/Dropbox/Draft/Colophon/Colophon.txt -o Colophon.org
`

perhaps I need to write out todo: into to-do:

#### tests for citations and references
`
pandoc ~/Dropbox/Draft/Colophon/Colophon.txt --toc --chapters -N --citation-abbreviations=cit.txt  -o ~/Dropbox/Draft/Colophon/ColophonCit.pdf
`

`
pandoc ~/Dropbox/Draft/Colophon/Colophon.txt -o ~/Dropbox/Draft/Colophon/ColophonBibCit2.pdf --toc --chapters -N --bibliography=~/Dropbox/Draft/Colophon/test.bib --citation-abbreviations=cit.txt
`

##Test Internal External Navigation

Put two documents together, Colophon and test, and see if the links work between them:
`
cd ~/Dropbox/Draft/Colophon/
pandoc Colophon.txt test.txt References.txt --toc --chapters -N --bibliography=BetterBibTexFormat.bib  -o ColophonBib.pdf
`

##Test Links as Notes

NB: From [documentation](http://johnmacfarlane.net/pandoc/README.html#templates): 

> links-as-notes
> causes links to be printed as footnotes in LaTeX documents

and

> Variables may be set at the command line using the -V/--variable option. Variables set in this way override metadata fields with the same name.

#### this is an attempt to specify the directory holding the files for pandoc processing:
`
pandoc --data-dir=$Home/Dropbox/Draft/Colophon/ --toc --chapters -N Colophon.txt   -o ColophonMultiple.pdf
`


#References

I'd also like to know how to put all the footnotes in the end of the document. I'd like to have the option to hide all the footnote numbering, but to have the footnotes at the end. I once read a book which had no indication in the text that there were any footnotes, but at the end, there was an appendix with all the footnotes, showing the page number and a quotation of the text that the footnote referred to. I'd love it if Pandoc would do this. 
^[todo: figure out how to have inobtrusive endnotes through pandoc.] 
^[todo: figure out how to have an appendix of Author references.] 
^[todo: figure out how to have an appendix of keyword references.] 


Pandoc [says](http://johnmacfarlane.net/pandoc/README.html#citations) there is a way to make sure the citations show up in the bibliography even if they are not mentioned in the text. Pandoc has commas between entries, rather than a list. Doesn't work as a list. The format in the example leads to strange right alighted text to the end of the document (before the references are appended). I've tried to have the nocite metadata field in the References section, but it gets rendered in the html output. So, I've had to put the nocite field in the first header of the document.

Pandoc should put all the references used in this document, sorted by title, after the line below.
^[todo: figure out how to have references sorted by author. I'm sure that depends on the citation style chosen. Where is that chosen? Can it be specified in the YAML at the beginning of the document?]

If the references aren't below this, but you see other text, then probably other documents have been appended to the main Colophon.txt.

---------------------