# git-survival-kit

For many developers, working life has become tough 😀 since Git has become widely used, and one of the main version 
control systems (CVS) adopted in the software development landscape.
Simple, because we think that for really undestand how git work and what is under the hood of the plugins, the better 
thing is the use of the Command Line Interface (CLI). 

Yes, that devil 😈.

This is the reason of the born of this repository, indeed the aim would create a collection of the most useful Git commands, 
that help developers and not, to survive in a working day with Git as CVS.

## About GIT

So, what is Git in a nutshell?

This is an important section to absorb, because if you understand what Git is and the fundamentals of how it works, then using Git effectively will probably be much easier for you. As you learn Git, try to clear your mind of the things you may know about other VCSs, such as CVS, Subversion or Perforce — doing so will help you avoid subtle confusion when using the tool. Even though Git’s user interface is fairly similar to these other VCSs, Git stores and thinks about information in a very different way, and understanding these differences will help you avoid becoming confused while using it.

Source: [Getting Started - What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)

## Top commands

Below the most used GIT commands in a developer day.

### Command `clone`

**Description:** Clone a repository into a new directory.

**Reference:** [git-add](https://git-scm.com/docs/git-clone)

### Command `add`

Add file contents to the index.

**Reference:** [git-add](https://git-scm.com/docs/git-add)

---

### Command `commit`

Record changes to the repository.

**Reference:** [git-add](https://git-scm.com/docs/git-commit)

---

### Command `push`

Update remote refs along with associated objects.

**Reference:** [git-add](https://git-scm.com/docs/git-push)

---

### Command `checkout`

Switch branches or restore working tree files.

**Reference:** [git-add](https://git-scm.com/docs/git-checkout)

---

### Command `merge`

Join two or more development histories together.

**Reference:** [git-add](https://git-scm.com/docs/git-merge)

---

### Command `revert`

Revert some existing commits.

**Reference:** [git-add](https://git-scm.com/docs/git-revert)

---


## Semaphore similitude

For novice devs, one of the common mistake is the wrong command sequence. All are familiar with one of this phrases.

## Git commit without add

_When I try to commit files, Git say "Your branch is up to date with 'origin/main'"_ 🤔

## Git push without commit

_When I try to push my changes, Git say that "Everything up-to-date"_ 🤔

### Add and commit without push
_Mmmm...I do git fetch and git pull, but "I'm not see your updates"_ 🤔


To fix in mind the right sequence of commands, to make available your updates at the rest of dev teams, thing a semaphore

🔴 Add updated files with `git add`</br>
🟠 Commit the changes with `git commit` or `git commit -m "Ok I'm committed"`</br>
🟢 Push to remote repository with `git push`</br>



## Reference Documentation
For further references, please consider the following resources:

- [GIT docs](https://git-scm.com/docs)
- [GIT book (EN) v.2 ](https://git-scm.com/book/en/v2)

## Contributors

- [fra-diomede](https://github.com/fra-diomede)
- [GuastafierroSt](https://github.com/GuastafierroSt)
- [vacammar](https://github.com/vacammar)
