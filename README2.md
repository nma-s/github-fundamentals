
# What I have learned this week 

This week we have covered the fundamentals of GitHub. Before I go on further to the nitty gritty, let discuss what GitHub is and the purpose of it. 

## What is GitHub 

To understand what GitHub is, it is crucial to grasp an understanding of Git.

Git is a **distributed** (Decentralised) version control system that allows developers to: 
- track changes in their code
- collaborate with other develops on projects
- share projects with others

#### What do we mean by distributed? 

Being distributed means that every developer has a fully copy of the repository on their own machine, including the history.

**Github** is a cloud based hosting platform for **Git** repositories. It provides an online remote space for developers to host, collaborate and track issues. 

### Good to know

* Git works locally on your computers
* GitHub works remotely so allows you to push repos to the cloud so tht you can access your repo from anywhere

## How does Git/GitHub work?

There are a number of features that make up GitHub. 

### 🗂 Repositories

A **repository** (or "repo") is a remote storage location for your projects. It holds all your code files, configuration files, documentation (like a `README.md`), other assets. 

Repositories are used to:
- Organize and store your project
- Track the history of your code changes
- Collaborate with other developers

### 🌿 Branches
A **branch** is a parallel version of your code. The default branch is usually called `main`, and it represents the stable version of your project.

When developing new features or fixing bugs, you typically **create a new branch**. This lets you work on your changes **without affecting the main branch**.

- Each new branch starts out with the same content as the branch it was created from (usually `main`).
- You can then make changes independently in that branch.
- This keeps your __main codebase__ clean and functional while you experiment or build new things.

### 🔁 Merging
Once you're happy with the changes in your branch (for example, after testing a new feature), you can **merge** that branch back into `main`.

- Merging takes the new code and integrates it into the main branch.
- Before merging, it’s common to review the changes and resolve any conflicts if two branches changed the same lines of code.

This workflow helps teams work on multiple features at the same time without overwritting each other code.

### Cloning

Cloning is used to create a copy of a remote repository on your local system.

> The command: `git clone https:....`

### 🍴 Forking

**Forking** a repository means that you can create a copy of someone else's GitHub repository under your own GitHub account. is similar to cloning. It allows you to work on the repo without changing the original version.

Forking is commonly used when:
- You want to contribute to an open-source project.
- You need to experiment with someone else's codebase safely.
- You plan to suggest changes through a pull request.

### 🆚 Forking vs. Cloning

- **Forking** creates a **copy of the repository on GitHub** (your online account).
- **Cloning** creates a **copy of the repository on your local machine** (your computer).

You can fork first (to get a version under your account), then clone it to your computer to make local changes.

### 🤝 Collaboration Through Forks

Once you've made changes in your forked repo, you can:
- Push your updates to *your* GitHub fork.
- Create a **pull request** to suggest your changes to the original repository.
- Use comments and discussions to get feedback and improve your code before it’s merged.

This makes forking a powerful tool for **collaboration and open-source contributions**.

### 🅿️ Pull Requests 

Opening a pull request allows you to tell others about the changes you want to make and create a forum for discussion  and feedback.