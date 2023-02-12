# Linear-Search-Algorithm

## Introduction
This program is an implementation of a Linear Search algorithm, which is used to search for a specific item in a list of items. The program has two classes, Environment and Agent. The Environment class is responsible for creating a list of files and selecting one of the files randomly to be searched for by the Agent. The Agent class performs the linear search, which involves comparing each item in the list to the target item, one by one, until the target is found.

## Usage
The program can be run from the command line by executing the script. The script does the following:

Imports the os and random modules.
Creates an instance of the Environment class and initializes the filelist attribute, which is a list of files in the specified directory. The target file to be searched for is selected randomly from this list and stored in the agentfind attribute.
Creates an instance of the Agent class and initializes the count attribute to 0. The count attribute keeps track of the number of iterations it takes to find the target file in the filelist.
The program performs 20 trials of the linear search and stores the results of each trial in the performance list.
The average search time is calculated and printed to the console.
A plot of the performance list is generated and displayed, showing the journey of the agent over time.
