# CMPSC 100: Fall 2021, Week 0

* Distributed: 25 August 2021
* Due: 29 August 2021

---

<div class="alert alert-block alert-info">
    These various parts of this assignment are important for making progress in the course. The various point values of the components reflect this.
</div>

|Type         |Point value |
|-------------|------------|
|Activities   |20 pts.     |
|Lab          |10 pts.     |
|Participation|15 pts.     |
|             |            |
|Total        |55 pts.     |
|             |5.5% of course |

## Table of contents

---

### Week 0: Configuration

For those who just want to get to work, consult the `Instructional Materials` section. However, for folks who want to walk through activites with explanations, some context or history, and general folderol/frivolity, start at [Activities](#Activities).

* [Overview](#Overview)
* [Instructional materials](#Instructional-materials)
  * [Media](#Media)
  * [Activities](#Activities)
  * [Lab](#Lab)
* [The "terminal"](#The-"terminal")
  * [What is a "terminal"?](#What-is-a-"terminal"?)
  * [Using our terminal](#Using-our-terminal)
* [GitHub: Part 0](#GitHub:-Part-0)
  * [Activity 0: Securing your GitHub account](#Activity-0:-Securing-your-GitHub-account)
  * [Activity 1: "Cloning" a repository](#Activity-1:-"Cloning"-a-repository)
* [The terminal revisited](#The-terminal-revisited)
  * [Activity 2: Terminal commands](#Activity-2:-Terminal-commands)
* [Markdown](#Markdown)
  * [Activity 3: Basic markdown](#Activity-3:-Basic-markdown)
  
#### Lab: _The Maltese Python_ and submitting work

* [Lab: _The Maltese Python_](#Lab:-The-Maltese-Python)
* [Take a break](#Take-a-break)
  * [GatorGrader](#GatorGrader)
    * [Activity 4: Checking your work](#Activity-4:-Checking-your-work)
  * [GitHub: Part 1](#GitHub:-Part-1)
    * [Activity 5: "Committing" to a repository](#Activity-5:-"Committing"-to-a-repository)

## Overview

---

Starting the week, we explore setting up the tools, technologies, and platforms that will guide our work this semester. These include:

* The "terminal"
* GitHub
  * "Cloning" a repository
  * "Committing" a repository
* JupyterLab
* Markdown
* GatorGrader

We'll also start looking at the basic of the Python programming language with a couple of detours into how and why programming languages and computational systems work.

Follow the links below to access instructional materials for the week. Each `.ipynb` file is a `Jupyter notebook` (more on this later) which contains discussion, instruction, and activities -- some meant for use during class video sessions, others to be complete on your own. Simply double-click on it in the file tree to the right to open it in a new tab.

### Before we start

This week features a lot more "fiddly" parts than many of our upcoming weeks. This may require a bit more patience on your part; these steps are very important to having a successful class.

Of course, as will always be true throughout the semester, I am committed to making sure that these steps go as smoothly as possible and, where they might not, I will gladly offer assistance.

I give you my final prefatory note about assistance: **please do not hesitate to ask for it**. As I write in the course [Syllabus](https://github.com/allegheny-college-cmpsc-100-fall-2021/course-materials#syllabus):

> [h]istorically, students who are successful in my courses visit and discuss course concepts with the instructor and Technical Leaders early and often.

True, that.

## Evaluation

---

This assignment will be evaluated according to the following guidelines.

### Activity 3 - Markdown.md:

* Three (3) `heading`s
* Two (2) `list`s
* One (1) `image`
* One (1) descriptive paragraph

### Lab: _The Maltese Python_

* No `TODO` markers
* `the_maltese_python.png` placed in `cage/` folder`


### Overall `git` operations

* At least `5` total commits
  * You already have `3` because of GitHub Classroom -- you need to do at least `2` (more recommended!)

## Instructional materials

---

### Media

Click the images below the headers to launch videos.

#### SSH keys

[![YouTube thumbnail](https://i3.ytimg.com/vi/qEPjUGQFmzQ/hqdefault.jpg)](https://www.youtube.com/watch?v=qEPjUGQFmzQ)

#### Markdown

[![YouTube thumbnail](https://i3.ytimg.com/vi/s-oSuHFVnR4/hqdefault.jpg)](https://www.youtube.com/watch?v=s-oSuHFVnR4)

### Activities

* [Activity 0: Securing your GitHub account](activities/activity-0-ssh-keys.md)
* [Activity 1: "Cloning" a repository](activities/activity-1-github-clone.md)
* [Activity 2: Terminal commands](activities/activity-2-basic-terminal.ipynb)
* [Activity 3: Markdown](activities/activity-3-markdown.ipynb)
  * [Activity 3a: Markdown file](activities/activity-3a-markdown.md)
* [Activity 4: GatorGrader](activities/activity-4-gatorgrader.ipynb)
* [Activity 5: "Committing" to a repository](activities/activity-5-github-push.ipynb)

## The "terminal"

---

> [f]rom the mid 1970's to the mid 1980's, most people used real text-terminals to communicate with large computers....They consisted only of a screen, keyboard, and only enough memory to store a screenfull or so of text (a few kilobytes). Users typed in programs, ran programs, wrote documents, issued printing commands, etc. A cable connected the terminal to the computer (often indirectly). It was called a terminal since it was located at the terminal end of this cable.
>
> David S. Lawyer, [1.7 What is a Text-Terminal?](https://linux.die.net/HOWTO/Text-Terminal-HOWTO-1.html#ss1.7)

### What is a "terminal"?

The discussion above provides good history with an eye toward why we still use the word "terminal" to describe the interface we use to issue commands to a system. While we're not beholden to [room-sized computers anymore](https://en.wikipedia.org/wiki/UNIVAC), you're not exactly sitting in front of the server running any of the programs we use. Ergo, you need an interface that serves the same purpose as a historical "terminal": an "endpoint" used to issue different system or programming commands.

### Using our terminal

Whenever we're using JupyterLab, it's probably a good idea to have a terminal open, as we will see now and in the coming weeks.

There are two ways to launch a terminal in JupyterLab:

#### File menu

* From the `File` menu, select the `New` option
* In the resulting sub-menu, click `Terminal`

This will open a new tab for an active terminal.

#### Launcher tab

<div class="alert alert-block alert-warning">
  It's possible that you've closed your <b>Launcher</b> tab. In that case:
    <ul>
        <li>you can either launch the terminal from the <b>File</b> menu</li> 
        <li>or create a new <b>Launcher</b> from the same place</li>
    </ul>
</div>

* Locate the `Launcher` tab at the top of this window
* Under the `Other` heading, click the `Terminal` tile

This will open a new tab for an active terminal.

## GitHub: Part 1

---

GitHub is the platform that we're going to use to distribute and store our code.

### "Repositories"

Simply put, a "repository" is a collection of files and folders from a "snapshot" taken at a given point in time. This text is contained in such a repository. What's even better: repositories "remember" previous versions of themselves. In fact, you can _always_ go back and get a previous "snapshot".

We use a program called `git` to take and manage different versions of our files. `git` is referred to as a `Version Control System (VCS)`.

#### What is a "GitHub", then?

The quasi portmanteau "GitHub" is really what it says: a hub for `git` repositories. There are many other places on the internet that provide the service that GitHub does, but it's the largest such service out there.

(It has that sweet Microsoft money now.)

One of GitHub's services is something called GitHub Classroom -- a tool that allows me to create assignments, give them to you, and enables you to create your own complete copy of them in a [repository](#"Repositories").

### Activity 0: Securing your GitHub account

* [Activity 0 - Securing your GitHub account](activities/activity-0-ssh-keys.md)

### Worksheet 1: "Cloning" a repository

* [Activity 1 - "Cloning" a repository](activities/activities-1-github-clone.md)

## The terminal revisited

---

### Basic commands

In this course, you may learn some more handy terminal commands. However, we generally can get by with the following three (3):

* `cd`
* `ls`
* `pwd`

#### `cd`

* Stands for **c**hange **d**irectory
* Allows users to move "up" and "down" a file "tree"
  * Think: going from one place to another
* Easy way to remember: `I want to go to...`

#### `ls`

* Stands for **l**i**s**t
* Lists the contents of a directory
* Easy way to remember: `I want to look around.`

#### `pwd`

* Stands for **p**ath to **w**orking **d**irectory
* Shows the directory you're currently in
* Easy way to remember: `Where am I?`

### Worksheet 2: Terminal commands

The following worksheet provides some guided practice with these basic terminal commands.

* [Activity 2 - Terminal commands](activities/activity-2-basic-terminal.md)

## Markdown

---

While we are the Department of Computer Science, a large majority of our work is actually writing. For this (and documents like this one!) we use something called "Markdown."

The following worksheet introduces and provides an opportunity to practice with basic markdown.

### Worksheet 3: Markdown

* [Activity 3 - Markdown](activity/activity-3-markdown.md)

## Lab: _The Maltese Python_

---

![It's a fake!](https://cs.allegheny.edu/sites/dluman/cmpsc100/cmpsc-100-maltese-python.png)

> My way of learning is to heave a wild and unpredictable monkey-wrench into the machinery.
>
> Dashiell Hammett, _The Maltese Falcon_

In 2021 a professor attempted to boggle their students' minds by sending them a game in which they hid a Golden Python whose scales were conjured from digital text—an enterprising computer system seized this priceless token and the fate of the Maltese Python remains a mystery to this day...

It is hidden somewhere in the `/mansion`, but it is up to _you_ to find and `claim` it.

* [Lab: _The Maltese Python_](lab/week-0-lab.ipynb)

## Take a break

---

Well, after this -- knowing that the first half of your work is submitted.

### GatorGrader

GatorGrader is an automated tool that allows you to grade your assignments according to specifications that I set out in the [grading criteria](#Grading-criteria). The following worksheet teaches you how to run it:

#### Worksheet 4: Checking your work

* [Activity 4 - GatorGrader](activities/activity-4-gatorgrader.md)

### GitHub: Part 1

The final step in turning or saving assignments is to `commit` (or `push`) the content to GitHub. Complete the steps in the following worksheet to learn how to complete the process.

#### Worksheet 5: "Committing" to a repository

* [Activity 5 - "Committing" to a repository](worksheets/activity-5-github-push.md)

#### A strong warning

<div class="alert alert-block alert-danger">
    <p><strong>While we may use this server to store code, <u>you</u> are responsible for using GitHub as your main backup.</strong></p>
    <p>While I back this server up on a regular basis, I cannot guarantee that I'll have the ability to restore up-to-the-minute data for your work.</p>
    <p>Remember: to err is human; to back up your work is divine.</p>
</div>
