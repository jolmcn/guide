# Git, Python & Conda Guid

## Git

### Overview
Git is a version control system. It allows you to store code online and to move back and forward between older an newer versions of your code. 


Version control with Git goes something like this:
- A **Git Repository** is the name for a single project. **Repo** is the short name. 
- You can create a new **Git Repo** locally on your computer or using your Github/Gitlab account.
- You can download a **Repo** as a zipped folder directly, or you can *clone* it to your computer using either the terminal/command line or a GUI application. 
- Changes made to the downloaded (local) version of the **Repo** will not affect the version stored online until you *commit* and *push* your changes.
- Changes can be pushed to the **Master** branch of your **Repo** or to a new branch.
- You can switch easily between your **Master** branch and other created branches.
- Any changes you push can usually be reversed by *rolling back* to a previous *commit*.
- When working with a **repo** created by another Git user, you can create a  *fork* of the **repo**, essentially a copy of the **repo** on your own Git account that you can edit.
- When multiple people are working on a single **repo**, changes created on new branches can be **merged** into the *master* branch.
- This might not all be clear now, you will likely not need to use all of these functions! See **Use** section below for instructions on how to *clone* a **repository**, and how to *add*, *commit* and *push* changes.


### Installation

#### Prerequisites

Create an account on [GitHub](http://github.com/)

#### PC

##### Command Line Version
- [Download](https://git-scm.com/download/win) and install.
	- This is what I tend to use. It comes with a dedicated command line application called Git Bash to run Git commands (e.g. *commit*, *add*, *clone*, etc).
	- **NOTE:** Even if you plan to use the GUI version below, I recommend downloading these tools. I have found that the GIT Bash terminal useful for Python and Conda (see below).

##### GUI Version
- [Download](https://desktop.github.com/) and install.
	- This is a desktop app created by GitHub. It will allow you to do all the same things you can do in the command line version but with a graphical interface that is useful for more easily seeing the changes made to your repo.


#### Mac

##### Command Line Version
1. Install *[Homebrew](https://brew.sh/)* using the following steps:
	* Open the *Terminal* application on your Mac
	* Copy and paste the following into the terminal window, then press enter:
	``` 
	/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
 	```
2. Install Git using Homebrew
	* When Homebrew has finished installing, copy and paste the following into the terminal window, then press enter:
	```
	brew install git
	```

##### GUI Version
- Same as Windows! [Download](https://desktop.github.com) and install.

### Use

#### Creating a Repo
1. Go to [Github](https://github.com)



## Python

### Overview

Python is a popular, high-level coding language used widely in Machine Learning and AI applications, to name just a few contexts. Most ML projets will require you to run a Python program and/or download some other Python libraries. There are a number of different ways to download existing Python libraries.

### Installation

#### PC

#### Mac

### Use


## PIP

### Overview

**PIP** is the standard package management system for Python. In other words, it is the default tool for installing existing Python libraries. Unless you have created a local environment (e.g. using Miniconda - see below), libraries/packages installed with PIP will be installed globally on your computer.

### Installation

#### PC

#### Mac

### Use


## CONDA

### Overview

Anaconda/Miniconda is a platform for creating enclosed environments for running Python projects. 

Conda allows us to run multiple projects on the same computer with different versions of Python or different versions of specific Python packages. Many existing repos on Github will require different versions of Python or specific Python packages, and Conda can allow us to run these projects more easily.

### Installation

#### PC

#### Mac

### Use
