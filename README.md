# classwork-more-like-funwork
(For CSCC Purposes Only.)

* [Assignment](https://gist.github.com/peterhurford/4d43aa5d6de114c0c741ba664c9c5ff5)
  * [Question 1](question-1)  
  * [Question 2](question-2)  
  * [Question 3](question-3)  
* [References](./Lab2Git.pdf)

## Question 1
How do you see the files changed within each commit from git log?  
* Running `git log --stat` within a git bash terminal will show the files being changed within each commit.   

## Question 2
How do you see the contents of what changed within each file from the git log?
* Using the `git diff` command will show the contents of each file.  For added flare, add the `--patch` flag onto the command to provide further versatility.  

## Question 3
What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
* A HEAD is a reference to the most recent commit on your local branch. This is not to be confused with a `head` which is a reference to the big, heavy thing on top of your body. (See [head](https://www.dictionary.com/browse/head))
