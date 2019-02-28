---
layout: default
---

Let's get started making our first Pull Request.

# Step 0: Make a GitHub account

# Step 1: Fork the repository

The first step in your journey to making a Pull Request against an existing repository is to create a copy of that repository. There are many ways to copy a repository, the method we'll use is called *forking*. [Read More](https://help.github.com/en/articles/fork-a-repo)

To fork a repository, head to its webpage and select the **Fork** button.

If you are a part of any Organizations, you will be prompted to pick where to Fork the repository to - either an Organization or your own personal account. For this tutorial, select your own account.

<a href="/assets/images/tutorial/Fork.gif" target="_blank"><img src="/assets/images/tutorial/Fork.gif" alt="Fork the repository"></a>

# Step 2: Make changes to the forked repository

Next, we'll make changes to the repository we forked. Again, there are many ways to modify the content of a repository. For this tutorial, we'll be using the GitHub web interface to make our changes.

We will be updating a file called **contributors.yml** and adding our own GitHub username to it.

To begin - locate the file you'd like to modify.

<a href="/assets/images/tutorial/LocateFile.gif" target="_blank"><img src="/assets/images/tutorial/LocateFile.gif" alt="Locate the file to modify"></a>

Locate the Edit icon (a pencil) and select it. You'll now be able to modify that file directly. And, don't worry about making mistakes - were in our own copy (a.k.a. fork) of the repository, so it doesn't matter if we mess up!

<a href="/assets/images/tutorial/ModifyFile.gif" target="_blank"><img src="/assets/images/tutorial/ModifyFile.gif" alt="Modify the file"></a>

# Step 3: Commit the changes to the forked repository

After your modifications are complete, you need to save them. Scroll down to the area entitled **Commit changes**

There, add a short message describing your changes (e.g. "Added username") and select **Commit changes**

<a href="/assets/images/tutorial/CommitChanges.gif" target="_blank"><img src="/assets/images/tutorial/CommitChanges.gif" alt="Modify the file"></a>

# Step 4: Create a Pull Request!

It's finally time to create our request to have our changes pulled into the original repository.

Select the **Pull requests** tab, then **New pull request**

<a href="/assets/images/tutorial/MakePullRequest.gif" target="_blank"><img src="/assets/images/tutorial/MakePullRequest.gif" alt="Modify the file"></a>

GitHub will automatically understand that you want to introduce the changes in your forked repository into the original repository. It will show you on the **Comparing changes** page exactly what the difference is between the original repository and your fork (this set of changes is called a "diff").

<a href="/assets/images/tutorial/Diff.png" target="_blank"><img src="/assets/images/tutorial/Diff.png" alt="Modify the file"></a>

To finish off creating the Pull Request, select **Create pull request** then fill out the form entitled **Open a pull request**. You'll need to add a title and optoinal description to explain the changes you're making. Lastly, select **Create pull request**

<a href="/assets/images/tutorial/MakePullRequest.gif" target="_blank"><img src="/assets/images/tutorial/MakePullRequest.gif" alt="Modify the file"></a>

# Step 5: Await your Pull Request being merged

You did it! What happens next is in control of the maintainers of the original repository. They now have the ability to see exactly what changes you'd like to make to their repository - and, if they're satisfied, they will *merge* your work.

If you've been following this tutorial, once your Pull Request is merged you'll see your name appear on this page: [{{ site.url }}/contributors](/contributors)

Congrats!

# Further Reading

* [A Survivor's Guide to Git](https://www.prolificinteractive.com/2018/12/05/a-survivors-guide-to-git/) - A beginner-friendly tutorial for understanding how to start using Git


