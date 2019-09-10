# Hello!
This project will help you get setup and ready to work with Git and the GitHub flow. If you're new to Git, [this handbook](https://guides.github.com/introduction/git-handbook/) is a great intro.

# Get started
1. [Create your GitHub account](https://github.com/join).
1. [Download and install GitHub Desktop](https://desktop.github.com/).
1. [Download and install VS Code](https://code.visualstudio.com/download) (optional, but recommended).

# Setup GitHub Desktop
1. Open GitHub Desktop.
1. Go to `File > Options` and select `Accounts`.
1. Sign into your GitHub account.
1. Next, go to `Git`, enter your name and email address and **Save**.

# Clone a repository
To work with GitHub, you need a local copy of the repository on your computer.

1. Go to `File > Clone Repository...`.
1. Select this repository (`SSC-CIO-DigitalTaskForce/hello`).
1. Select the folder you want to clone it to on your computer and **Clone**.

You're now ready to start making changes!

# Create a new branch
We use the [GitHub flow](https://guides.github.com/introduction/flow/) to make changes.  To get started, we'll create a branch:  

1. Make sure `hello` as the Current repository in the top bar.
1. Select `Current branch` and click **New branch**.
1. Give it a meaningful name and click **Create**.

You're now working in a new branch of the repository.  All Git repositories have a main branch called `master`.  When you make changes in a new branch, it keeps your work separate from the `master` branch until you're ready to merge your work.  

# Make a change

1. Open the `HELLO.md` markdown file in a text editor like Notepad or VS Code.
1. Add your name to the file and **Save**.
1. Go back to GitHub Desktop.  It now shows that you've changed the `HELLO.md` file, and exactly what was changed.  
1. If you're happy with the change, enter a commit summary and click **Commit**.  For more complex changes, you can also enter a description.

![GitHub Desktop view of file changes and the commit message](./assets/imgs/diff.png)

You've just created a new commit!  This is where Git shines.  It keeps a complete history of changes (commits) made to a project that you can browse whenever you want.

# Create a Pull Request

Now that you've made a change, it's time to merge it into the `master` branch of the repository.  This is done with a pull request.

1. Select `Publish branch` from the top bar. 
1. Select `Create Pull Request`.  This opens GitHub in a browser and lets you view your proposed changes.
1. Update the pull request title and description to explain your change.
1. Click `Create pull request`.

The pull request can now be reviewed by other team members, and if everything looks good, it will get merged into `master`.  

# Update your local repository
As you're working on a repository, you'll also want to get other people's changes.  

1. Select `Fetch origin` from the top bar.
1. If there are changes, it will ask if you want to `Pull origin`.  This will merge the changes with your selected branch.

# That's it!
You're now ready to start working in Git.  If you have any problems following this guide, let us know with [an issue](https://github.com/SSC-CIO-DigitalTaskForce/hello/issues) or, even better, suggest a change with a pull request :wink: