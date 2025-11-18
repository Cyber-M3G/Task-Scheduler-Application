# Task-Scheduler-Application
This project implements a Python-based task scheduling system designed to improve productivity by organising tasks according to priority. Tasks are stored using an appropriate data structure to ensure that higher-priority tasks are executed first.

 Features
Task Class

Stores:

Task description

Due date

Priority level

Estimated completion time
Includes a method to print the task details.

Scheduler Class

Handles:

Adding tasks

Retrieving the next task (highest priority)

Printing all scheduled tasks

Saving tasks to a file

Loading tasks from a file

Main Menu

A user-friendly menu that:

Displays options

Accepts user input

Continues running until the user exits the program

 Data Structure Choice

A priority queue (heap) ensures tasks are always retrieved from highest to lowest priority efficiently.
