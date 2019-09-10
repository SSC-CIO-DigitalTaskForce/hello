# Hello!
This project will help you start working with GitHub. Once you've finished, you'll be able to: 

* [Clone a repository](#clone-a-repository)
* [Create a new branch](#create-a-new-branch)
* [Make a change](#make-a-change)
* [Create a pull request](#create-a-pull-request)
* [Merge a pull request](#merge-a-pull-request)
* [Update your repository](#update-your-repository)

:rocket: If you're new to Git, [this handbook](https://guides.github.com/introduction/git-handbook/) is a great intro.

# Setup
1. [Create your GitHub account](https://github.com/join).
1. [Download and install GitHub Desktop](https://desktop.github.com/).
1. [Download and install VS Code](https://code.visualstudio.com/download) (optional, but recommended).
1. Open GitHub Desktop.
1. Go to `File > Options` and select `Accounts`.
1. Sign into your GitHub account.
1. Next, select `Git`, enter your name and email address and **Save**.

# Clone a repository
To work with GitHub, you need a local copy of the repository (or project) on your computer.

1. Go to `File > Clone Repository...`.
1. Select this repository (`SSC-CIO-DigitalTaskForce/hello`).
1. Select the folder you want to clone it to on your computer and **Clone**.

Now you have a local copy of the repository that matches the remote repository on GitHub.

# Create a new branch
We use the [GitHub flow](https://guides.github.com/introduction/flow/) to make changes, so the first step to making a change is creating a new branch.

1. Make sure `hello` is selected as the current repository in the top bar.
1. Select `Current branch` from the top bar and click **New branch**.
1. Give it a meaningful name and click **Create**.

You're now working on a new branch of the repository.  All Git repositories have a main branch called `master`.  When you make changes in a new branch, it keeps your changes separate from the `master` branch until you're ready to merge them.  

# Make a change
1. Open the `HELLO.md` [markdown file](https://guides.github.com/features/mastering-markdown/) in a text editor like Notepad or VS Code.
1. Add your name to the file and **Save**.
1. Go back to GitHub Desktop.  It now shows that you've changed the `HELLO.md` file, and exactly what was changed.  
1. If you're happy with the change, enter a commit summary and click **Commit**.  For more complex changes, you can also enter a description.

![GitHub Desktop view of file changes and the commit message](./assets/imgs/diff.png)

You've just created a new commit!  This is where Git shines.  It keeps a complete history of changes (commits) made to a project that you can browse whenever you want.

# Create a pull request
Now that you've made a change, it's time to merge it with the `master` branch of the repository so everyone can see it.  This is done with a pull request.

1. Select `Publish branch` from the top bar.  This pushes your new branch up to the remote GitHub repository.
1. Select `Create Pull Request`.  This opens GitHub in a browser and lets you confirm your changes.
1. Update the pull request title and description to explain the change.
1. Click `Create pull request`.

The pull request can now be reviewed by other team members, and if everything looks good, it will get merged into `master`.  

# Merge a pull request
The final piece needed to make your change available to everyone working on the repository is to merge your pull request.

1. Go to the [pull requests page of this repository](https://github.com/SSC-CIO-DigitalTaskForce/hello/pulls) and select your pull request.
1. Click the arrow next to the `Merge pull request` button and select `Rebase and merge`.
1. Click the `Rebase and merge` button and confirm the merge.

Your changes are now part of `master`!  You can also delete your branch.  In Git, it's a good idea to merge smaller changes more frequently, so it's normal to create a branch, make a single change and then delete the branch.

# Update your repository
As you're working on a repository, you'll also want to get other people's changes so you stay in sync with their work.  

1. Select `Fetch origin` from the top bar.
1. If there are changes, it will ask if you want to `Pull origin`.  This will merge the changes with your selected branch.

# That's it!
You're now ready to start working in Git.  If you have any problems following this guide, let us know with [an issue](https://github.com/SSC-CIO-DigitalTaskForce/hello/issues) or, even better, suggest a change with a pull request :wink:
