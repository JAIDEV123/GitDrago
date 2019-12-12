# GitDrago

Custom built version control implemented in Python.
This was done purely to gain a better uunderstanding of how git works. By using `./drac` followed by the git command. 

## Acknowledgment

GitDrago was made by following this ![tutorial](https://wyag.thb.lt/#orgdefb891). To get a better understanding of the different areas that git usesm- Working, Staging, and Repository, I found ![this](https://hackernoon.com/understanding-git-index-4821a0765cf) to be quite helpful as it illustrates the relation between index, objects and refs quite concisely.

## libdrac.py

All git commands and the logic behind them is contained in this file. It parses arguments, computes keys, and manages the repository. Follow the tutorial to get a better understanding of how the code works. In brief, there are classes for the repository, and various objects such as blob, tree, commit, and tag. Operations on these classes mimic the flow of information in a regular git workflow.

Branching is one critical git feature that hasn't been implemented but can be extended by using tags which are pointed to be refs.

