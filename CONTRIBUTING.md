# Contribution Guidelines

This document describes basic guidelines for contributors at any FlutterBuddies' project.

All project communication shall be done at issues or FlutterBuddies Discord  [server](https://discord.gg/X3pfRES6). Everything in this text that you find confusing or have any objections, can and should be discussed at issues or Discord.

The upcoming titles sort of describe the order of things you want to explore before contributing to a project.

## Discord

If you'd like to talk about the project in general, please do at project's Discord channel. We can go on from there.

## Issues

Issues at the project's repository are a main place to look at when planning to contribute. Two situations can occur:

**Your idea is already present in an issue**

In this case, after reading all the comments at this issue to assess the situation and how it aligns with your ideas, you can

- add your comment with some further insight or a question
- contact issue's assignee (either by leaving a comment with assignee tagged or contacting assignee directly) for details on how can you contribute code

**You have an idea not present in issues**

In this case, you can create a new issue with detailed explanation of your idea, question or bug report with minimal code example if applicable. Then the other contributors will comment further at your issue and you can plan how this will be developed. By default, you can then become the assignee at this issue, the one who will be responsible for it's development. Of course, this is not forced upon anyone so you can let us know in the comments that you prefer not to be the assignee. Then others can apply to be the assignee.

If an issue doesn't have an assignee, the position is open for anyone who wants it. In this assigneeless situation, the "acting assignees" are FlutterBuddies admins.

## Pull Requests

To contribute, you will eventually be doing a **Pull Request** for your **Fork**. See [Useful links](#useful-links) bellow if you're not familiar with these concepts.

First, you need to fork the project's repository and set the upstream via `git remote add upstream https://github.com/Flutter-Buddies/<project>.git`.

When you fork the project, you will be at `main` or `master` branch by default. To switch branches, use `git checkout <branch-name>`. It will be clearly discussed on which branch should each issue be worked on if project has multiple branches.

If you are contributing at some branch for a while, to have the latest changes if something has been pushed in the meantime, do `git fetch upstream`. This will create branches `upstream/<branch-name>` that you then need to merge into your branch you're working on. To do that, `git checkout <branch-name>` (if you're not already on it) and `git merge upstream/<branch-name>`.

After you are done with implementing your changes, push them to your repository. Then, create a Pull Request for your changes to be merged into `upstream`, i.e. the original FlutterBuddies `<project>` repository.

### Useful links

- [Git Handbook](https://guides.github.com/introduction/git-handbook)
- [GitHub Hello World](https://guides.github.com/activities/hello-world/)
- [git branches - official GitHub docs](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-branches)
- [Fork - official GitHub docs](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo)
- [Syncing a fork - official GitHub docs](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)
- [Syncing a fork - StackOverflow](https://stackoverflow.com/questions/7244321/how-do-i-update-a-github-forked-repository)
- [Creating a pull request from a fork - official GitHub docs](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)

## Code Style

It is sufficient that you format your code. See [here](https://flutter.dev/docs/development/tools/formatting) how this can be accomplished and automated.
