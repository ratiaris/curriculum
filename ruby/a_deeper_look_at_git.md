# A Deeper Look At Git
*Estimated Time: 3-4 hours*

Hopefully you've been using the basic Git commands to create repositories and push your code up to Github.  If not, you've got a bit of catching up to do but don't worry.
 
In any case, Git is a crucial skill to have whether you're a professional web developer or just a hobbyist who needs to back up the code base.  It's the "save" button on steroids for code and it allows giant teams of developers to collaborate.  There really aren't all that many commands for you to learn, either, but sometimes the real difficulty of it comes from visualizing in your head what it's actually doing.

In this lesson, we'll dive deeper than just the `$ git add .` and `$ git commit` and `$ git push` commands you've mostly been using.  Maybe you've had the dubious pleasure of getting a merge conflict when you tried to pull or push changes.  Maybe you're just curious how multiple developers can work on a single code base at the same time.  Either way, this section should help you take the first steps towards expanding your Git toolkit and understanding what's actually going on under the hood with Git.

It's important to take a look at this stuff before getting any deeper into things because the project work is becoming more and more complex so using a disciplined Git workflow is no longer optional.  The axiom used to be "save early and often" and now it's "commit early and often".  Hopefully, after you've finished this lesson you will feel much more comfortable with the basics and like you at least know what to Google if you'd like to do more.

We'll begin by reading some things that are probably review from [Web Development 101](/web-development-101/git-basics) but, if you're like most people, you could benefit from a refresher. We'll then dive deeper into topics that are relevant so you can use git for a more effective workflow, whether you're just working on your own project or trying to bring in collaborators as well.


## Points to Ponder

*Look through these now and then use them to test yourself after doing the assignment*


* How do you amend a commit message that you just messed up?
* How do you view the history of your most recent commits?
* What are two different uses for `$ git checkout`?
* How do you undo a recent commit?
* What are branches?
* How do you create a new branch to work on? 
* How do you push that (non-master) branch up to Github?
* How do you merge the changes from your new branch into the master branch again?
* Why is working with feature branches useful?
* What is the difference between using `$ git merge` and `$ git rebase`? (hint: history)
* What is the difference between a "remote" and your local repo?
* How do you add your Github repo as the remote?

## Assignment

**Note:** *Subversion* (SVN) was the widely used version control system prior to Git (and is still widely used in larger corporations) and that's why many of the readings below will reference it.  Just read the very top two sections of [this chapter from git-scm](http://git-scm.com/book/en/Git-and-Other-Systems-Git-and-Subversion) if you'd like a slightly better explanation.

1. If you haven't had the chance to do so, go through the [Web Development 101 Git Basics section](/web-development-101/git_basics).
2. If you're still feeling a bit shaky, look at [Git Basics](https://www.atlassian.com/git/tutorial/git-basics) from Atlassian.
3. Read the section on [Undoing Changes](https://www.atlassian.com/git/tutorial/undoing-changes) from the same site.
2. Read about [Using Feature Branches](https://www.atlassian.com/git/tutorial/git-branches) and then look at how it fits into a real workflow in [this section](/ruby-programming/using-git-in-the-real-world).
3. Take a look at [Rewriting Git History](https://www.atlassian.com/git/tutorial/rewriting-git-history) to understand how Rebasing works.  There's a lot of debate out there about whether it's best to use a "Merge" or "Rebase" based workflow.  We'll stick with merge because it's a bit more straightforward and the errors can be a bit easy to get over, but you should be aware of rebasing as an alternative type of flow.
4. Read about working with [Remote Repositories](https://www.atlassian.com/git/tutorial/remote-repositories), which should mostly be familiar to you by now.
1. Layer onto your knowledge a bit deeper by reading [Pro Git chapters 2 and 3](http://git-scm.com/book).


## Additional Resources

*This section contains helpful links to other content. It isn't required, so consider it supplemental for if you need to dive deeper into something*


* Watch [Get Going from Pro Git](http://git-scm.com/video/get-going) if you'd like a refresher of things.
