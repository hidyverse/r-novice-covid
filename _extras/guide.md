---
title: "Instructor Notes"
---

## Timing

Leave about 30 minutes at the start of each workshop and another 15 mins
at the start of each session for technical difficulties like WiFi and
installing things (even if you asked students to install in advance, longer if
not).

## Lesson Plans

* 01 Introduction to Cyverse, R, and RStudio
* 02 Project Management With RStudio + 03 Seeking Help
* 04 Data Structures

## Setting up git in RStudio

There can be difficulties linking git to RStudio depending on the
operating system and the version of the operating system. To make sure
Git is properly installed and configured, the learners should go to
the Options window in the RStudio application.

* **Mac OS X:**
  * Go RStudio -> Preferences... -> Git/SVN
  * Check and see whether there is a path to a file in the "Git executable" window. If not, the next challenge is figuring out where Git is located.
  * In the terminal enter `which git` and you will get a path to the git executable. In the "Git executable" window you may have difficulties finding the directory since OS X hides many of the operating system files. While the file selection window is open, pressing "Command-Shift-G" will pop up a text entry box where you will be able to type or paste in the full path to your git executable: e.g. /usr/bin/git or whatever else it might be.
* **Windows:**
  * Go Tools -> Global options... -> Git/SVN
  * If you use the Software Carpentry Installer, then 'git.exe' should be installed at `C:/Program Files/Git/bin/git.exe`.

To prevent the learners from having to re-enter their password each time they push a commit to GitHub, this command (which can be run from a bash prompt) will make it so they only have to enter their password once:

~~~
$ git config --global credential.helper 'cache --timeout=10000000'
~~~
{: .bash}

## Pulling in Data

The easiest way to get the data used in this lesson during a workshop is to have
attendees access data from within Cyverse by searching "r-novice-covid" and selecting "daily_summary.csv". Rather, one may download the raw data from [ReDATA](https://arizona.figshare.com/articles/dataset/University_of_Arizona_Test-Trace-Treat_COVID-19_testing_results/14869740) by clicking `Download all`.


## Overall

Make sure to emphasize good practices: put code in scripts, and make
sure they're version controlled. Encourage students to create script
files for challenges.

If you're working in a cloud environment, get them to upload the
data after the second lesson.

Be sure to actually go through examples of an R help page: help files
can be intimidating at first, but knowing how to read them is tremendously
useful.

Don't worry about being correct or knowing the material back-to-front. Use
mistakes as teaching moments: the most vital skill you can impart is how to
debug and recover from unexpected errors.

[covid-data-link]: https://arizona.figshare.com/articles/dataset/University_of_Arizona_Test-Trace-Treat_COVID-19_testing_results/14869740
