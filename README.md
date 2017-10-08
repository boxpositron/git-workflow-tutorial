# Git workflow tutorial
This repo outlines our Git workflow as well as contains a list of CDC projects contributors. When working on any CDC project, please follow this workflow.

- Fork the repository in question.
- Clone your fork (e.g `git clone https://github.com/YOUR-USERNAME/REPO-NAME.git`).
- Create a new branch for the issue you're working on. The issue can be a feature, fix, documentation etc. You can name the branch whatever you want. We recommend a short and descriptive name, delimeted by hyphens if it contains 2 or more words (e.g `git checkout -b the-great-fix`).
- Work on the issue. Ensure your solution functions as intended. Run tests if any.
- Add, commit and push (`git add .`, `git commit -m "so so and so"`, `git push`). Please refer to this guide to learn how to write **semantic commit messages**: https://seesparkbox.com/foundry/semantic_commit_messages. "Useless" commit messages won't be tolerated. *True story!*
- Go to the upstream repo (i.e the repo your forked from) and start a Pull Request (PR). Describe in details what you did to accomplish the given task, referencing the issue you worked on. Your PR would be reviewed ASAP and merged with the main repo. If we have any issues with your PR, we'd tell you to make the neccessary corrections then merge it.
- Sync your fork to the upstream once your PR has been merged.
- Delete the branch you worked on.

### Help
- [How to fork a repo](https://help.github.com/articles/fork-a-repo).
- [How to clone a repo](https://help.github.com/articles/cloning-a-repository).
- [How to create and delete a branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository).
- [How to sync a fork](https://help.github.com/articles/syncing-a-fork).

*Learn more about **Git** and **GitHub** here: **https://help.github.com**. Also, don't forget to communicate to us any issues you may be having on the **Slack**. Remember: "Rome wasn't built in a day..."*

**For you to work on any CDC project, you MUST first add your name to the list of contributors in CONTRIBUTORS.md (on this repo) using our workflow.**

To do this you don't need to clone this repo to your local computer like you would a normal project. You can do everything on GitHub. All you have to do is fork the repo, create a new branch in your fork (name the branch your GitHub username), add your full name to the list of contributors, then commit. Start a PR on this repo and we'll merge ASAP. Cheers!