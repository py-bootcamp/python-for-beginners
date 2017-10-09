# Things you need to have before starting this workshop

1. A computer
2. [Python and Anaconda](#installing-python-and-anaconda)
3. [Visual Studio Code](#installing-visual-studio-code)
4. [A Github account](#create-a-github-account)
5. [Git](#installing-git)

Now you are ready 👍

## Installing `Python` and `Anaconda`
---

[`Python`](http://python.org/) is a popular language for research computing, and great for general-purpose programming as well.
You could probably have it already installed but we need some more libraries.

The shorter way to install all of them is to use the [Anaconda distribution](https://www.continuum.io/anaconda), is a collection of libraries and a packet manager, an all-in-one installer.

You can find a version for Windows, Mac OSX and Linux.

**Regardless of how you choose to install it, please make sure you install Python version 3.6**.

We will teach `Python` using the [`Jupyter Notebook`](http://jupyter.org/), a programming environment that runs in a web browser. For this to work you will need a reasonably up-to-date browser. The current versions of the Chrome, Safari and Firefox browsers are all supported (some older browsers, including Internet Explorer version 9 and below, are not).

---

### Windows

[Video tutorial](https://www.youtube.com/watch?v=xxQ0mzZ8UvA)

1. Open http://continuum.io/downloads with your web browser.
2. Download the `Python 3.6` installer for Windows.
3. Install `Python 3` using all of the defaults for installation except make sure to check **Make Anaconda the default Python**.

---

### Mac OSX

[Video tutorial](https://www.youtube.com/watch?v=TcSAln46u9U)

1. Open http://continuum.io/downloads with your web browser.
2. Download the `Python 3.6` installer for OS X.
3. Install `Python 3` using all of the defaults for installation.

---

### Linux

1. Open http://continuum.io/downloads with your web browser.
2. Download the `Python 3.6` installer for Linux.
3. Install `Python 3` using all of the defaults for installation. (Installation requires using the shell. If you aren't comfortable doing the installation yourself stop here and request help at the workshop.)
4. Open a terminal window.
5. Type:
~~~
bash Anaconda3-
~~~
and then press tab. The name of the file you just downloaded should appear.

6. Press enter. You will follow the text-only prompts. When there is a colon at the bottom of the screen press the down arrow to move down through the text. Type yes and press enter to approve the license. Press enter to approve the default location for the files. Type yes and press enter to prepend Anaconda to your PATH (this makes the Anaconda distribution the default `Python`).

---


## Installing Visual Studio Code
---

There are many editors available, some of them specifically just for Python.
We decided to use [Visual Studio Code]()https://code.visualstudio.com/download

**Please come with this editor installed, otherwise we won't be able to support you if you will have problems.**.

---

### Windows

1. https://code.visualstudio.com/download with your web browser.
2. Download the `Windows` installer.
3. Follow the instructions.
4. Open VSC (Visual Studio Code) to check if the program is correctly installed.

---

### Mac OSX

1. Open https://code.visualstudio.com/download with your web browser.
2. Download the `Mac` installer.
3. Follow the instructions.
4. Open VSC (Visual Studio Code) to check if the program is correctly installed.

---

### Linux

1. Open https://code.visualstudio.com/download with your web browser.
2. Download the installer for Linux.
3. You have 3 ways to install Visual Studio Code on linux, depending from your distribution.
4. Open VSC (Visual Studio Code) to check if the program is correctly installed.

---


## Create a github account
---

You need to have a [github.com](https://github.com/join?source=login) account. Creating an account is for free. You will need to use the same email and password you used during the course, so please rememeber them 👍.

## Installing Git
---

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on github.com. You will need a supported web browser (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 or above).

---

### Windows

[Videotutorial](https://www.youtube.com/watch?v=339AEqk9c-8)
1. Download the [Git for Windows installer](https://git-for-windows.github.io/).
2. Run the installer and follow the steps bellow:
    1. Click on "Next".
    2. Click on "Next".
    3. Keep "Use Git from the Windows Command Prompt" selected and click on "Next".
    If you forgot to do this programs that you need for the workshop will not work properly. **If this happens rerun the installer and select the appropriate option.**
    4. Click on "Next".
    5. Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
    6. Keep "Use Windows' default console window" selected and click on "Next".
    7. Click on "Install".
    8. Click on "Finish".
3. If your "HOME" environment variable is not set (or you don't know what this is):
    1. Open command prompt (Open Start Menu then type cmd and press [Enter])
    2. Type the following line into the command prompt window exactly as shown: setx HOME "%USERPROFILE%"
    3. Press [Enter], you should see SUCCESS: Specified value was saved.
    4. Quit command prompt by typing exit then pressing [Enter]
This will provide you with both Git and Bash in the Git Bash program.

---

### Mac OSX

[Video Tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY)
For OS X 10.9 and higher, install Git for Mac by downloading and running the most recent "mavericks" installer from [here](https://git-scm.com/download/mac) After installing Git, there will not be anything in your /Applications folder, as Git is a command line program. For older versions of OS X (10.5-10.8) use the most recent available installer labelled "snow-leopard" available here.

---

### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run sudo apt-get install git and for Fedora run sudo yum install git.

---


If something went wrong, breath, relax, prepare a good coffee and send us an email: **hello@pybootcamp.com**

This installation tutorial is based on [Software Carpentry](http://swcarpentry.github.io/workshop-template/#setup).