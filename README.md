# Hello!
This project will help you get setup and ready to work with Git and the GitHub flow.  

:heavy_check_mark: If you've never worked with Git, [this handbook](https://guides.github.com/introduction/git-handbook/) is a great intro to the concepts.  There's also a good guide on the [GitHub flow](https://guides.github.com/introduction/flow/).

# Get started
1. [Create your GitHub account](https://github.com/join).
1. [Download and install Git](https://git-scm.com/downloads).
1. [Download and install VS Code](https://code.visualstudio.com/download) (optional, but recommended!).
1. Configure Git with your name and email.  Use the same email that you created your GitHub account with:
```bash
# Open a command prompt
git config --global user.name "Your name"
git config --global user.email "your.name@canada.ca"
```

# Clone the remote project
Now that Git is setup, you're ready to start working.  You'll need a local copy of this project on your computer so you can make changes.  This is where the distributed part of Git comes in.  Many people can work on cloned, local copies of a project, and have those changes merged back into a single remote project (called `origin`).

```bash
# This command creates a copy of the repo in the command prompts current directory.
git clone https://github.com/SSC-CIO-DigitalTaskForce/hello.git
```
# Make a change
Next, we're going to make a change and commit it to your local project.  A commit is a snapshot of a file's current state.  Git keeps a history of all the commits made to a project, so you can always see exactly what was done over the life of a project.

1. Create a branch for your change.  This keeps your work separate from the main project until you're happy with it and ready to share it with other people working on the project.
```bash
# Change to the project directory
cd hello

# Create and change to a new branch
git branch your-branch-name
git checkout your-branch-name
```
2. Open the [HELLO.md](https://github.com/SSC-CIO-DigitalTaskForce/hello/blob/master/HELLO.md) markdown file in a text editor (I'm partial to [VS Code](https://code.visualstudio.com/download)).
3. Add your name to it and save the file.

:heavy_check_mark: Markdown lets you style text on the web.  As usual, GitHub has a [handy markdown guide](https://guides.github.com/features/mastering-markdown/).

# Check your project status
Now that you've changed a file, Git knows that a file has changed and can show you exactly what's different. This is where Git really shines!

```bash
# Show the changed files and what changed in them
git status
git diff
```

# Commit your changes
Once you're happy with the change you made, it's time to stage and commit them:

* **Stage**: tells Git you want to commit specific files.
* **Commit**: creates a snapshot of the files, which allows you to see their changes over time.

```bash
# Stage and commit the HELLO.md file to your branch
git add HELLO.md
git commit -m "Added my name to the project"
```

# Push your changes to the remote project
The last thing you need to do is share your changes with other people working on the project.  In GitHub, this is done with a pull request:

```bash
# Push your changes to the remote project so you can create a pull request
git push origin your-branch-name
```

Now head over to [the project on GitHub](https://github.com/SSC-CIO-DigitalTaskForce/hello) and create a [pull request](https://guides.github.com/activities/hello-world/#pr)!

# Getting other people's work
Once your pull request is merged, it's available to everyone.  As you're working, you'll also want to get other people's work, to make sure your local project stays in sync with the remote project:

```bash
# Change to the master branch and get the latest version of the remote project
git checkout master
git pull
```

If you're working on a change in a local branch, and new work comes in, you can add it to your local branch like so:

```bash
# Get the latest changes to master, switch to your branch and add those changes to your branch
git checkout master
git pull
git checkout your-branch-name
git rebase master
```

# That's it!
You're now ready to start working in Git.  If you have any problems following this guide, let us know with [an issue](https://github.com/SSC-CIO-DigitalTaskForce/hello/issues) or, even better, suggest a change with a pull request :wink:




