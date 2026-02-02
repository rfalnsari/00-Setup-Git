Let's recap the `git` commands you need to remember in order to work on the challenges during the semester.

## Status

First, let's make sure that our working directory is **clean**:

```bash
git status
```

If you get the following result, then you're all set and can start working on this challenge:

```text
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```

If you do not get this message, you need to first commit / clean your repo before you can start. Do not hesitate to raise a ticket to get some help from a TA over the first few days. `git` can be hard, so please do ask!

## First commit

Let's create a Python file:

```bash
touch today.py
```

Open this file in your text editor. You will need to declare and implement a function called `my_name_is`, which doesn't take any parameter and returns a constant of type `str`. The value of this constant will be your GitHub nickname.

Run `pylint today.py` until one test passes (no need for the second one to be successful, we'll take care of it in a second).

```text
Your code has been rated at 2.50/10 
```

Good, you made some progress. It's time to pause and save your progression. Just like a checkpoint!

```bash
git add today.py
git commit -m "Implement my_name_is function"
git push origin master
```

## Second commit

Let's start solving the second test. To do so, you need to declare and implement a function called `my_age_is`, which doesn't take any parameter and returns a constant . The value of the constant will be your age.

You can use this useful command to check what has changed in the file:

```bash
git diff
```

If you are satisfied, you can now commit & push to GitHub:

```bash
git add today.py
git commit -m "Implement function"
git push origin master
```
