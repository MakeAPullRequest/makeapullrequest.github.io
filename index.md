---
layout: default
---

Welcome! This is a beginner-friendly page devoted to **walking you through making your very own Pull Request**. We assume you have some clue what a Pull Request is or what it's used for, or else you wouldn't have found this page. Still, let's review a bit.

Pull Requests are a way to submit changes to (code) repositories. Repositories are collectons of files hosted on sites like [GitHub](https://github.com), most often associated with software development. Software developers use repositories and Pull Requests to track changes to code bases over time.

In this tutorial, we'll walk through creating a Pull Request against the followng code repository: [https://github.com/MakeAPullRequest/makeapullrequest.github.io](https://github.com/MakeAPullRequest/makeapullrequest.github.io)

By the time you're finished, you'll have submitted a real change to a real codebase and be able to see your username listed among [others getting started](/contributors).

The use case we're walking through is submitting code to an exisiting repository - this is exactly what you might do to contribute to an [Open Source](https://github.com/open-source) project.

So, let's get to it!

# Step 0: Make a GitHub account

We're going to be contributing to a codebase hosted on GitHub. In order to do so, you'll need a GitHub account. If you have one, login - if you do not, you'll need to [sign up](https://github.com/join).

# Step 1: Fork the repository

The first step in your journey to making a Pull Request against an existing repository is to create a copy of that repository. The purpose of doing so is that we can work on that copy without any fear of messing up the original.

AThere are many ways to copy a repository - the method we'll use is called [*forking*]

To fork a repository, head to its webpage and select the **Fork** button.

For this tutorial, we'll be forking the following repository: [https://github.com/MakeAPullRequest/makeapullrequest.github.io](https://github.com/MakeAPullRequest/makeapullrequest.github.io)

<a href="/assets/images/tutorial/Fork.gif" target="_blank"><img src="/assets/images/tutorial/Fork.gif" alt="Fork the repository"></a>

(Note: *If you are a part of any Organizations*, you will be prompted to pick where to Fork the repository to - either an Organization or your own personal account. For this tutorial, select your own account)

# Step 2: Make changes to the forked repository

Next, we'll make changes to the repository we forked. There are many ways to modify the content of a repository. For this tutorial, we'll be using the GitHub web interface to make our changes.

We will be updating a file called **contributors.yml** and adding our own GitHub username to it.

To begin - locate the file you'd like to modify. For this tutorial, the file we want to modify is found at **_data/contributors.yml**

<a href="/assets/images/tutorial/LocateFile.gif" target="_blank"><img src="/assets/images/tutorial/LocateFile.gif" alt="Locate the file to modify"></a>

Locate the **Edit** icon (a pencil) and select it. You'll now be able to modify that file directly via the webpage.

Again, don't worry about making mistakes! We're in our own copy (a.k.a. fork) of the repository, so it doesn't matter if we mess up.

Add your username to the list of contributors - to do so, add text similar to the following to the end of the file:

```
- username: @YOUR-USERNAME-HERE
```

<a href="/assets/images/tutorial/ModifyFile.gif" target="_blank"><img src="/assets/images/tutorial/ModifyFile.gif" alt="Modify the file"></a>

# Step 3: Commit the changes to the forked repository

After your modifications are complete, you need to save them. Scroll down to the area entitled **Commit changes**

There, add a short message describing your changes (e.g. "Added username") and select **Commit changes**

<a href="/assets/images/tutorial/CommitChanges.gif" target="_blank"><img src="/assets/images/tutorial/CommitChanges.gif" alt="Commit changes"></a>

# Step 4: Create the Pull Request!

It's finally time to create our Pull Request - this will notifiy the owners of the original repository that we have changes for them to review.

Select the **Pull requests** tab, then **New pull request**

<a href="/assets/images/tutorial/StartPullRequest.gif" target="_blank"><img src="/assets/images/tutorial/StartPullRequest.gif" alt="Start a Pull Request"></a>

GitHub will automatically understand that you want to introduce the changes in your *forked* repository into the *original* repository. You may see the word **base** and **head**, but they don't matter much in terms of this tutorial. Each term simply represents the original and forked repository respectively.

On the **Comparing changes** page, you can see exactly what the suggested differences are (this set of changes is called a "diff").

<a href="/assets/images/tutorial/Diff.png" target="_blank"><img src="/assets/images/tutorial/Diff.png" alt="Diff"></a>

To finish off creating the Pull Request, select **Create pull request** then fill out the form entitled **Open a pull request**. You'll need to add a title - and optionally a description -- to explain the changes you're making. 

Lastly, select **Create pull request**

<a href="/assets/images/tutorial/CreatePullRequest.gif" target="_blank"><img src="/assets/images/tutorial/CreatePullRequest.gif" alt="Create a Pull Request"></a>

# Step 5: Await your Pull Request being merged

You did it! You submitted a request to change a code repository. Your Pull Request should look something like this:

<a href="/assets/images/tutorial/PullRequestOpen.png" target="_blank"><img src="/assets/images/tutorial/PullRequestOpen.png" alt="Open Pull Request"></a>

What happens next is in control of the maintainers of the original repository. They now have the ability to see exactly what changes you'd like to make to their repository - and, if they're satisfied, they will *merge* your work into the original repository. Merging your work means it becomes a part of the original repository. Here's what a merged Pull Request looks like:

<a href="/assets/images/tutorial/PullRequestMerged.png" target="_blank"><img src="/assets/images/tutorial/PullRequestMerged.png" alt="Merged Pull Requet"></a>

If you've been following this tutorial, once your Pull Request is merged you'll see your name appear on this webpage: [{{ site.url }}/contributors](/contributors)

Congrats! You've joined a worldwide community of developers contributing to code online.

# Further Reading

* [GitHub's "Creating a pull request from a fork"](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork)
* [A Survivor's Guide to Git](https://www.prolificinteractive.com/2018/12/05/a-survivors-guide-to-git/) - A beginner-friendly tutorial for understanding how to start using Git


