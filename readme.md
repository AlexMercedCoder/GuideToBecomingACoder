# So You Want to Become a Coder
### by Alex Merced (AlexMercedCoder.com)

## Welcome

Welcome! If you are reading this you are considering becoming a coder. Below you'll find lots of resources to learn about the world of coding.

### Start Here

I recommend a few steps, the first being to try to do the free lessons at General Assemblies Dash Platform. This is a great low-risk way to get a feel for what you are getting into before you decide to learn more by doing a Bootcamp at General Assembly (Where I teach) or on your own.

- [General Assemblies Dash](https://dash.generalassemb.ly/)

I also recommend watching this video where I breakdown the many career paths and technologies in development.

<center>

[![Becoming a Developer](http://img.youtube.com/vi/abKUWOldphg/0.jpg)](http://www.youtube.com/watch?v=abKUWOldphg "Becoming a Developer")

</center>

The below blog post should contain a lot of useful reference during your journey. 

**Ultimate Coder Reference REFERENCE POST**: https://tuts.alexmercedcoder.com/basicref/

After deciding what path you want to go down the next step would be choosing which language learn first. Depending on your path here is my recommendations...

- Frontend Web: HTML/CSS/Javascript
- Backend Web: Javascript and literally any language (they all have web frameworks)
- Data: Python
- iOS: Swift
- Android: Kotlin
- Enterprise: .NET, Java
- Systems: Rust, Go

**NOTE:** This guide is primarily geared towards web but should still be able to be a solid starting place for any path. Next will be a discussion of tooling, guides for particular languages can be found afterwards.

# The Tools

Below you'll find resources on many of the main tools you'll need as you explore the world of development. Don't underestimate the importance of having a good appreciation for your tooling to help you become a better coder so take the time to get familiar with the tools below.

## Bash (Terminal)

Bash is the default shell environment in unix based systems (Technically, Zsh is the default on mac, but the commands are pretty much the same). Windows is not a unix based system which is why they aren't as heavily used in development shops unless they are .NET which is a windows stronghold. To be able to have a Bash terminal or Unix environment on your windows machine below are some options.

**Solutions for Windows Users**

<details>
<summary>
Reveal
</summary>
<p>

1. Install Xubuntu (https://xubuntu.org/) as a second operating on your machine (This is in my opinion the best option and a tutorial how to do so is here: https://www.lifewire.com/guide-to-installing-xubuntu-linux-2202075)

2. Use Windows Subsystem for Linux to have a Linux environment in your windows install (here is a tutorial => https://www.windowscentral.com/install-windows-subsystem-linux-windows-10 )

3. Install Xubuntu into a virtual machine using VirtualBox (tutorial: https://lmtools.com/setup-ubuntu-virtual-machine-in-windows-using-oracle-virtualbox )

4. Just use windows but install git-bash to have access to a bash shell in your windows file system, it's not exactly the same and will have minor differences along the way. (https://gitforwindows.org/)

</p>
</details>

---

Watch this video to understand how to use the Bash shell to explore your file system.

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

Github.com, Bitbucket.com, and Gitlab.com are hosts of remote repositories where you can store your local repositories for backup, sharing or collaboration.

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

## Github

Github.com, Bitbucket.com, and Gitlab.com are hosts of remote repositories where you can store your local repositories for backup, sharing or collaboration.

Documentation will often be written in MarkDown, a special markup language for writing basic documents, watch the videos below to learn about remote repositories and using Markdown Files.

**VIDEO: GIT REMOTES**

[![Git Remotes](http://img.youtube.com/vi/TOsVVxXdtu8/0.jpg)](http://www.youtube.com/watch?v=TOsVVxXdtu8 "Git Remotes")

**VIDEO: Writing Markdown Files**

[![Writing Markdown Files](http://img.youtube.com/vi/lbpRomejEd0/0.jpg)](http://www.youtube.com/watch?v=lbpRomejEd0 "Writing Markdown Files")

Learn more about using Remote Repositories with the following lessons from Git Labs, I highly recommend working through these brief quick lessons.

1. First Day on Github: https://lab.github.com/githubtraining/first-day-on-github

2. First Week on Github: https://lab.github.com/githubtraining/first-week-on-github

3. Managing Merge Conflicts: https://lab.github.com/githubtraining/managing-merge-conflicts

## VSCode

VSCode is a popular text editor for editing code files, watch the video below to learn about how to use VSCode.

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

Node is a runtime, it allows us to run javascript out of the browser which gives javascript a whole new life as a language for backend servers, scripting and more.

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

You may be fond of other browsers but Chrome by far has the most robust tools to assist in web development. Learning the Chrome dev tools will help make debugging and overcoming roadblocks in your code much easier.

**VIDEO: INTRO TO Chrome Dev Tools**

[![Chrome Dev Tools](http://img.youtube.com/vi/Bx9bhPOxNZk/0.jpg)](http://www.youtube.com/watch?v=Bx9bhPOxNZk "Chrome Dev Tools")

# More Topics

Below you'll find guides for learning particular languages and topics, enjoy!

- [HTML/CSS](/more/htmlcss.md)
- [Javascript](/more/js.md)
    - [Frontend JS](/more/js/frontend.md)
    - [Backend JS](/more/js/backend.md)
- [Python](/more/python.md)
- [Ruby](/more/ruby.md)
- [Go](/more/go.md)
- [PHP](/more/php.md)
- [Rust](/more/rust.md)
- [Swift](/more/swift.md)
- [Kotlin](/more/kotlin.md)
- [Perl 5 & Raku](/more/rakuperl.md)
- [Java](/more/java.md)
- [.Net](/more/dotnet.md)
- [Databases](/more/db.md)
- [Deployment](/more/deploy.md)
- [Computer Science](/more/cs.md)
- [Other](/more/other.md)
- [Self-Teaching Rubrics](https://github.com/AlexMercedCoder/self_learning_rubrics)

## Contribute

If you have a resource or advice you'd like to contribute, submit it via a issue on this repository.
