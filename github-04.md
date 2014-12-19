# File and Repository History in GitHub

* by Konrad M. Lawson
* [Originally published on April 1, 2013 at ProfHacker](http://www.wired.com/wiredenterprise/2012/02/github/)

As we have seen, GitHub has a "social" element that ties a community of shared and replicated groups of text together through the process of a "fork." Collaborators working together on a project can "push" and "pull" changes to a single repository, but GitHub also makes it trivial for complete strangers to find, fork, and then issue a "pull request" on, for example, a syllabus, an article, or other set of documents.

Unlike a wiki, where a single central "canonical" text usually dominates, GitHub is completely decentralized by design. Multiple versions of a repository coexist, and usually contain the complete history of every change and author who participated in its authorship, at least up to the moment of the fork. If a fork becomes more popular or attracts more substantial improvements over time, an original author's work can remain untouched in their original repository, even as every line they authored remains correctly attributed in forks that build upon their work.

**If the quantifiable currency of academia is measured in citations, then that of an author in the collaborative world of GitHub exists at two distinct levels.**

  * At the first level, it is measured in the quality, number, and longevity of one's "commits," that is, the words and lines created, modified, and deleted in a repository - whether that repository is your own project or someone else's.

  * At the second level, it is to be measured in the success of the project itself, narrowly quantifiable in terms of stars and forks, but far more importantly, in its use. The number of forks gives you an indication of how often a work has been planted, like a seed, as the foundation of someone else's further development, while the cloning and download of a work represents the pool of potential users.

As such, both are poor metrics by themselves. However, **if elements of this model are adopted in our academic scholarship going forward, it can and should supplement, rather than replace, other practices of review, citation, and quotation.** It could achieve this while unlocking some of the truly transformative potential of collaborative work that we see taking place in the world of software development.

## History and Blame

Let's take a closer look at how changes and attribution are tracked in GitHub (and therefore the git version control system that is its core). As I will discuss in an upcoming post, GitHub is not always the best environment for writers of text outside the world of programming and this will probably become apparent to readers as we go. Let's use the _Wired_ article ["Lord of the Flies"][8] and especially its [GitHub Repository][9] as and example. The authors used GitHub as the platform for the writing of their article as an experiment and it was one my inspirations for thinking more about the potential for GitHub's approach in research and writing.

   [8]: http://www.wired.com/wiredenterprise/2012/02/github/
   [9]: https://github.com/WiredEnterprise/Lord-of-the-Files

Let's open up the Lord of the Flies [repository][10]. Above the main list of text files in the repository, which includes the _Wired_ article and a number of translations created by readers, are three buttons (Figure 1).

   [10]: https://github.com/WiredEnterprise/Lord-of-the-Files

![Figure 1: A screenshot of the 3 buttons above the main list of text files in a GitHub repository. The three buttons are 'Files,' 'Commits,' and 'Branches.'][11] 
**Figure 1: A screenshot of the 3 buttons above the main list of text files in a GitHub repository. The three buttons are 'Files,' 'Commits,' and 'Branches.'**.

   [11]: http://chronicle.com/blogs/profhacker/files/2013/04/Screen-Shot-2013-03-29-at-18.19.07.png

Pressing the second of these -- "Commits" -- gives you an overall history of the entire repository. (This is similar to the "View History" button one sees on any Wikipedia article.) Keep in mind, however, that any commit can contain multiple changes. For example, perhaps someone changed a single sentence of the English article, but then proceeded to also make the same change in the German and French translations of the article before committing their changes. In the "Commits" overview, all of these changes might have been submitted at once. Each commit will indicate who made it and a short message summarizing the changes. We can also see pull requests at work here. Notice that typos are being fixed or translations being added and then pull requests including changes are being "merged" into the "master" document (Figure 2).

![A screenshot from the GitHub interface showing the history of changes to a given document: typos fixed, translations added, and pull requests -- including changes -- 'merged' into the 'master' document][12]
**Figure 2: A screenshot from the GitHub interface showing the history of changes to a given document: typos fixed, translations added, and pull requests -- including changes -- 'merged' into the 'master' document.**

   [12]: http://chronicle.com/blogs/profhacker/files/2013/04/Screen-Shot-2013-03-29-at-18.23.11.png

Over to the right on the Commits history page you will see that each commit has its own ID number. Below it, the "Browse code" link allows you to step back in time to see what the entire repository looked like after that commit happens. If, on the other hand you click on the Commit ID itself, you will be presented with a "diff" of every file that was changed - a representation of all changes between the commit and its parent, that is, a comparison with the version of the repository that came before it. Contributors to wikipedia will recognize this though in some ways wikipedia offers a better interface. A diff will indicate in green all lines that have been added, and red all lines that have been deleted. It will also show you a total number of changes at the top that gives you an immediate indication of how much was changed. Often you will see two seemingly identical lines in both colors which happens when only part of a line has been changed or moved slightly. Sometimes, a dark green color will indicate individual words that were changed but this reveals one of the weaknesses of GitHub as a resource for writers: the web interface for GitHub does not come close to, say, Microsoft Word track changes, in clearly revealing small edits to text (If you use git on the command line, you can use something called "wdiff" or an option called "--color-words").

Instead of looking at the history of all Commits for a repository you can also go to any individual file in the repository, say, the [English text][13] of the Lord of the Flies article, and click the "History" button. This will show only the list of commits which modified that particular file.

   [13]: https://github.com/WiredEnterprise/Lord-of-the-Files/blob/master/Lord-of-the-Files.en.txt

The Commits for a repository or a file gives you the deep history, but is less useful when you just want to know who is responsible for a part of a given text _as it currently stands_ in the version of the repository you are looking at. For this, go to any file and click on "blame" instead of "history." If we open "blame" for the [Japanese translation][14] of the article, for example, you can see that the original translation was submitted by the user omo, with oshow, mumurik, hisashim, syoichi, and kuenishi correcting typos. Clicking on any of the commit ideas next to the text attributed to them will show a diff that allows you to tell whether they were making small changes or adding significant amounts of new content.

   [14]: https://github.com/WiredEnterprise/Lord-of-the-Files/blame/master/Lord-of-the-Files.ja.md

## Network and Graphs

The "Commits" for the entire repository, the "history" of an individual file, and the "blame" feature are the heart of a repository archive of all its past changes. GitHub also offers some really wonderful "big picture" looks at the repository. The ["Network"][15] option, for example, gives you a beautiful visual representation of the git "tree" of the project. Each branch and fork of the code is depicted, with each commit indicated by a small dot and moments where branches "merge" with arrows. Read [this blog post][16] for more on how it works.

   [15]: https://github.com/WiredEnterprise/Lord-of-the-Files/network
   [16]: https://github.com/blog/39-say-hello-to-the-network-graph-visualizer

The [graphs][17] feature is also interesting, though some might be uncomfortable with the degree of transparency it offers. The [contributors][18] graph shows you the number of commits by each project contributor over time, the [code frequency][19] gives you a cleaner overview of how many lines are being added as opposed to deleted over time, and the [punch-card][20] gives you a sense of the "working schedule" of the project in terms of what days and times of day commits tend to be made.

   [17]: https://github.com/WiredEnterprise/Lord-of-the-Files/graphs
   [18]: https://github.com/WiredEnterprise/Lord-of-the-Files/graphs/contributors
   [19]: https://github.com/WiredEnterprise/Lord-of-the-Files/graphs/code-frequency
   [20]: https://github.com/WiredEnterprise/Lord-of-the-Files/graphs/punch-card

With the complete access to the history of every document in the form of the Commits overview, the blame feature, and the network and graphs, GitHub exposes an unprecedented amount of information about the creative process to the world. Not only is code made available to the world for download, use, and modification, but the contributions of every coder can be traced through the git repository.

My emphasis so far has been on the collaborative potentials of a platform like GitHub but this post should have made clear how much is revealed when we work completely in public through git. A culture of almost extreme transparency has rapidly become mainstream in the world of open source programming, as evidenced by the extremely rapid rise of GitHub.

**If we set aside the technical obstacles to a GitHub like system for scholarly authorship as well as the solitary ways that some of our fields are known for, could this level of transparency ever take hold in our own academic work? What do you think? Can scholars overcome the "do not cite or circulate" secrecy that we often protect our drafts with and be convinced to expose the evolving ideas and prose in line with the "release early and release often" philosophy of the software world?**

   [21]: http://octodex.github.com/inspectocat/
   [22]: http://octodex.github.com/faq.html
