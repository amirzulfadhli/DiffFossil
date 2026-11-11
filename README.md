# DiffFossil

A Git history analysis tool built to help developers understand how their code changes over time 

DiffFosil is a command line application designed to make exploring commit history, comparing versions and identifying frequenlt modified files easier

## About the Project

When working on a software project, developers make many commits as tjey add features, fix bugs or update existing code. Over time, it can become difficult to understand which parts of the proejct have changed the most.

Git already provides commands such as git log and git diff, but reviewing large amounts of history manually can be time consuming.

DiffFosil aims to make this process easier by organizing Git history into useful statistics and reports.

The goal is to make repository history easier to explore, especially for students and developers who want to understand their projects better.

## Planned Features

### Git History Exploration

1. Read the commit history of a local Git repository
2. Display commit information such as hash, author, date and message
3. Show files changed in a selected commit
4. Inspect the history of an individual file

### Version Comparison

1. Compare two commits, branches or tags
2. Identify files added, modified or deleted between selected versions
3. Show the number of lines added and removed
4. Summarize the overall changes between two versions

### File Change Analysis

1. Count how frequently files have been modified
2. Calculate code churn using lines added and deleted
3. Rank files by change frequency or code churn
4. Identify potential change hotspots that may need closer inspection

### Reports and Filtering

1. Display readable results in the terminal
2. Filter analysis by file or selected commit range
3. Generate summaries of repository activity
4. Export analysis results to CSV files

### Repository Safety

1. Analyze local repositories without changing their contents
2. Use read only Git operations for history inspection
3. Display clear error for invalid repository paths or Git references

//All features are currently planned and have not yet been inplemented

### Tech Stack

| Technology | Purpose |
| --- | --- | 
| Python | Main application logic and data processing |
| Git | Reading repository history and comparing versions |
| Python library | Command line arguments, running Git commands and file handling |
| CSV | Exporting analysis results |
| unittest | Automated testing | 
| Git & Github | Version control and project documentation | 

//Tech stack may change as developement progresses

## How it Works

1. The user opens DiffFosil and provides the path to a local GIt repository
2. DiffFosil checks wether the selected folder is a valid Git repository
3. The user chooses an analysis option, such as history, comparison or hotspots
4. DiffFossil reads the required commit and file information from Git
5. The application processes the results into useful statistics
6. The analysis is displayed in the terminal
7. The user can optionally export the result to a CSV file

## Installation and Running the Project 

Status: not yet available

## Planned Requirements

- Python 3 (version to be confirmed)
- Git
- A local Git repository
- A terminal/command prompt

## Planned Developement Setup

1. Clone the DiffFossil repository
2. Open the project directory
3. Check that **Python** and **Git** are installed
4. Run the application using the configured developement command
5. Select a repository and an analysis option

//The exact commands and tested installation instruction will be added after a working version is available

## Developement Journey

### Planned Developement Milestones

| Phase | Developement Work | Estimated Hours |
| --- | --- | --- |
| 1 | Planning, README, requirements | 1h |
| 2 | Project structure and Git integration | 2h |
| 3 | Commit history reader | 2h |
| 4 | Version comparison | 3h |
| 5 | File history and code churn analysis | 4h |
| 6 | Hotspot detection & ranking | 3h |
| 7 | CLI commands and filtering | 3h |
| 8 | CSV report export | 2h |
| 9 | Testing and debugging | 3h |
| 10 | Final testing, documention release | 2h |

//These are estimated planning target, Actual sessions will be recorded separately

## Challenges and Lessons learned

This section will document real problems encountered during developement, including Git parsing issues, debugging, design decisions, unsuccessful approaches and improvements

## Screenshots and Demo

Screenshots and GIFs showing the tool's working analysis results will be added once the features are implemented

## Project Scope

The inital focuses on analyzing the history of local Git repository throught a command line interface

Features outside the initial scope:

- Graphical desktop interface
- GitHub/GitLab accound integration
- Cloud synchronization
- Automatic code modification or repository cleanup
- AI based code reviews or code quality scoring
- Team analytics dashboards

## Future Improvements 

Possible improvements after the initial version:

- Visual charts for commit activity and code churn
- A timeline showing how individual files evolved
- Support for more advanced filtering options
- Export formats such as JSON or HTML
- Better handling and visualisation of renamed files
- Comparison of change patterns across branches

//These are potential additions, not implemented features

## AI disclosure

AI assistance was used to help organize project plan, suggest initial scope and tech stack and help me wording

Developement, implementatiom, debugging and testing will be complete by myself. Documentation will be revised in my own words

This disclosure will be updated to accurately describe any additional AI assistance during the project developement/implementation

## Project Goal 

Create a functional Git history analysis tool that helps developers understand how their repositories change while learning about Git internals, command line application developement, data processing, testing and generating useful software reports