---
layout: post
title:  Installing ixi lang - tips and tricks
tags:
- News
- Blog
- ixi lang
- Tips
---

There's been a small flurry of interest across my social media accounts the last few days around ixi lang, a programming language built on top of Supercollider by [Thor Magnusson](http://www.ixi-audio.net/thor/) for live-coding music, which I've rediscovered and am finding enormously inspiring as a songwriting tool. I've released two songs ([Bloom](https://www.youtube.com/watch?v=MJSRAuPQoA8) and [The Seaside Town](https://www.youtube.com/watch?v=NAyDQdjcNq0)) using it, and will be playing [a show with it in Sheffield in September](https://tickets.partyforthepeople.org/events/4156-algorave-sheffield). You can follow my progress in songwriting with it [at my Github](https://github.com/emmawinston/ixilang-experiments). 

I've also had a few messages from people who are struggling to get it working, since it can be a little tricky. Here's what I've figured out so far about getting it up and running. Please let me know if you have any questions or problems, or if you find any other workarounds. I'll update this post with any new information as and when I get it.

---

### For OS X users - standalone app
The standalone app is the simplest option, but only works on OS X.

If you are on a Mac running Sierra or later, **the version linked from the form on the ixi lang website will not work.** [Use this link to download ixi as a .dmg instead](http://www.ixi-audio.net/ixilang/thanks.html). **This appears to work for most people.**

After you run the .dmg, make sure you drag the files inside somewhere on to your system, rather than trying to run them straight from the popup window - another user has told me this worked for them.

**That said, none of this worked for me.** I was only able to install the ixi standalone app on my Mac by copying and pasting the files from an old machine I'd installed it on back in 2016. I don't know why this is! I've spoken to Thor about this and he's looking into it, but in the meantime, try the above, and if none of it works, drop me an email and I will send you my own working build to try out. 

I can't figure out where the problem lies despite running both my older build and the current live .dmg through a diff checker, so until Thor has worked it out, I'm happy to supply an older build individually for anyone who gets really stuck, though I can't promise it'll work for you.

---

### For OS X users - Supercollider classes
If you can't get the standalone app working, *or* you want to use ixi inside Supercollider, you need to install it as a Supercollider extension. If you don't already have Supercollider, [you can get it here](https://supercollider.github.io/download). Download the current version.

Again, we have an out-of-date link complicating things! **The link on the ixi lang website to the Qt GUI Supercollider classes is incorrect, and if you are running a version of Supercollider later than 3.6.5, it will not work.** [Instead, download the Qt classes from here and follow the instructions on the Github readme to install](https://github.com/thormagnusson/ixiLangQt). 

To run it, open Supercollider, start the server, then run the command XiiLang(). The black ixi lang window should open.

The default example project in Application Support > Supercollider > ixilang is correctly structured, but is blank in the Supercollider version. If you want example files, [this subfolder](https://github.com/emmawinston/ixilang-experiments/tree/master/projectfiles) on my Github contains an example project structure.

---

### For Windows users - Supercollider classes
*These instructions are incredibly vague, sorry - I do not have a Windows machine to test on and am piecing this together from what I've read myself.*

If you are running Windows, as far as I know there is no standalone app. Your only option is to [install Supercollider](https://supercollider.github.io/download) if you don't already have it, and then install ixi as classes for Supercollider. I can't verify this myself, but the good people of Twitter seem to reckon [this version](https://github.com/mortuosplango/ixiLangQt) works. 

Advice given [here](https://twitter.com/EggyHerman/status/858524890827304960) suggests you need to boot the server in Supercollider, then run XiiLangGUI() to start ixi. 

I believe, from the above link (though again can't verify) that this version does not come with an example project. [This subfolder](https://github.com/emmawinston/ixilang-experiments/tree/master/projectfiles) on my Github contains an example project structure. Create a folder in the user support directory with the title of your project, and place the example files inside.