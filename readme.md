# Pre-Cohort Orientation Markdown

### by Alex Merced (AlexMercedCoder.com)

## Welcome

Welcome!!! If you are reading this you are about to embark on a Software Engineering Immersive Remote course. I've created this markdown to highlight some best practices to best prepare before your first day of class and as a reference throughout the cohort for useful resources.

### Start Here

This guide below will tell you what you need to setup before the first day of class.

- [QuickStart Setup Guide](/more/quickstart.md)

Below you'll find videos and reference materials on all the main tools you'll be using throughout the course.

### Please Start by Watching the Video Below

[![Orientation Video](http://img.youtube.com/vi/1waFGXeNafY/0.jpg)](http://www.youtube.com/watch?v=1waFGXeNafY "Orientation Video")

**BEGINNERS REFERENCE POST**: https://tuts.alexmercedcoder.com/basicref/

## Bash (Terminal)

Bash is the default shell environment in unix based systems (Technically, Zsh is default on mac, but the commands are pretty much the same). Windows is not unix based which is the primary reason we heavily discourage going through the course with a windows environment although there are several options on how to use your windows machine in the course.

**Solutions for Windows Users**

<details>
<summary>
Reveal
</summary>
<p>

Bash is the default shell environment in unix based systems (Mac and Linux). Windows is not unix based which is the primary reason we heavily discourage going through the course with a windows environment although there are several options on how to use your windows machine in the course.

1. Install Xubuntu (https://xubuntu.org/) as a second operating on your machine (This is in my opinion the best option and a tutorial how to do so is here: https://www.lifewire.com/guide-to-installing-xubuntu-linux-2202075)

2. Use Windows Subsystem for Linux to have a Linux environment in your windows install (here is a tutorial => https://www.windowscentral.com/install-windows-subsystem-linux-windows-10 keep in mind any WSL specific issues will be on you to troubleshoot throughout the course)

3. Install Xubuntu into a virtual machine using VirtualBox (tutorial: https://lmtools.com/setup-ubuntu-virtual-machine-in-windows-using-oracle-virtualbox warning this can slow depending on the resources you share with the virtual machine)

4. Just use windows but install git-bash to have access to a bash shell in your windows file system, it's not exactly the same and will have minor differences along the way. I'll add a section later with tips if you decide not to go with option 1 which I HIGHLY recommend as the best option. (https://gitforwindows.org/)

</p>
</details>

---

You will be spending a lot of time in the course in the bash shell so getting familiar with how it works will make life much easier. So please watch the video below.

**VIDEO: INTRO TO BASH**

[![Bash Video](http://img.youtube.com/vi/snOP94q34V4/0.jpg)](http://www.youtube.com/watch?v=snOP94q34V4 "Bash Terminal")

**Bash Commands Reference**

<details>
<summary>
Reveal
</summary>
<p>

Exaustive List here: https://dev.to/awwsmm/101-bash-commands-and-tips-for-beginners-to-experts-30je

`ls -la` show all files in current directly including hidden files

`rm file.txt` remove file in this folder

`rm -rf folderName` remove folder in this folder

`touch file.txt` create a file in this folder

`mkdir folderName` make this particular folder

`pwd` print the directory you are currently in

`cat file.txt` print the contents of file to terminal

`cd folderName` go into subfolder

`cd ..` go into parent folder

`which commandName` which folder is the executable for a certain command

</p>
</details>

---

## Git

Git is software for tracking versions of files. This will be the primary way you'll track the progress of your code and submit it for evaluation. Just to make one thing very clear right way...

Git - software that tracks versions of different projects on your computer in local repositories.

Github.com and git.generalassemb.ly(Git Enterprise) - These sites host repositories remotely, so you can push the code from your local git repository to a remote repository for backup, sharing, deploying and more.

Watch the following videos to learn more about SSH Keys, Git, and Github

**VIDEO: SSH KEYS**

[![SSH Keys](http://img.youtube.com/vi/6u84sACs0v0/0.jpg)](http://www.youtube.com/watch?v=6u84sACs0v0 "SSH Keys")

**VIDEO: GIT AND GITHUB**

[![Git and Github](http://img.youtube.com/vi/L4zbgo7KFoA/0.jpg)](http://www.youtube.com/watch?v=L4zbgo7KFoA "Git and Github")

**Git Terminal Commands Reference**

<details>
<summary>
Reveal
</summary>
<p>

More commands here: https://dzone.com/articles/top-20-git-commands-with-examples

`git init` create a git repository in the current folder (never make a git repository inside another repository)

`git add -A` add all files to staging

`git commit -m "message here"` commit all files in staging

`git remote add remoteName remoteUrl` add a remote to push code too (Github or Git Enterprise), you can add as many remotes as you want

`git push remoteName branchName` push to code to the specified remote to the specified branch typically git push origin master

`git remote rm remoteName` remove a remote

`git log` see a log of commits

`git remote -v` see list of remotes

`git checkout -b newBranchName` create a new branch

`git checkout exisitingBranchName` switch a different branch

`git merge branchName` merge branch into your current branch

`git pull remoteName branchName` pull code from remote repo

</p>
</details>

---

## Github and Git Enterprise

Github.com should be where you store your unit projects and anything you plan on deploying (making live online).

git.generalassemb.ly (Git Enterprise) should be where your class repo is located and you turn in your homework.

Documentation will often be written in MarkDown a special basic language for writing a basic documents, watch the videos below to learn about remote repositories and using Markdown Files.

**VIDEO: GIT REMOTES**

[![Git Remotes](http://img.youtube.com/vi/TOsVVxXdtu8/0.jpg)](http://www.youtube.com/watch?v=TOsVVxXdtu8 "Git Remotes")

**VIDEO: Writing Markdown Files**

[![Writing Markdown Files](http://img.youtube.com/vi/lbpRomejEd0/0.jpg)](http://www.youtube.com/watch?v=lbpRomejEd0 "Writing Markdown Files")

Learn more about using Remote Repositories with the following lessons from Git Labs, highly recommend working through these brief quick lessons.

1. First Day on Github: https://lab.github.com/githubtraining/first-day-on-github

2. First Week on Github: https://lab.github.com/githubtraining/first-week-on-github

3. Managing Merge Conflicts: https://lab.github.com/githubtraining/managing-merge-conflicts

## VSCode

VSCode will likely be the main text editor you'll be using to edit your code throughout the cohort. Please watch the two videos below to become more familiar with VSCode and helpful extensions.

**VIDEO: VSCode Basics**

[![Visual Studio Code Basics](http://img.youtube.com/vi/Pf54xUgWzhc/0.jpg)](http://www.youtube.com/watch?v=Pf54xUgWzhc "Visual Studio Code Basics")

**VIDEO: VSCode Extensions**

[![Visual Studio Code Extensions](http://img.youtube.com/vi/eftHJZwHYTQ/0.jpg)](http://www.youtube.com/watch?v=eftHJZwHYTQ "Visual Studio Code Extensions")

**VSCode Shortcuts Reference**

<details>
<summary>
Reveal
</summary>
<p>

1. Shortcuts for Mac: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf

2. Shortcuts for Linux: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf

3. Shortcuts for Windows: https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf

</p>
</details>

---

## Node

Node is a runtime, it allows us to run javascript out of the browser which gives javascript a whole new life as a language for backend servers, scripting and more. Node will be used heavily through the cohort so watch the video below to learn how to use it.

**VIDEO: Intro to NodeJS**

[![NodeJS](http://img.youtube.com/vi/MifUZuRKrqg/0.jpg)](http://www.youtube.com/watch?v=MifUZuRKrqg "NodeJS")

**Node Terminal Command Shortcuts**

<details>
<summary>
Reveal
</summary>
<p>

`node filename.js` run the specified javascript file in the current folder

`npm init -y` create a new package.json file in the current folder

`npm install PackageName` install the specified package, add it to package.json file

`npm install` install all dependencies listed in the package.json file

`npm uninstall PackageName` uninstall the specified package

</p>
</details>

---

## Chrome

You may be fond of other browsers but Chrome by far has the most robust tools to assist in web development and will be the primary browser we'll use through out the course. Learning the dev tools will help debugging and overcoming roadblocks in your code much easier.

**VIDEO: INTRO TO Chrome Dev Tools**

[![Chrome Dev Tools](http://img.youtube.com/vi/Bx9bhPOxNZk/0.jpg)](http://www.youtube.com/watch?v=Bx9bhPOxNZk "Chrome Dev Tools")

## More Topics

Here you'll find other resources for other topics you may come across during the cohort. These can be examined at whatever time you feel appropriate to do so just make sure you explore the above videos about the tooling you'll be using during the cohort to give yourself the best foot forward.

- [HTML/CSS](/more/htmlcss.md)
- [Javascript](/more/js.md)
- [Python](/more/python.md)
- [Ruby](/more/ruby.md)
- [Go](/more/go.md)
- [PHP](/more/php.md)
- [Rust](/more/rust.md)
- [Swift](/more/swift.md)
- [Kotlin](/more/kotlin.md)
- [Perl 5 & Raku](/more/rakuperl.md)
- [Databases](/more/db.md)
- [Deployment](/more/deploy.md)
- [Other](/more/other.md)

## Contribute

If you have a resource or advice you'd like to contribute, submit it via a issue on this repository.
