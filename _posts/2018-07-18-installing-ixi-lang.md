---
layout: post
title:  Installing ixi lang - tips and tricks (updated 11/01/2019)
tags:
- News
- Blog
- ixi lang
- Tips
---

My last record, [Tell Me I Can Fix This On My Own](http://deerful.bandcamp.com/album/tell-me-i-can-fix-this-on-my-own), was made with ixi lang, a programming language built on top of Supercollider by [Thor Magnusson](http://www.ixi-audio.net/thor/) for live-coding music. I love it to bits, it's a wonderful introduction to creative programming, and I want everyone to try it.

I've also had a few messages from people who are struggling to get it working, since it can be a little tricky. Here's what I've figured out so far about getting it up and running. Please let me know if you have any questions, or if you find any other workarounds. I'll update this post with any new information as and when I get it.

**Please note, I am not the developer and do not know the nuances of why the various versions do and do not work. This is solely a guide to installation. Bug reports about how the software itself works should be directed to Thor - I can't help with those!**

---

### For OS X users - standalone app
The standalone app is the simplest option, but only works on OS X.

If you are on a Mac running Sierra or later, **the version linked from the form on the ixi lang website will not work.** [Use this link to download ixi as a .dmg instead](http://www.ixi-audio.net/ixilang/thanks.html). **This appears to work for most people.**

After you run the .dmg, make sure you drag the files inside somewhere on to your system, rather than trying to run them straight from the popup window - another user has told me this worked for them.

**That said, none of this worked for me.** I was only able to install the ixi standalone app on my Mac by copying and pasting the files from an old machine I'd installed it on back in 2016. I don't know why this is! [My build is available here](https://drive.google.com/open?id=1fbuUajo_wI8leOOn9WsOexts-DfGmZnN) - download the 'ixi lang' folder to anywhere on your computer, and just run the app from the file with the orange icon. 

Bear in mind that this is a very old version - it seems to work for most people, but it probably shouldn't! Saving snapshots appears to be slightly bugged and inconsistent, but it is functional enough for me to perform live from it.

---

### For OS X and Windows users - Supercollider classes
If you're on OS X, but can't get the standalone app working, *or* you want to use ixi inside SuperCollider, you need to install it as a Supercollider extension. 

If you're on Windows, there is no standalone app, but you can use ixi inside the program SuperCollider. 

**Ignore the instructions on the ixi lang website** - the links are incorrect, and the released version does not work on newer versions of Supercollider.

[Try these instructions](https://drive.google.com/open?id=1IxaBenVLOjEx8dwtG_itrF16Z0NodTTfkZAbhgjW2Ts), using a version of the software edited by [Lucy of Heavy Lifting](http://twitter.com/abelstaites). In OS X, initialising projects and assigning samples seems to be extremely buggy; I cannot get ixi to automatically create the files it needs to run, so I have provided links to do this manually. 

I have not tested it in Windows, but according to Lucy it should run smoothly. 
