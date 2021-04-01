---
title: TextEditor
bibliography: /home/dhb/Documents/Sources.bib
csl: /home/dhb/Documents/chicago-fullnote-bibliography.csl
suppress-bibliography: true
---



In truth, the difference between Atom and Zettlr is marginal. They handle citations, links, MD conversion to PDF slightly differently. The strength of the search and the overall look and feel are also in play:

**citation** Zettlr can do the footnotes and produce PDFs with footnotes based on the bibtex or JSON file. Atom, on the other hand, is having trouble with autocomplete-bibtex, but Zotero picker works perfectly well, provided I remember to open Zotero.

**links**: Z reads Obsidian backlinks that do not have folder name directly. Atom has a Wikilinks package, which work perfectly but which, like Atom-notes,  must have links that indicate the note and the directory.

**conversion** Zettlr PDF requires YAML on mac (which changes title if different from designated file name). On Linux, straight forward so far

 Atom runs best through the terminal and for PDF is fairly simple: Include YAML, cd to folder, pandoc -s -o (pdf name) --citeproc (md name).

 **searches** Atom slightly more powerful

**storage** Atom more easily store in GitHub, although to be fair I haven't tried it in awhile.


**ease of writing** Atom has dual editor; Zettlr needs kludges with Quick Look. Atom has autocomplete; Zettlr does not. Atom can show PDFs (with package); Zettlr in Linux can not

**Conclusion** -- Really liked autcomplete-bibtex, but not a deal breaker. Atom has slightly more versatility and the tree structure of files that enable Scrivener-like handling of projects.
