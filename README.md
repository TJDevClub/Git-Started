# Lecture Notes

## Git and Github!
- Github is a way for people to collaborate on software projects. It revolves primarily around __Git__, a version control system that keeps track of the changes you make in a project.
- It's important to note that Git and Github are two complete separate things. Git is the version control part; Github is the collaborative part.
- Download Git [here](https://git-scm.com/downloads)
- Make a Github account [here](https://github.com/)
- Basics:
    + Create a git repository from inside a directory (folder):
        * __repository__ = project
        * `git init`
    + Clone a git repository into a directory:
        * __clone__ = to download a preexisting repository from github (or other git server)
        * `git clone https://github.com/TJDevClub/DevClubVR MyFolderName`
    + Commit a change:
        * After you've implemented a feature or fixed a bug, you'll want to **commit**, or "save" that version in Git.
        * You accomplish this in 2 steps:
            1. Add the files you want to commit.
                + `git add [file(s)...]`
            2. Commit the changes with a commit message.
                + `git commit -m "commit message"`
                + If you just do `git commit`, you will be prompted to enter a commit message.
    + Pushing your working directory:
        * After you have committed, you'll want to push your changes to the master version on Github.
        * `git push origin master`
        * `origin` is the remote repository (on Github's servers)
        * `master` is the branch that you are pushing; you can create more branches, we'll talk about why later.
    + Pulling from Github:
        * If you want to make sure your local repository is up to date with the remote repository, you'll want to pull.
        * `git pull origin master`
    + Help it's not working! Refer to this comic. Then Google it. Git provides fantastic documentation

    ![xkcd 1597](http://imgs.xkcd.com/comics/git.png)

## Activity time!
- Fork this repo on Github: `https://github.com/TJDevClub/Git-Started.git`
- Clone **your** repo: `git clone https://github.com/TJDevClub/Git-Started.git`
- Make a new file, call it 'hi.txt'
- Write whatever you want inside.
- Type `git status` to see the status of your files.
- Type `git add hi.txt` to add the file to your staging area.
- Commit this file, with the commit message "Say Hello"
    + Note on commit messages: Short commit messages should be **concise**,**informative**, in the **imperative form**, and in **title case**
- Make a new branch called "Hello" with
    + `git branch Hello`
- You can checkout this branch with
    + `git checkout Hello`
- Then you can push to your repo.
- Do some more stuff; whatever you want.
- Make a pull request to the official TJ Dev Club repository.

## Resources (I highly recommend reading these)
- [A visual guide to Git](https://marklodato.github.io/visual-git-guide/index-en.html)
- [Udemy's Guide to Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1)
- [Better Explained's Guide to Git](https://betterexplained.com/articles/aha-moments-when-learning-git/#GUIDs_are_GOOD)
- [Learn Git in Y minutes](https://learnxinyminutes.com/docs/git/)
