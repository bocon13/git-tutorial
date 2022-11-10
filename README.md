# GitHub Guide for Contributing to Existing Repos from the Web Browser

When using GitHub from a web browser, you can mostly ignore the details and complexities of git, but it is helpful to understand the general flow for how changes are made:
https://docs.github.com/en/get-started/quickstart/github-flow

The general idea is:
1.	Make a new **branch** when you want to start a new change
2.	Add as many commits as you want to that branch during development (and as you address comments from review)
3.	Create a **pull request** when you are ready to share (which will automatically get updates as you continue to update your branch)
4.	Merge the pull request when you’re happy with it

*Note: The materials in this tutorial are part of GitHub’s documentation, and there will be often interesting and related content adjacent to these links in the navigation bar on the left.*

## GitHub Web-Based File Editor

This is the easiest way to make changes to existing files in GitHub:
https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files

If you’re working with Markdown files, you’ll need to understand at least basic Markdown syntax:
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

## GitHub.dev Web-Based IDE (VS Code)

For changes to multiple files or in cases where you want a richer development environment, GitHub also offers VS Code in the cloud that automatically syncs with your repo:
https://docs.github.com/en/codespaces/the-githubdev-web-based-editor

There is also a live tutorial and demo that works through an example:
https://www.youtube.com/watch?v=jIHfmJvWkkc

VS Code has a lot of features and shortcuts:
https://code.visualstudio.com/docs/introvideos/basics

## Pull Requests

When multiple people are working on the same file in parallel, the second (and third, etc.) person to try to merge their code may encounter a merge conflict if git can’t figure out how to merge the two changes together (and git is pretty conservative).

When conflicts happen, it’s usually pretty easy to resolve:
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github

Sometimes conflicts are too complex to resolve in the GitHub UI. You can resolve it using git from the terminal, copy your changes to a new branch and start over, or ask someone on your team for help.

**Tips to avoid merge conflicts:**
-	Keep changes small – you’ll be less likely to have conflicts and they’ll be easier to resolve when they happen.
-	Keep changes quick – the longer your branch exists, the more likely it will diverge from the **main** branch.
-	Start new changes from the main branch – starting from old branches increases the likelihood that you’ve diverged before you even get started.
