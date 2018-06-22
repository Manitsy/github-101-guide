# Git 101 Guide For Projects
#Pluralsight/projects

[Projects](https://www.pluralsight.com/product/projects) are a new hands-on way to learn on Pluralsight. They follow real-world practices and workflows which may new if you’ve never worked in the technologies before.

The flow of every project follows the same structure:

1. Learn what you’ll build in this project.
2. Setup and install all dependencies on your local computer.
3. Download the code for this project (by cloning it from GitHub).
4. Get this project working on your local computer.
5. Complete some number of code tasks.
6. Upload your code (by pushing it to GitHub).
7. Pluralsight Checks your work and verifies everything is correct!

One of the common themes for all Pluralsight Projects is the use of Git and GitHub, which is a requirement for all projects. This guide walks you through everything you need to know to use Git and GitHub in order to complete a Pluralsight Project.

## What are Git and GitHub?
Before going too far, let’s explain what these are! Git a version control system, similar to Subversion, CVS, Team Foundation Version Control, Mercurial, Harvest and other VCS’s (version control systems).

If you’ve never used a version control system before directly, I bet you’ve used them indirectly. Time Machine for Mac and Google Docs version history are two widely used applications of version control. In both cases, and with Git, you have a current version and the ability to go back in time and see previous versions. That’s the power of Git - being able to save multiple copies of a file and track history over time.

### Where Does GitHub Come In?
Having a bunch of past versions of code on your local computer will only get you so far. Eventually you’ll want to collaborate with other people - maybe building on someone else code, collaborating with another developer or even just getting feedback in a code review.

GitHub is a platform that allows you to upload your code and allow others (if granted permission) the ability to contribute changes back to it.

The end result of this is that you can have multiple people working out of the same codebase without them constantly deleting each others work. Version control systems are a tremendously powerful tool!

## Installing And Configuring Git
In order to work with Git, you’ll need to install it locally. You can grab the latest version from the official site for Git, [git-scm.com](https://git-scm.com/), and install it locally.

Once you git installed locally, you should be able to run the `git` command from your terminal (Mac) or command line (windows).

You’ll want to set two configuration settings right away - your name and your email. Every time you make a code change, that change will be stamped with this user information, so make sure you’re setting this correctly.

```bash
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

Now whenever you make a commit to git, it’ll be associated with your name and email!

## Authenticating with GitHub
For Pluralsight Projects to work, we need to connect your Pluralsight account to your GitHub account  - where your code will be for this project. The first step to doing this is to authenticate with GitHub.

Pluralsight isn’t granted any private permissions as part of this. We can’t see your private repositories or those of the companies you work for. We can’t make changes to your code.

What this permission does is allow us to know that you are you, and give you credit for working on the Project within Pluralsight.

## Forking a Repository on GitHub
In order to start working on a Project, you’ll need a starting point – that’s where forking comes in. “Forking a repository” means making a copy of this repository into your own account on GitHub. You can think of a “repository” as a folder of code annotated with all the version history with it.

To fork a repository, sign into GitHub and visit the original webpage for the repository.  For example, if the Project asked you to fork a repository at the URL [GitHub - adamfortuna/HelloPluralsightProject: Demonstration on how projects work at Pluralsight.](https://github.com/adamfortuna/HelloPluralsightProject), then you would open that up in your browser and click the “Fork” button.

[img]

If you are a member of any organizations (companies) on GitHub, you may be prompted with a question on where to fork this repository to. All Pluralsight Projects assume you’re working out of your personal account, so make sure to choose to fork to that location.

[img]

After a few seconds, the fork of this repository should show up in your account!

## Cloning a Repository from GitHub

Once you have your fork
