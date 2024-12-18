# ⛑️ git-survival-kit

For many developers, working life has become tough 😀 since Git has become widely used, and one of the main version 
control systems (CVS) adopted in the software development landscape.

Now, most of your say yourself; "_But because use Git from CLI, when we have beautiful plugins in the my favourite IDE?_"
Simple, because we think that for really understand how git work and what is under the hood of the plugins, the better 
thing is the use of the Command Line Interface (CLI). 

Yes, that devil 😈.

This repository born with indeed the aim would create a collection of the most useful Git commands, 
that help developers, and not, to survive in a working day with Git.

## About GIT

So, what is Git in a nutshell?

This is an important section to absorb, because if you understand what Git is and the fundamentals of how it works, then using Git effectively will probably be much easier for you. As you learn Git, try to clear your mind of the things you may know about other VCSs, such as CVS, Subversion or Perforce — doing so will help you avoid subtle confusion when using the tool. Even though Git’s user interface is fairly similar to these other VCSs, Git stores and thinks about information in a very different way, and understanding these differences will help you avoid becoming confused while using it.

**Source:** [Getting Started - What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)

## Top commands

Below the most useful GIT commands in a developer day, and some tricks.

### 📌`clone`

**Description:** Clone a repository into a new directory.

**Reference:** [git-add](https://git-scm.com/docs/git-clone)

### 📌`add`

Add file contents to the index.

**Reference:** [git-add](https://git-scm.com/docs/git-add)

---

### 📌 `commit`

Record changes to the repository.

**Reference:** [git-add](https://git-scm.com/docs/git-commit)

Or more convenient with `-m` option, that allow to specify a commit message in a single line. </br>
Example `git commit -m "Ok"`

---

### 📌 `push`

Update remote refs along with associated objects.

**Reference:** [git-add](https://git-scm.com/docs/git-push)

---

### 📌 `checkout`

Switch branches or restore working tree files.

**Reference:** [git-add](https://git-scm.com/docs/git-checkout)

---

### 📌 `merge`

Join two or more development histories together.

**Reference:** [git-add](https://git-scm.com/docs/git-merge)

**Scenario:** Suppose we need to merge a feature branch into develop branch.

One of the best strategy for reduce the possibility of conflicts, can be to first, merge destination branch (`develop`)
into `feature` branch, after move to destination (`develop`) branch and merge the `feature` branch. 

---

### 📌 `revert`

Revert some existing commits.

**Reference:** [git-add](https://git-scm.com/docs/git-revert)

---

### 📌 `tag`

Create, list, delete or verify a tag object signed with GPG.

**Reference:** [git-add](https://git-scm.com/docs/git-tag)

Declinations of `tag` command are used to:

- **List tags:** `git tag --list` or shortly `git tag -l`
- **Delete tag:** `git tag --delete my-tag` or shortly `git tag -d my-tag`

Remember also, that after the creation of tag, we need to push it:

`git push origin my-tag`

---

### 📌 `stash`

temporarily shelves changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on. Stashing is handy if you need to quickly switch context and work on something else, but you're mid-way through a code change and aren't quite ready to commit.

**Reference:** [git-add](https://git-scm.com/docs/git-stash)

`git stash pop`

This command restores the most recent changes you saved in the stash to your working directory and removes them from the stash list. It's useful when you temporarily saved changes and are ready to continue working on them.

---

## Devs mysteries 👻

For novice devs, one of the common mistake is the wrong command sequence. All are familiar with one of this phrases.

### Git commit without add

_When I try to commit files, Git say "Your branch is up to date with 'origin/main'"_ 🤔

### Git push without commit

_When I try to push my changes, Git say that "Everything up-to-date"_ 🥴

### Add and commit without push
_Mmmm...I do git fetch and git pull, but "I'm not see your updates"_ 🤯


## Semaphore similitude 🚦

To fix in mind the right sequence of commands, to make available your updates at the rest of dev teams, thing a semaphore.

🔴 Add updated files with `git add`</br>
🟡 Commit the changes with `git commit` or `git commit -m "Ok I'm committed"`</br>
🟢 Push to remote repository with `git push`</br>

Yes, that's all. </br>
Enjoy the power of Git 🚀


## The credentials hells 🔥

How many times we have entered credentials after single git command?</br>
I think it has happened to everyone at least once.

To solve this, use the below command:

`git config --global credential.helper store`

after, the credentials are stored into `~/.git-credentials` file and Git not ask you to digit again 😉



## Reference Documentation
For further references, please consider the following resources:

- [GIT docs](https://git-scm.com/docs)
- [GIT book (EN) v.2 ](https://git-scm.com/book/en/v2)
- [Learn Git Branching](https://learngitbranching.js.org)

## Contributors

We are only the start contributors, feel free to fork or integrate other, `we appreciate you contribute`.

- [fra-diomede](https://github.com/fra-diomede)
- [GuastafierroSt](https://github.com/GuastafierroSt)
- [vacammar](https://github.com/vacammar)
