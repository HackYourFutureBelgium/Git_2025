# HOMEWORK SUBMISSION

## TL;DR

- [ ] Start any coding session from `main`.
- [ ] Periodically keep your local `main` up to date with changes in the remote `main`.
- [ ] Periodically merge the up-to-date local `main` into your homework branch.
- [ ] Always checkout to a new homework branch from `main`.
- [ ] Did we mention `main`?
- [ ] Implement the homework in the right folder.
- [ ] Write meaningful commit messages.
- [ ] Before pushing, double check that your branch name is correct.
- [ ] If the branch name is not correct, you can checkout to a new, correct branch from the current branch - you will carry all the commits with you.
- [ ] If your PR has been auto-closed, do not reopen it. Follow the guidlines and make a proper PR.
- [ ] Stay patient. Slack, Google and ChatGPT are your best friends now.
- [ ] Make the changes as per PR review in the appropriate branch, push the changes to the appropriate branch, and close the PR.

 <br/>

<hr>
<hr>

## Before you start your homework

1. You are probably opening the local repo on the last weeks branch - make sure that any changes you have there are either committed and pushed, or stashed, or discarded - whatever you prefer. The point is to be mindful that:
   <br/> - you are most probably starting on a branch you last worked with, that is how VS Code works,
   <br/> - and there might be changes that you have not handled last time.

<br/>

2. Checkout to `main` and pull the latest changes from it. If you skip this step, you will get in trouble sooner or later.

<br/>

3. Checkout to your new homework branch, following the branch naming convention of `module-week/yourname`. If `week` is not applicable, it is obviously just `module/yourname`.
   See [allowed branch name prefixes](#allowed-branch-name-prefixes).

<br/>
❗ If you name the branch incorrectly, your PR might get automatically closed (soon after opening), depending on the configurations that are set up at that moment in your homework repo. It is your responsibility to monitor it and, if needed, open a new PR from a new correctly-named branch. **Do not reopen the closed PR**.

<br/>
❗ Always firstly checkout to the new homework branch from an updated `main`. Always.

<br/>

### Allowed branch name prefixes:

|                   |                   |                   |                   |     |
| ----------------- | ----------------- | ----------------- | ----------------- | --- |
| git-week1         | git-week2         |                   |                   |     |
| javascript1-week1 | javascript1-week2 | javascript1-week3 | javascript1-week4 |
| javascript2-week1 | javascript2-week2 | javascript2-week3 |                   |
| javascript3-week1 | javascript3-week2 | javascript3-week3 |                   |
| typescript        |                   |                   |                   |     |
| databases-week1   | databases-week2   | databases-week3   |                   |     |
| node-week1        | node-week2        | node-week3        |                   |     |
| react1-week1      | react1-week2      | react1-week3      |                   |     |
| react2-week1      | react2-week2      | react2-week3      |                   |     |

### Examples

> ❌ git/weeek1/maria <br/>
> ❌ javascript1/maria <br/>
> ❌ git-week2 <br/>
> ❌ node-week1-homework <br/>
> ❌ react2-week4/maria <br/>
> ❌ react1week1/maria <br/>
> ✅ javascript1-week3/maria

<br/>

## Completing and submitting your homework

1. Implement your homework in the right folder. Be mindful of structuring and naming.

<br/>

2. If you take a longer time to finish the homework, periodically update your local `main` and your homework branch with `main`. Google "update your feature branch with main". The feature branch in this case is your homework branch.

<br/>

3. Verify that your branch name is right. Commit and push your homework to the repository. If the branch name is not right, you can commit and checkout to a new, correct branch from the current branch - you will carry all the commits with you. Then you can push.

<br/>

4. Go to the homework repository and create a Pull Request from your homework branch to `main`.

<br/>

5. Post the link to the PR to your class channel and celebrate with your classmates! 🎉 💃🏽 🕺🏾 🥳

<br/>

## After submitting your homework

1. Follow the PR to see the review (if you submitted it on time) and interact with the reviewer as well as make the suggested changes.

<br/>

2. When you have made changes to the code since the homework submission and review, push the changes and close the PR`*`.

<br/>
<br/>

> `*` Why you should close the PR and not merge it? PRs are normally intended to merg code!
> <br/> It is because you are sharing a central homework repository. We do not aim to merge all your homeworks into one clump - that does not make any sense and would be a very chaotic process as you are implementing your homeworks in the same folders, and some of you might even have the same naming. The more you understand about Git, the more this will make sense. The point here is just to have a convenient submission process while you also practise shared repository handling every week.
