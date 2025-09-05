# Git Playground 🎯

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active%20%2F%20Experimental-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A safe sandbox environment for experimenting with, practicing, and mastering advanced **Git** and **GitHub** workflows. This repository is intentionally designed to be a messy lab where I break things, learn, and reinforce my version control skills.

## 🚀 Purpose

-   **Hands-on Practice:** Go beyond theory and get real practice with Git commands.
-   **Experiment Fearlessly:** Try risky operations (rebase, reset, merge conflicts) in a controlled environment.
-   **Build Muscle Memory:** Reinforce workflow patterns through repetition.
-   **Track Progress:** Use this repo as a public log of my Git learning journey.

## 🛠️ What's Inside? (Experiments & Exercises)

This repo contains various branches and scenarios for practicing:

| Topic/Scenario | Branch Name | Description |
| :--- | :--- | :--- |
| **Basic Commits** | `main` | Practice making atomic commits with good messages. |
| **Branching & Merging** | `feature/*`, `bugfix/*` | Create branches, develop features, and merge them back. |
| **Rebasing** | `rebase-experiment` | Practice rewriting history and cleaning up commits. |
| **Merge Conflicts** | `conflict-branch` | Intentionally create and resolve merge conflicts. |
| **Interactive Rebase** | `interactive-rebase` | Practice squashing, rewording, and reordering commits. |
| **Git Hooks** | `hooks` | Experiment with client-side Git hooks. |
| **Stashing** | `stash-demo` | Practice saving and applying temporary changes. |

## 📖 How to Use This Repo

1.  **Clone and Explore:**
    ```bash
    git clone https://github.com/YOUR-USERNAME/git-playground.git
    cd git-playground
    git branch -a # See all the practice branches
    ```
2.  **Checkout a Branch:** Pick a topic you want to practice and switch to its branch.
    ```bash
    git checkout -b rebase-experiment origin/rebase-experiment
    ```
3.  **Experiment:** Follow the instructions (if any) in the branch's README or just start experimenting!
4.  **Break Things:** The goal is to learn. Don't be afraid to break the repository. You can always delete it and re-clone it.

## 🔄 Reverting to a Clean State

Inevitably, you'll mess things up. Here's how to reset your local playground:

```bash
# Get the latest from the remote, overwriting any local changes
git fetch origin
git reset --hard origin/main

# Or, simply delete the repo and re-clone it (easiest method!)
rm -rf git-playground
git clone https://github.com/YOUR-USERNAME/git-playground.git

## 🤝 Contributing & Feedback

This repository is primarily a personal learning log. Therefore, direct pull requests for code changes are not expected. However, I greatly value knowledge sharing and constructive feedback!

**The best ways to contribute:**
-   **Open an Issue:** If you have a suggestion for a complex Git scenario, a tricky exercise idea, or found an insightful resource, please open an Issue. Let's discuss and learn together!
-   **Share Ideas:** Your ideas for advanced branching strategies, realistic merge conflict examples, or useful hook scripts are highly welcome.

This is a playground for experimentation, and collaborative learning makes it more powerful.