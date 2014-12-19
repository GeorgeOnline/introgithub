# The Limitations of GitHub for Writers

* Written by Konrad M. Lawson
* [Originally published on April 16, 2013 at *ProfHacker*](http://chronicle.com/blogs/profhacker/the-limitations-of-github-for-writers/48299)

This posting is the last in a series introducing the text hosting and version control service [GitHub][2]. Up until this point I have talked about some of the great features of working with repositories of text in GitHub and the ways in which it facilitates collaboration even without direct collaboration. It is, in its own motto, a "social coding" environment that allows anyone to "fork" code, issue "pull requests" to propose improvements on someone else's work, as well as keep a history of changes and improvements on work over time. I have argued that these innovations have much to teach us in our own worlds of scholarship.

   [2]: http://github.com/
   [3]: http://chronicle.com/blogs/profhacker/getting-started-with-a-github-repository/47393
   [4]: http://chronicle.com/blogs/profhacker/direct-editing-and-zen-mode-in-github/47497
   [5]: http://chronicle.com/blogs/profhacker/forks-and-pull-requests-in-github/47753
   [6]: http://chronicle.com/blogs/profhacker/file-and-repository-history-in-github/48047
   [7]: http://chronicle.com/blogs/profhacker/resources-for-…git-and-github/48285

GitHub, in its current form, can serve the needs of writers and scholars, just as it currently serves programmers, and more recently, groups adding laws and government regulations as repositories on the site. For many reasons, however, both GitHub, and the broader approach to collaboration that it has promoted in the world of coding, is not _ideal_ for writers and there are good reasons to support the development of alternative services more suited to our academic or other writing needs.

There are three rough categories of issues:

  * Specific technical obstacles to adopting GitHub and git in the workflow of writing and scholarship
  * Some ways that alternative services might overcome these obstacles while maintaining some of the benefits of the GitHub environment
  * The larger disciplinary obstacles that any scholar is likely to face if they fully embrace some of the core approaches of the open source world such as the one we see on GitHub

In this posting I'll touch on the first two items above. Some of my upcoming postings will introduce some alternatives to GitHub that have emerged in just the last few months that address some of the problems I outline below. The last issue, on disciplinary obstacles, will be the main focus of my next posting.

## Some Limitations

Perhaps the biggest obstacle I have found in promoting GitHub to my friends and fellow historians is quite simply the effort required to master its basic concepts, commands, and workflows. I have tried to present some of the basic ideas in this series, but the truth is that it is hard to convince anyone to adopt GitHub and git into their daily workflow when its benefits are not immediately obvious, it is not an expected skill in our academic communities (the way that version control systems have become in the world of programming), and the tools and terms are mostly foreign to us. This is compounded by the fact that there are not any thorough tutorials or guides that are specifically designed to teach git or GitHub to writers who intend to use it for the powerful collaborative features it offers, as opposed to simply as a version control system. In addressing this challenge, any alternative to GitHub designed with writers in mind needs to think about how to retain some of the power of GitHub, especially the powerful community interactions between repositories that forking/pull requests allow, while reducing the complexity and high bar to entry.

## A Plain Text World

Another challenge comes from the fact that GitHub and git work best when operating on plain text. Many of us are used to composing our scholarship in Word, Google Docs, etc. and save our documents in something other than simple text. As many ProfHacker readers know, we have been pushing the beauty and power of plain text (Lincoln's post on [text editors][8] is just one of many examples), and composing plain text documents in a simple mark up language such as Markdown (see, for example, Jason's [recent review][9] of a new book on the topic). If you have made the switch to plain text and Markdown, using GitHub with your documents is a breeze. This is not the case for many scholars, however, and an alternative to GitHub for writers might want to provide robust import and export features to make moving documents into and out of a text repository in a variety of formats as easy as with a converter like Pandoc (Read [Lincoln's introduction][10] to the tool).

   [8]: http://chronicle.com/blogs/profhacker/writing-power-tools-text-editors/38940
   [9]: http://chronicle.com/blogs/profhacker/markdown/47813
   [10]: http://chronicle.com/blogs/profhacker/pandoc-converts-all-your-text-documents/38700

## Text as Dominant

A related but more difficult challenge is the way in which text is the dominant form in GitHub. While other files such as images, sounds, etc. can be included in a repository, it is much harder to incorporate the versioning features, and the incremental improvement features that make GitHub so powerful when you are dealing with other kinds of content. It is easy to show the exact difference between two similar text files using a "diff" but the "diff" between a jpg image containing a dog and one containing a dog with a moustache drawn on it is just a bunch of binary gobbledygook. This can have an impact on the quality of experience when the "social" aspect of sharing or collaborating on works include these other kinds of material. This is unfortunate given the fact that we are entering a period when the century or more old formats that constitute our academic scholarship are starting to become more open to the incorporation of things like images, sound, interactive and dynamic datasets, and so on. An alternative to GitHub for writers needs to think about how these other formatted files will be treated in the broader versioned and collaborative environment.

## Units

Another challenge that is true for GitHub but need not affect alternatives to GitHub comes from its units of measurement. To work effectively with text repositories in GitHub things go smoothest when you keep everything nice and short - lots of small short text files, rather than a single long text for, say, a book or an article. This minimizes the chances of merge conflicts, and makes it easy to extract pieces, among other things. If you are used to composing works in sections, especially if you use an application like Scrivener (see [Ryan's review here][11] to do your writing, this comes naturally, but less so for others. Either way, the file list and browse interface of GitHub generally feels more appropriate for code than for our scholarship. If the file units are not an ideal fit, neither is the default way that diffs are done: on a line by line basis. Lines of code are very often semantically intact units in programming languages and perhaps for poetry, but we are much more used to seeing the kind of word and letter level of changes in Wikipedia, Microsoft Word "track changes" and Google Docs. Seeing which "lines" have been changed, even when changed words are darker, the way it is in the GitHub web interface, is not ideal for looking over changes. At the very least, sentences within unbroken lines would be an improvement.

   [11]: http://chronicle.com/blogs/profhacker/scrivener-scrivening-scriverastic/23026

## Are We Fixing Bugs and Adding Features?

All of the guides to git and GitHub talk about the tasks of a programmer in terms of fixing bugs or adding new features. Git and GitHub serves these tasks well, with the world of branches and sporadic commits generally fitting well with the workflow of a programmer. Of course, as writers we also "fix bugs" when we edit our work, and "add features" when we create new content. But these metaphors are somewhat forced. Writing with a git repository and treating a commit like choosing "Save" from the File menu doesn't quite feel right to me. I am already saving my text document as I go along, and I need to take the extra step to decide not only what unit of added text corresponds to an appropriate commit, but I need to compose a commit message to describe what I have done. Maybe this will make me a better writer, as it forces me to reflect on what I have done in brief breaks between flashes of genius. Or maybe it just distracts me from getting more writing done? Either way, alternatives to GitHub may wish to rethink the process or simplify it. Scrivener and lots of other applications support "snapshots" of your writing, and as we shall see, some of the new alternatives to GitHub for writers use something similar but don't force you to write commit messages.

## Best Fit?

**Are GitHub Forks and Pull Requests the Best Fit for our Use Cases?**

One of the things I like the most about GitHub, if I haven't said this enough, is the powerful way in which repositories are connected to each other through forks, and the way in which potential strangers can easily cooperate with each other through pull requests. However, does the way that GitHub handle this fit the most likely or interesting use cases for writing and scholarship? Think back to the way in which texts were often mixed and recomposed in centuries past. Set aside the lack of attribution and blatant plagiarism that occurred in those days, which is a problem that GitHub helps address by including powerful attribution features in the form of repository history and fork relationships. Were authors of earlier ages more likely to take a text they liked and simply tweak and add to it before republishing or extract pieces from multiple texts, and add a sprinkling of their own commentary? I think the latter was more common, as it is among plagiarists today (Of course, programmers also do this all the time as they incorporate tiny snippets of code from all manner of sources into their work).

If a service like GitHub offers a wonderful way to transform a taboo practice of plagiarism into a virtuous cycle of mutual attribution and both active and passive collaboration, then I think writers would want it to better account for cases in which repositories have not one, but several parents. That is, they are forked from multiple places. It is true that the line by line "blame" feature found in GitHub now identifies the author of any individual line of a text in GitHub at the micro level, but the way in which a repository is seen as a child of another repository at a more macro level may benefit from a rethinking which accommodates more rich models of ancestry. Another alternative is to embrace more fully the micro level of line by line or paragraph by paragraph attribution found in a repository history but offer far better ways to browse and analyze this information. Similarly, these features which reward authors through attribution might also benefit by thinking about ways to potentially differentiate the significance of contributions beyond aggregate lines added and deleted? We do this in some ways today through an economy of citations, but in a scholarly world driven by GitHub-style collaborative authorship, other models might arise.

If GitHub falls short for writers, it is by no means impossible to use it in its current form. Fortunately, however, in just the past few months there have been some great moves towards creating tools that borrow heavily from the versioning and collaborative features GitHub but which are targeting writers. I recently interviewed the founders of the promising [Authorea][12] and will also introduce [Draftin][13] and [Editorially][14]. In my next posting, however, I want to look at some of the disciplinary obstacles to these alternative approaches to collaborative authorship.

   [12]: http://authorea.com
   [13]: http://draftin.com/
   [14]: http://editorially.com/
