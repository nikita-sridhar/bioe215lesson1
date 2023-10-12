Avoid using setwd() and rm(list = ls()) as this prevents code from being reproducible

Use good project file organization, with subfolders (i.e. data, docs, figs, output, paper, R, reports, scratch) within a root directory. The root directory contains the .Rproj file.

Use Github to track changes to code and to make it easier to have a one-click script, and to make it easier to share code. Regularly commit to update changes made (with explanations for the changes) locally to your computer, and push to update those remotely. Use the pull command if multiple people are working on a project, to locally obtain changes others made to the script.

Use RMarkdown to easily generate a report that can be easily updated with code and figures.

Things to only do once on your system:
Install Git, create a token (update once every 90 days)

Things to do before each project:
Create an R Project with GitHub repository in R Studio 
usethis::use_git() > commit all uncommitted files > usethis::git_default_branch_rename() > usethis::use_github(). this should make git and R speak to each other
Set up folder structure in root folder
Activate GitHub pages to create a report that you can easily update. to do this, go on github website, under your repo, settings, pages, code and automation, change branch from none to main.




