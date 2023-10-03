Reading questions

Project workflows
Bryan (2017)

#What problems can setwd() cause in your scripts and how do RStudio projects address them?

It can make scripts localized to your machine - scripts will ONLY run on your machine, which immediately makes your script non-reproducible. RStudio addresses this problem by hosting all data in the same folder, which is also linked to an online repository which others can access. 

#When you call rm(list=ls()), what is removed from your environment? What’s left over that restarting your R session would remove? What’s the keyboard shortcut for restarting your R session?

It creates the illusion of working with a blank space, but this is not the case. It removes user-created objects, but does not remove oackages, or sometimes working directories. Command+Shift+F10 is the keyboard shortcut for restarting an R session.

Version control
You either read Bryan (2018) or Braga et al. (2023). Answer the questions for the paper you read.

Bryan (2018)

The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? Which happen remotely?

Commit and pull happens locally, push happens remotely

Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)?

Word docs are binary files which are too complex(??) for Git to use for merges

Why is Markdown useful for GitHub repos?

It puts all of the code in an easily digestible format

Braga et al. (2023)

Imagine you’re working with a few collaborators on an analysis. Come up with two examples of Issues you might open. How would using Issues differ from communicating over email?
What are three ways GitHub features can promote open science practices?