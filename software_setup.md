# Setup

To participate in this course, you will need access to the software described below. In addition, you will need an up-to-date web browser. I recommend [Google Chrome](https://www.google.com/chrome/).

Once you've installed all of the software below, test your installation by following the instructions at the bottom on this page.

## 1. The Bash Shell

Bash is a commonly-used shell that gives you the power to do simple tasks more quickly. Due to time constraints, I will cover Bash very briefly in this course but don't go into it in-depth. 

#### Windows

Install Git for Windows by downloading and running the [installer](http://msysgit.github.io/). This will provide you with both Git and Bash in the Git Bash program. **NOTE**: on the ~6th step of installation, you will need to select the option "Use Windows' default console window" rather than the default of "Use MinTTY" in order for nano to work correctly.

After the installer does its thing, it leaves the window open, so that you can play with the "Git Bash".

Chances are that you want to have an easy way to restart that Git Bash. You can install shortcuts in the start menu, on the desktop or in the QuickStart bar by calling the script /share/msysGit/add-shortcut.tcl (call it without parameters to see a short help text).

If you receive an "xcrun" error message, take a look at https://stackoverflow.com/questions/32893412/command-line-tools-not-working-os-x-el-capitan-macos-sierra-macos-high-sierra/32894314#32894314.

However, GitBash is limited to Git related commands. Therefore, I strongly recommend also installing [Windows Subsystem](https://docs.microsoft.com/en-us/windows/wsl/).

#### Mac OS X

The default shell in all versions of Mac OS X is bash, so no need to install anything. You access bash from the Terminal (found in `/Applications/Utilities`). You may want to keep Terminal in your dock for this class. If you want to something advanced, then try [ZSH](https://ohmyz.sh/) (optional).

#### Linux

The default shell is usually Bash, but if your machine is set up differently you can run it by opening a terminal and typing bash. There is no need to install anything.

## 2. Git

Git is a version control system that lets you track who made changes to what when and has options for easily updating a shared or public version of your code on github.com. You will need a supported web browser (current versions of Chrome, Firefox or Safari, or Internet Explorer version 9 or above).

#### Github account

I highly recommend to create your [github](https://github.com/) account. Also, seriously consider signing up for [the GitHub Student Developer Pack](https://education.github.com/pack/join). You can use an advanced git account either for free or discounted price.

#### Windows

Git should be installed on your computer as part of your Bash install (described above).

#### Mac OS X

**For OS X 10.9 and higher**, install Git for Mac by downloading and running the most recent "mavericks" installer from [this list](http://sourceforge.net/projects/git-osx-installer/files/). After installing Git, there will not be anything in your `/Applications` folder, as Git is a command line program. **For older versions of OS X (10.5-10.8)** use the most recent available installer labelled "snow-leopard" available [here](http://sourceforge.net/projects/git-osx-installer/files/).

#### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager. For Debian/Ubuntu run sudo apt-get install git and for Fedora run sudo yum install git.

## 3. R

[R](http://www.r-project.org/) is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. To interact with R, we use [RStudio](http://www.rstudio.com/).

#### Windows

Install R by downloading and running [this .exe file from CRAN](http://cran.r-project.org/bin/windows/base/release.htm). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). All you need is RStudio Desktop.

#### Mac OS X

Install R by downloading and running [this .pkg file from CRAN](http://cran.r-project.org/bin/macosx/R-latest.pkg). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). All you need is RStudio Desktop. Please note that if you already have R and update to a newer version, you will have to reinstall any previously installed packages.

#### Linux

You can download the [binary files](http://cran.r-project.org/index.html) for your distribution from CRAN. Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo yum install R`). Also, please install the [RStudio IDE](http://www.rstudio.com/ide/download/desktop). All you need is RStudio Desktop.

## 4. Pandoc and Latex

Pandoc is a universal document converter. It can be used to convert scripts (like in jupyter notebooks) into pdfs for assignments. For PDF output, you’ll also need to install LaTeX, a type-setting system. We recommend that you do the MacTex full install.

#### Windows
Install Pandoc and Latex using the instructions [here](http://pandoc.org/installing.html).

#### Mac OS X
Install Pandoc and Latex using the instructions [here](http://pandoc.org/installing.html).

#### Linux
Install Pandoc and Latex using the instructions [here](http://pandoc.org/installing.html).

## Testing your installation

If you have trouble with installation, please leave a message in the #software-installation channel of the Slack workspace. The TA will consult with you.

Open a command line window ('terminal' or, on windows, 'git bash'), and enter the following commands (without the $ sign):

```bash
$ R --version
$ git --version
$ pdflatex --version
$ pandoc --version
```

If the software have been installed properly, those commands *should* print output version information.

**NB**: If you're using git bash (Windows), the `R --version` command may not work. In this case, just make sure you can open up RStudio. One possible solution: The Software Carpentry installer may need to run as Administrator. (Right click the install app, select “Run as administrator”).

This should open a programming interface in your default web browser. It may take a few minutes the first time. To close, just close your browser and then `CTRL-C` to end the process in the command line.

Software Carpentry maintains a list of common issues that occur during installation may be useful for our class here: [Configuration Problems and Solutions wiki page.](https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions)

Credit: Thanks to [Software Carpentry](http://software-carpentry.org/workshops/) for providing installation guidelines.
