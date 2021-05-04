# Example to discuss and practice Git conflict resolution

There are two branches in addition to `main`: `improve-starters` and `improve-desserts`
and you can try these steps to discuss and practice conflict resolution:

- merging first `improve-starters` into `main`, then `improve-desserts` into `main`
- merging first `improve-desserts` into `main`, then `improve-starters` into `main`
- merging `improve-desserts` into `improve-starters` and vice versa

You can abort merges with `git merge --abort` and rewind `main` back with `git reset --hard origin/main`.

Also try to rebase the branches on top of `main`, "behind" each other.
