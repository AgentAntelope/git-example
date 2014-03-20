git-example
===========

A repo for teaching git.

  - Add a new word to the dictionary and commit it. (You'll need to use the `git add` and `git commit` commands to do this. You don't need to push!)

  - Take out the commit that adds the bad words to the dictionary. (You'll need to use the `git blame` command to find the commit that added the bad words. Then you'll need to use the `git rebase -i` command to remove the commit.)

  - At some point in the history the tests slow down. Find the commit that caused this change. (You'll need to use `git bisect`.)

  - Find Alice's oldest commit. Explain what it does. (You'll need to use `git log`.)

  - Find Bob's most recent commit. Explain what it does. (Again, you'll need to use `git log`.)
