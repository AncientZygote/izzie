# izzie
Tutorials, theory development, etc. related to the Isabelle Proof Assistant

We wrote a tutorial for new users of the Isabelle Proof Assistant. It features many screen shots and detailed hand-holding as we walk through a simple proof that the square root of a prime number cannot be a rational number. This is a LaTeX typeset pdf document  (download it and read it on your computer or other device; GitHub no longer displays pdf documents in the browser)  with hyperlink cross-referencing, index and cites to many useful papers providing additional information: [Isabelle Tutorial](https://github.com/AncientZygote/izzie/blob/master/IsabelleTutorial.pdf) 

Subsequently, we inserted document text in the Isabelle theory file discussed in the tutorial above. That theory file can be downloaded at 
[SqrtTutor1.thy](https://github.com/AncientZygote/izzie/blob/main/SqrtTutor1.thy). This theory file now constitutes a tutorial in how to print LaTex typset text from an Isabelle theory file using the Isabelle document printing batch tools. The pdf LaTeX print of that theory is at [How To Print Theory](https://github.com/AncientZygote/izzie/blob/main/HowToPrintThyIsab.pdf). We did not include a ROOT file because we want the user to follow the print tutorial and use the Isabelle tool mkroot to create that ROOT file and then edit it as described in the tutorial. We did include final versions of the root.bib bibiliography file (BibTeX) [root.bib file](https://github.com/AncientZygote/izzie/blob/main/root.bib) and root.tex [root.tex file](https://github.com/AncientZygote/izzie/blob/main/root.tex), although the latter is also created in a default version by Isabelle mkroot and it would be instructive to begin with that default and edit it as instructed by the tutorial. The theory file itself, at the link already given above, [SqrtTutor1.thy](https://github.com/AncientZygote/izzie/blob/main/SqrtTutor1.thy), should be opened in a text editor and viewed to see the actual syntax of the Isabelle document commands and some of the theory lines that are hidden in the pdf printed.
