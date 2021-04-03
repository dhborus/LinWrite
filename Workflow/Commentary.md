## Computer Setup Commentary

### Operating System and Machine

Ordinarily, I would stick with Apple equipment. There are two complicating factors. First, the iPad - iMac scheme is not particularly viable since Karen has, for the most part, laid claim to the iMac. In addition, the iPad had some drawbacks. It's not quite a work machine and has developed some glitches particularly interruptions and skips and difficulty charging (at least with one cord).

Second, it seems clear that Apple will be moving away from the Intel architecture. That will force a choice of paying the Apple tax or using a laptop that is old, slow, and has a draining battery or one with a smaller screen (and possibly a draining battery). Laptops do have the advantage of portability, which will open up the iPad to be an entertainment device only.

As it stands, few of my major apps are OS-dependent. Atom, Zettlr, pandoc-latex, Obsidian, Firefox, and Bitwarden are all plain text or available on different platforms. So a switch to Linux is theoretically possible, although I will be faced with the equipment problem mentioned above.  

So until June, the question is whether Linux will suffice. Can I communicate, research, write, and prepare for publication? Can I find replacements for Alfred, Keyboard Maestro, and MS Word? Can I learn the shortcuts? If yes, the test then becomes whether the 13" is usable. Key will be how well the battery lasts (the 15” works worse with Linux than with MacOS) and how the screen looks at that size.

If Linux will not work, the question is whether the 13” or a silicon laptop will be the machine of choice. If I opt for Apple silicon, then sale or donation of old laptops.

I have moved the keys, set up Autokey, and found a way to transfer files from Linux to Mac and to use Working Copy to download clips from Firefox on the iPad. Nitroshare (for Manjaro) and SSH are possible tools as well. I do not, as yet, have a replacement for either Alfred or Keyboard Maestro.

### Distro

The general Linux question is whether I can comfortably do my work and use the computer as I more or less use a Mac. There is, of course, much to learn, and so it appeals to my acquire skills inclinations. But it also will mean that I remove myself from the shiny, just works world of Apple. The development of silicon and Big Sur and beyond means that the mac collection in the house will eventually become obsolete at worst and "laggy" at best. The virtue of Linux is that it will extend the life of my current machines and save me money. This result makes even more sense given that I do not do heavy work (video, photos, music) but surf and research, take notes and write. Yes, there's streaming but not so much as to tax the machine. Linux makes sense for those things, even with a steep learning curve.

As for the distribution, I have solved many of the Manjaro problems -- screen fonts (16X9 rather than X10), email, Dropbox, Autokey usage, update, Zotero picker rather than autocomplete, Mint is solid but it isn't very exciting. Manjaro has great software repositories, although Debian-based distros and easier to learn. I have heard that Manjaro eventually runs into difficulties once updating occurs, so I will keep elementary in reserve since it is terribly solid and is the most Mac-like.

Will need Alfred and Keyboard Maestro replacements (ULauncher comes close).

Working Copy and SSH will allow IOS, MacOS, and Linux exchange.

**Conclusion** Keep Manjaro until it becomes ragged and then replace with elementary os.

### Text Editor

In truth, the difference between Atom and Zettlr is marginal. They handle citations, links, MD conversion to PDF slightly differently. The strength of the search and the overall look and feel are also in play:

**citation** Zettlr can do the footnotes and produce PDFs with footnotes based on the bibtex or JSON file. Atom, on the other hand, is having trouble with autocomplete-bibtex, but Zotero picker works perfectly well, provided I remember to open Zotero.

**links**: Z reads Obsidian backlinks that do not have folder name directly. Atom has a Wikilinks package, which work perfectly but which, like Atom-notes,  must have links that indicate the note and the directory.

**conversion** Zettlr PDF requires YAML on mac (which changes title if different from designated file name). On Linux, straight forward so far

 Atom runs best through the terminal and for PDF is fairly simple: Include YAML, cd to folder, pandoc -s -o (pdf name) --citeproc (md name).

 **searches** Atom slightly more powerful

**storage** Atom more easily store in GitHub, although to be fair I haven't tried it in awhile.


**ease of writing** Atom has dual editor; Zettlr needs kludges with Quick Look. Atom has autocomplete; Zettlr does not. Atom can show PDFs (with package); Zettlr in Linux can not

**Conclusion** -- Really liked autcomplete-bibtex, but not a deal breaker. Atom has slightly more versatility and the tree structure of files that enable Scrivener-like handling of projects.

Ok. Let's see if this will work.
