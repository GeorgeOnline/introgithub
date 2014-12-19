# Getting Started With a GitHub Repository

* by Konrad M. Lawson
* [Originally published on March 15, 2013 at *ProfHacker*](http://chronicle.com/blogs/profhacker/?p=47393)

If we look across the landscape of collaborative writing on the web, there are a few clearly discernible hubs of activity. Wikipedia and Google Docs might be identified as two of them, but one the most remarkable and unique is [GitHub][3]. This is the first of a new series of postings on GitHub, its limits, and some emerging alternatives for scholarship. GitHub is the leading hosting service for code that runs the powerful distributed version control software [git][4] (see Julie's [introduction][5] for more on version control). While many outside the world of programming may never have heard of it, I think it is important to recognize it as a site of online writing and creativity as important as any other of our time. The phenomenal rise of GitHub in the world of coding has been described in the Wired feature, ["Lord of the Files"][6] and the authors even wrote the article itself in a GitHub [repository][7]. It is my conviction that some of the most important innovations that stand behind its rise will come to have a profound impact on writing and sharing in the humanities as well.

Perhaps the most important feature of GitHub that has made it such an attractive home to open source and, increasingly, text documents, is the way in which it enables a form of "collaboration without collaboration." On this platform of millions of repositories of (mostly) text it is incredibly easy to not just download other people's work, but "fork" it, modify it, and either propose that your modifications be "pulled" back into the original or else continue to live independently. This all happens while maintaining a full history of who changed what line of information and preserving a connection is preserved back to the original project it may have originated from. On platforms like GitHub (it is neither the first nor alone, but has a strong lead today), complete strangers can communicate through "commit messages," that describe the changes they made without forming teams or joining a project (though teams and projects might develop out of these initial contacts). In this way, authors don't operate on a single canonical document (as in Wikipedia or, most often Google Docs / Etherpad documents) but keep their own copy that can either merge or diverge from the founding text. They also operate in a world where contributions, in the form of commits, are all recorded, allowing a rich ecology of attributions that is already a powerful currency of legitimation in the programmer community.

## ProfHacker on GitHub

GitHub has already made several appearances here at ProfHacker. Brian introduced the idea of posting and [forking syllabi][8], and Lincoln [wrote about][9] how one actually goes about forking a syllabus you might find on GitHub as well as some tips on good basic practices. Mark put his syllabus for a course on Video Game Studies on GitHub but then [asked some][10] really important questions about the value and best practices of creating repositories out of our syllabi.

In this posting I want to simply introduce how one might get started with their own GitHub repository for any kind of text, whether it is a syllabus for a course, an article you wish to open to collaborative authorship, or any other text you want to expose to the powerful versioning features of git - all without using the command line. As we have mentioned in some of our earlier postings on GitHub, the best way to compose documents that you want to share on GitHub is in plain text, perhaps with Markdown or some other formatting so you can easily export later to other outputs such as PDF, HTML, and so on. Images, and other binary files can also be included in Github, but they are best limited to supplementary files.

## Getting Started

### 1. Create a GitHub account

If you don't already have an account, you will be able to create one easily just by going to the GitHub homepage [here][11]. GitHub accounts are free, and remain so as long as you allow your repositories be open source and available to the world. You only have to get a paid account if you wish to have private repositories protected from prying eyes.

### 2. Download the GitHub client

GitHub has client software that allows you to interact with your account and perform the most common tasks. It won't be enough for the more powerful advanced features that a version control system like git allows, but serves nicely for most things. Lincoln and Mark and have introduced the [Mac][12] ([Download][13]) and the [Windows][14] ([Download][15]) client here at ProfHacker last year. Download the client and install it on your computer. In the examples below I'll use the Mac version, but most steps should be almost the same for Windows.

### 3. Create a repository within the client

The first time you run the client on your computer, you will be asked to provide your name, email address, and sign in to your GitHub account. After you do this, you can begin to use the client as a way to manage your local repositories, download repositories you may have forked, and push changes that you make to the GitHub servers.

[![New Repository][16]][16]

To add a new repository choose "Create New Repository" from the "+" menu at the bottom of the screen (in the Mac client. The Windows client may be a little different). Choose a name and a location on your computer to keep your repository files. Think of your repository as a single writing project, whether it be a simple syllabi to more complex articles, dissertations, and so on.

### 4. Publish the repository to your account

When you added a new repository, all you get is what looks like a blank folder on your hard drive. If fact, there is also a hidden directory inside your new repository called ".git" which stores everything about your files and their history.

Add a plain text file in your new repository folder using whatever text editing application you like working with best. When you return to the GitHub application, you will see (on a Mac at least) that the second icon "Changes" will have changed slightly to indicate that your repository has new changes.

[![Commit Changes][17]][17]

Here it is important to understand that getting your changes to GitHub is a two step process. First you "commit" your changes, which will record a "commit message" giving you an opportunity to describe what kind of changes or additions you have made. Enter your commit comment, and an optional elaboration and note that the new plain text file you put in the folder is selected by default. Press "Commit."

Now the final step of pushing your commit to the server can happen. Since you have just created a brand new repository, the "Sync Branch" button at the top right should say instead, "Publish Branch." Click on this button and you are done. If you open your GitHub account online you should see your repository and the file that you added.

## Next

_This series on GitHub will continue next week with a post on direct editing and zen writing mode, on forking and pull requests, a discussion of some good online sources for learning more, a post on the limitations of GitHub from the perspective of writers outside the world of code, and then an introduction to [Authorea][18], the first git-based platform that really tries to meet some of these challenges, especially for the world of collaborative publishing for scientists._

_Image "Skitchtocat" in the [Octodex collection][19] by GitHub under terms [here][20]._


   [1]: http://chronicle.com/blogs/profhacker/files/2013/03/skitchtocat-300x300.png
   [2]: http://chronicle.com/blogs/profhacker/files/2013/03/skitchtocat.png
   [3]: http://github.com (GitHub)
   [4]: http://git-scm.com/ (Git Home)
   [5]: http://chronicle.com/blogs/profhacker/a-gentle-introduction-to-version-control/23064 (Gentle Intro to Version Control)
   [6]: http://www.wired.com/wiredenterprise/2012/02/github/ (Lord of the Files)
   [7]: https://github.com/WiredEnterprise/Lord-of-the-Files (Lord of the Files GitHub Repository)
   [8]: http://chronicle.com/blogs/profhacker/forking-your-syllabus/39137 (Forking Your Syllabus)
   [9]: http://chronicle.com/blogs/profhacker/how-to-fork-a-syllabus-on-github/39447 (How to Fork a Syllabus on GitHub)
   [10]: http://chronicle.com/blogs/profhacker/git-a-fork-in-my-syllabus-its-done/40331 (Git a Fork in My Syllabus, It’s Done)
   [11]: http://github.com (GitHub)
   [12]: http://chronicle.com/blogs/profhacker/github-for-mac/37502 (GitHub for Mac)
   [13]: http://mac.github.com/
   [14]: http://chronicle.com/blogs/profhacker/introducing-github-for-windows/40271 (GitHub for Windows)
   [15]: http://windows.github.com/
   [16]: http://chronicle.com/blogs/profhacker/files/2013/03/Screen-Shot-2013-03-12-at-6.01.14-PM.png
   [17]: http://chronicle.com/blogs/profhacker/files/2013/03/Screen-Shot-2013-03-12-at-6.04.02-PM.png
   [18]: http://authorea.com/
   [19]: http://octodex.github.com/
   [20]: http://octodex.github.com/faq.html
