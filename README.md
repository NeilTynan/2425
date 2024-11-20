# Computer Infrastructure Project Repository

This README has been written with [GitHub's documentation on README's] (https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) in mind.

## About this Project

This notebook contains my coursework and assignments for ATU module 2425 -- Computer Infrastructure. It includes both the weekly assignments and the overall project.

## Use of this Project

This repository may be of some interest to other students engaged in similar projects around computer infrastructure. Feel free to use whatever you like from it (though if another party has been referenced, I would ask that you likewise cite them).

## Getting Started

The workbook is structured in a linear fashion, so reading through it from start to finish is the best approach.

To understand how the workbook has developped to date, please see below a timeline of the work done on the notebook and the material referenced in the course of this work:

- **07/10/2024** - Created ReadMe and Gitignore file as per course materials: w02v03_create_your_repository. Gitignore file generated using the template at Python gitignore template at https://github.com/github/gitignore/blob/main/Python.gitignore, the Windows gitignore template at https://github.com/github/gitignore/blob/main/Global/Windows.gitignore, the MacOS gitignore template at https://github.com/github/gitignore/blob/main/Global/macOS.gitignore and the Linux gitignore template at https://github.com/github/gitignore/blob/main/Global/Linux.gitignore.
- **30/10/2024** - Created data directory and timestamp and weather sub directories (task 1) as per course materials: w04v03_mkdir_rm. Added "now.txt" file and appended timestamps to it (task 2) as per course materials: w05v03_redirect-View-only. 
- **08/11/2024** - Generated a file (formatted.txt) which included a formated timestamp and an empty file with the current timestamp for the file name (tasks 3 and 4) as per course material: w05v02_date. Downloaded two copies of today's weather data to create the "Today" and "20241108_114905.json" files (tasks 5 and 6) as per course materials: w06v01_wget and w06v02_wget_timestamps. Added a script, "weather.sh", to automate saving weather data to data/weather (task 7) as per course materials: w06v04_script.
- **10/11/2024** - Redid task 5, as it had the wrong filename. Completed task 8 by writing up the processes completed so far in a notebook. Task 9 was also completed in the same notebook and invovled loading in Met Eireann data into the notebook and examining it, as per course materials: w07v03_analyse. Started project work by by created a folder called ".github/workflows/" and a file called "weather-data.yml".
- **19/11/2024** - Completed Project, automating weather.sh script to run daily and push the new data to my repository. Course material referenced includes: w09v04_actions_attempt and w09v05_workflow_dispatch. A variety of other secondary materials were also referenced when it came to trying get the workflow to run correctly. These include: https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows (how to use crons).
- **20/11/2024** - Realised I accidently detached the HEAD of my commits from the main GitHub branch. Created a new branch and merged this with main to resolve this.


## Getting help

Queries about this repository can be directed directly to my GitHub account (NeilTynan).

## Other References

**HowtoDev**: *The "detached HEAD" state in Git: What it is and how to fix it* - https://how-to.dev/the-detached-head-state-in-git-what-it-is-and-how-to-fix-it (How to fix a detached head state).

**GitHub Actions**: *About Workflows* - https://docs.github.com/en/actions/writing-workflows/about-workflows (What the various steps involved in a workflow are and what they do)

## Author

I am student Atlantic Technological University's Higher Diploma in Data Science.   
