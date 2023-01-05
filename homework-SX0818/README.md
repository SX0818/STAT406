## Homework

*Don't make copies of files. These are yours. Just edit `hw0X.Rmd` and save. You will commit this and the knitted `hw0X.pdf`. Those should be the only files you need to deal with.*


This repository contains all of the homework assignments. Solutions will be posted in the "homework-solutions" repository.


If you lose 5+ points due to content, you may revise to gain up to 50% of lost points within 1 week of the PR review by pushing to the same branch and re-requesting review. The revision option does not apply to "penalties" incurred for failing to include the pdf, printing warnings in your document, etc.

> You MUST make at least 5 commits per homework assignment.

## Due dates

All due at 11pm

* HW1 29 September 
* HW2 18 October
* HW3 3 November
* HW4 22 November
* HW5 6 December

---

## Process

* First, you must `clone` this repo to your machine. You only need to do this once. The easiest way is with an RStudio Project. File > New Project > Version Control > Git. Then copy the url into the first field. You can save anywhere you like on your machine. 

* Now you're ready to go. So you want to start working...

* The below is the same as at [Stat-406/FAQ](https://ubc-stat.github.io/stat-406/faq/)

**If you are confused or concerned SAVE YOUR WORK and then post to Slack for help**

### Workflow in an RStudio Project

1. Make sure you are on `main` (Check the git tab.) Pull with the Blue Arrow.
1. Create a new branch (name it anything you like).
1. Work on your documents and save frequently.
1. Stage your changes by clicking the check boxes.
1. Commit your changes by clicking **Commit**. 
1. Repeat 3-5 as necessary.
1. Push to Github with the Green Arrow.
1. When done, go to Github and open a PR. Be sure to Request Review from the TAs.
1. Use the dropdown menu to go back to `main` and avoid future headaches.

### Workflow from the command line

1. Make sure you are on `main`: `git branch -v`. Pull in any remote changes: `git pull`
1. Create a new branch `git branch -b <name-of-branch>`
1. Work on your documents and save frequently.
1. Stage your changes `git add <name-of-document1>` repeat for each changed document. `git add .` stages all changed documents.
1. Commit your changes `git commit -m "some message that is meaningful"` 
1. Repeat 3-5 as necessary.
1. Push to Github `git push`. It may suggest a longer form of this command, obey. 
1. When done, go to Github and open a PR. Request review from the TAs.
1. Switch back to `main` to avoid future headaches. `git checkout main`.

