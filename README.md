I learned that a merge combines the history of 2 branches, so it adds them together, and then when it conflicts it gets fixed manually. Good for when history is needed.

I learned that a rebase is basically a application of a commit on top of another branch to keep the history linear and clean.

I learned that a squash takes a lot of commits and turns them into basically one, useful for keeping things tidy.

And a cherry-pick is when I take a single commit from one branch to another. Meaning I can do things like the hotfix that are targetted.

Feature 1 used a merge, feature 2 used a rebase, and feature 3 used a squash and a rebase. The hotfix used a cherry-pick

In real projects, I use a merge when I need branch history, a rebase when I need to clean up/linearize branch history, a squash when I need to clean up/remove messy commits in branch history
and a cherry-pick when I want to do a small targetted hotfix.