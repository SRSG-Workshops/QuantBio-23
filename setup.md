---
title: Setup for Computational Research Skills
---


# Version Control with Git

## Text Editor ##

A text editor is the piece of software you use to view and write code. If you
have a preferred text editor, please use it. Suggestions for text editors are,
Notepad++ (Windows), TextEdit (macOS), Gedit (GNU/Linux), GNU Nano, Vim.
Alternatively, there are IDE's (integrated developer environments) that have
more features specifically for coding such as VS Code; there are also IDEs
specific to languages will be listed in the appropriate section(s) below.

## Git Setup ##

### Windows
We'll be using Git Bash for both git and a shell to run it in. If you've already installed Git Bash then go to the next section. Otherwise, go to [git for windows](https://gitforwindows.org/) and click **Download**, then install it. 
Most of the options can be left on default, but be sure you check these:

- **Choosing the default editor used by Git:** Make sure **Nano** is selected from the drop-down. If you're comfortable with other editors, feel free to change it, but we recommend Nano - we use it as it's present on Windows, Mac *and* Linux. If you change it, you might not quite match what we're doing on-screen.
- **Adjusting your PATH environment:** Make sure **Git from the command line and also from 3rd-party software** is selected.
- **Choosing HTTPS transport backend:** Make sure **Use the native Windows Secure Channel Library** is selected.
- **Configuring the terminal emulator to use with Git Bash:** Make sure **Use Windows' default console window** is selected.

#### Mac OS
To use Git you must install the Apple Command Line Tools, this may take a few minutes.  

You can obtain these [from Apple](https://developer.apple.com/download/more/?name=command%20line%20tools%20for%20xcode%2012) (requires your Apple ID)

- Select **Command Line Tools for Xcode 12 (or higher)** and click the link to download the dmg archive.
- If prompted, choose to allow downloads from developer.apple.com
- Open the downloaded dmg archive from the Downloads folder
- Double-click the Command Line Tools.pkg icon to install

Alternatively, you can install the tools from the command line:

~~~
$ xcode-select --install
~~~
{: .language-bash}

#### Linux
Git comes pre-installed on most Linux distributions. You can test if it's installed by running `git --version`. 
If it's not installed, you can install it by running `sudo apt-get install git` or `sudo yum install git`, depending on 
your distribution.


## GitHub ##
We'll be using the website [GitHub](https://github.com/) to host, back up, and distribute our code. You'll need to [create an account there](https://github.com/signup). As your GitHub username will appear in the URLs of your projects there, it's best to use a short, clear version of your name if you can.


# Introductory Data Management with R

## Install R and RStudio ##

R is a programming language and software environment for statistical computing and graphics. The RStudio Integrated Development Environment (IDE) is a set of tools designed to help you be more productive with R.

We need to install R and RStudio: 
The latest links can be found on the [RStudio downloads page](https://www.rstudio.com/products/rstudio/download/#download)

### R

R can be found at [https://cran.rstudio.com/](https://cran.rstudio.com/), from here pick your OS and download the latest release, see below for direct links to your OS.

#### Windows
- [https://cran.rstudio.com/bin/windows/base/](https://cran.rstudio.com/bin/windows/base/)

#### Mac OS
- If prompted, choose to allow downloads from cran.rstudio.com.

- [https://cran.rstudio.com/bin/macosx/](https://cran.rstudio.com/bin/macosx/)
  - For intel based macs choose R-4.*.*.pkg
  - For ARM based macs (M1 etc.) choose R-4.*.*-arm64.pkg

#### Linux
- R is included on many linux distros check to see if it is already present. Else use your package manager (snap, apt, yum), or look [here](https://cran.rstudio.com/bin/linux/)


### RStudio

Your OS should be detected and a link provided under step 2 on this page [RStudio downloads page](https://www.rstudio.com/products/rstudio/download/#download).
Else select your OS from the list under All Installers.

#### Windows

Download and run the .exe file and follow instructions given by your OS.

#### Mac OS

Download the .dmg file.
- If prompted, choose to allow downloads from rstudio.com.
- Open the downloaded dmg archive from the Downloads folder.
- Drag the RStudio icon to the Applications folder to install.

#### Linux
Download the appropriate install file (.rpm or .deb) for your distro.