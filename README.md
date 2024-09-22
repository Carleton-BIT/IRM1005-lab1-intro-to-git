# intro-to-git-IRM1005-ITEC1005

**Note:** You must edit your code using VSCode, and perform actions in git using the git command line interface (as discussed in class!)

In this lab, you will do some simple HTML edits and commit your changes using the git CLI. These are the steps you must follow:

## Setup

1) Create a folder on your computer for this repository
2) Clone this repository into that folder using `git clone`
3) Open VSCode and install the Live Preview extension
4) Open the repository in VSCode

## Creating your first commit

6) Change the title of the webpage to "Lab 1",  verify it works using the Live Preview, and save your change
7) Stage your change for commit using `git add`
8) Commit the changes with a descriptive commit message using `git commit`

Important note for step 8: If you are using Nano [(nano looks like this)](https://www.linuxtrainingacademy.com/wp-content/uploads/2017/03/nano.png), after typing your message you can use ctl-X to quit, type y to save, and enter to confirm. If you're having problems, you may be using vim [(vim looks like this)](https://www.tecmint.com/wp-content/uploads/2019/04/Delete-Complete-Text-in-Vi-Editor.png) as your editor. If so, follow [these instructions](https://stackoverflow.com/questions/11828270/how-do-i-exit-vim) to exit vim. Once you've done so, you can change your editor to Nano with this command: `git config --global core.editor "nano"` and then you can try committing again.

11) Push your changes to your repository using `git push origin main`
12) Verify your changes are pushed to your repository by viewing it on the GitHub website

## If time permits - Creating your second commit

13) Change the body of the webpage to contain at least 4 different elements discussed in class (e.g. links, strong emphasis, stress emphasis, lists), and verify it works using the Live Preview. Then, save your changes.
14) Make a change to README.md
15) Stage your changes to both files for commit
16) Commit the changes with a descriptive commit message
17) Push your changes to your repository
18) Verify your changes are pushed to your repository by viewing it on the GitHub website
