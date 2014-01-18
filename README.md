SublimeC0
=========

C0 for Sublime Text 2/3 that includes syntax highlighting &amp; simple build system

This is version 1.0 of the project. See Change Log for version differences.

[C0] (http://c0.typesafety.net) is a type safe imperative language created by [Frank Pfenning] (http://www.cs.cmu.edu/~fp/) and is being used for the course 15-122 at Carnegie Mellon University.

### Included in version 1.0 ###
- Syntax Highlighting (You should be able to open files with extensions ".c0" & ".h0" and get syntax highlighting)
- Simple Build System, runs currently on Linux. Pressing `Ctrl+B` will compile your file without including any option and will create an executable with the name of the file appened with `_test`

### To include in the future ###
- More elegant syntax highlighting
- Snippets
- Build System that works on Mac & Windows that allows the user to include libraries & options

Installation
============
There are 2 ways to install the C0 package. The 2 ways are:

### Using [Package Control] (http://sublime.wbond.net): ###

Make sure you have Sublime Text 2/3 installed and follow the steps below:

1. Install Package Control, follow instructions [here] (http://sublime.wbond.net/installation)
2. Press on **Tools > Command Palette** and search for **Install Package** then press **Enter**
3. Search for **C0**, you should find the package, then click **Enter** to install

You have installed the package, enjoy! 

### Clone the SublimeC0 Repository: ###

This way would require more work than using the Package Control but will be convenient for getting the latest updates. In this way, you need to clone the SublimeC0 repo to your "Sublime Packages" directly. This would allow you to get the latest updates when you just call `git pull`

**If you ever find issues with the package, please make sure to report. This package is new and issues are expected.**
