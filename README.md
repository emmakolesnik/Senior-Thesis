# Introduction

This is a collection of code explicitly calculating the stationary distribution of the recombination Markov chain. It will also calculate the mixing time for a graph. Other analysis and graph analysis functions can be found at https://github.com/CMC-Summer-Research-2020/stationary-distribution-recom

# Files 
## Mixing Time.py
This code finds the stationary distribution for any size graph divided into any number of equal districticts and can also calculate the mixing time of any size graph. 
### Requirements
In order to memoize our code we use:
https://pypi.org/project/memoization/
```bash
pip install memoization
```
In order to transform jsons into nx graphs to create state graphs from https://github.com/vrdi/vrdi-graphs you need to install:
https://gerrychain.readthedocs.io/en/latest/
```bash
pip install gerrychain
```
## Graphs
These are the pickled files for all 9, 12, 15,and 16 vertex graphs I used in my analysis

## Spreadsheets
Each spreadsheet is titled after the size graph it contains data for. In a spreadsheet, every sheet contains information for a particular graph. They correspond numerically to the pickled files. In each sheet, each column represents a different starting point and each row is the total variation distance at each step of recombination.

# Authors and acknowledgment
Author: Emma Kolesnik

Senior thesis with the Department of Mathematicsat at Scripps College
Advisor: Professor Sarah Cannon, Claremont McKenna College

