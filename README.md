## The Command Line

The command line is a terminal giving you direct access to your operating system. You can enter simple commands to perform a variety of functions.

Many of the tasks we need to carry out (such as committing our code) are best performed in the command line.

Here are a couple of resources to help you learn:

- [http://cli.learncodethehardway.org/book/](http://cli.learncodethehardway.org/book/)
- [http://praxis.scholarslab.org/scratchpad/bash/](http://praxis.scholarslab.org/scratchpad/bash/)

## In-Class Demonstration
1. Create a new directory
2. Create a new file and add some text to it
3. Create a directory with a file inside of your current directory
4. Practice navigating back and forth between directories
5. Rename one of your directories

## Introduction to Git
- Git is a source control management tool.
- Git allows you to store and update your code in a structured way.
- Git includes history of changes you make, so you can create &quot;checkpoints&quot; and track your work better over time.
- Git is an intelligent tool, and does many things for you automatically, but can be tricky to use in some cases. It takes a bit of learning to get fully comfortable with Git.

## What is GitHub?
- GitHub is a service that lets you host Git repositories in the cloud.
	- In other words, they are hosted remotely by GitHub, and can be downloaded from / uploaded to over the internet.
- GitHub allows you to easily distribute code to others by sharing your repository.
- GitHub lets you view your code online easily with a web interface.
- GitHub is free to use as long as you make your code public.
Private repositories cost a monthly fee.

## Git Class Demonstration
- We will practice setting up a new Git repository and pushing it to GitHub.
- Note that empty repositories cannot be added to GitHub.
- Here is a cheatsheet of commands we will be using:

Add files to Git tracking:

```bash
git add -A
```

Commit files to local Git repository:

```bash
git commit -m "Initial commit"
```

Add remote to push to:

```bash
git remote add origin http://yourgithuburl.com
```

Push to remote repository:

```bash
git push -u origin master
```