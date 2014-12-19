# Direct Editing and Zen Mode in GitHub

* written by Konrad M. Lawson
* [Originally published on March 21, 2013 at *ProfHacker*](http://chronicle.com/blogs/profhacker/direct-editing-and-zen-mode-in-github/47497)

At the end of the last posting our new repository had only a single file saved in the repository's folder. Using the GitHub client software, we published the repository to our free online GitHub account. In this posting I'll describe the most basic workflow of modifying or adding files in your new repository and look at an easy way you can, if you like, work with your repository directly on your GitHub account.

   [2]: http://chronicle.com/blogs/profhacker/getting-started-with-a-github-repository
   [3]: http://github.com/

## Basic GitHub Workflow

If you open the repository text file we created in your favorite text editor, make a few changes, save them, then return to the GitHub client, you will notice that any modifications will be revealed in the changes tab. When you are ready, you can "commit" these changes, and then "synch" them with your GitHub account. For example, let us say you are putting a [syllabus on GitHub][4]. After adding a new section describing your grading policy, you save, go back to the GitHub client, write "added grading policy" in the commit message box, press "Commit" and then "Sync Branch" and you are done. Your changes will be reflected online in GitHub. If you are following Lincoln's [suggestion][5] to break your document into smaller pieces, you might have decided to add this section as a separate file. When you create a new text file and save it in the repository directory, the GitHub client automatically detects the newly added file, and lets you commit it along with any other modifications it finds.

   [4]: http://chronicle.com/blogs/profhacker/forking-your-syllabus/39137
   [5]: http://chronicle.com/blogs/profhacker/how-to-fork-a-syllabus-on-github/39447

As long as you are just working with your own files, this is all there really is to working with GitHub the vast majority of the time. You make changes to your files, you add new files, you commit small groups of changes when you are ready, and sync them with your GitHub account. Now, experienced users of git version control may read in horror as I write these postings without proceeding, in an orderly fashion, through the fundamental terms that git and other version control systems use. The GitHub client software conceals a lot of the power and complexity of the git version control system and even replaces things like push, pull, and fetch with the generic "sync," but I believe there are good reasons to begin with these most common simple tasks and build from there, rather than immediately expose the inner workings of the git machine, as it were.

## Direct Editing and Zen Writing Mode

With the GitHub client and a text editor on your machine, you can work offline, and when you are ready, commit changes, and sync to the GitHub account when you have an internet connection. If you are working on the same repository on two machines, say a home and an office computer, things can be kept simplest if you commit and sync before you head into the office, then when you get to the office, sync in the GitHub client before beginning to work with your files. Of course, you don't have to do this and can work without syncing back to GitHub but at some point you will have to teach yourself the powerful git ways to handle potential "merge conflicts" that can result from editing the same file in two places when you finally do sync changes.

You don't have to have work with the files offline at all, however. If you have a repository of files in your GitHub account that you have created or forked from someone else, it is very easy to simply browse your account to the appropriate file and click the "edit" button. When you are done making changes to a file, add a commit message at the bottom as you would in the GitHub client software on your own machine and press "save." GitHub seamlessly handles these changes as if you had modified a local file, saved the changes, commited and synced them.

[![Direct Edit and Zen Mode][6]][6]GitHub has recently taken the ease of online editing one step further by offering a clean "Zen Mode." When you click the edit button for any file, there is a small full screen mode labeled "Zen mode." When clicked, all of the GitHub distractions disappear and you presented with beautifully clean browser based editing environment.


   [6]: http://chronicle.com/blogs/profhacker/files/2013/03/Screen-Shot-2013-03-15-at-0.25.52.png


Remember, if you change files in your repository directly online, it will now be "ahead" of your offline copy, so remember to sync in your GitHub client before continuing with any changes to the files on your own computer if you want to avoid "merge conflicts" that require a few more skills to deal with.

_The next posting in this series on GitHub will look more closely at two of the more "social" aspects of working with text on GitHub: forking (already mentioned in several ProfHacker postings) and pull requests. The first allows you to create a copy of someone else's work, while maintaining, at least in GitHub, a connection back to the original. When you make changes to a fork, you can choose to propose that the original author re-incorporate your changes into their original through a "pull request."_


   [7]: http://www.flickr.com/photos/65305532@N06/8526197809/sizes/o/in/photostream/
   [8]: http://www.flickr.com/photos/65305532@N06/
