---
toc: true
layout: post
description: "Planning for the final class create task."
categories: [markdown, week-03]
title: "Create Task Planning"
---
## Initial Idea

A calendar that tracks user goals and displays percentages towards completing those goals and helps the user organize tasks and task categories by levels of importance. The program could also automaticallly shift around tasks on the calendar if the user does not mark them as done by a certain day. 

## College Board Requirement Review

# Program Purpose and Function

The Program will take input for different categories that the user will choose. Then the user will input tasks on certain dates on the calendar, each of which will automatically be considered one part of the whole and the calendar will display multiple bars tracking the users progress towards that whole. The importance of these tasks could be increased or decreased by the user making them larger or smaller parts of the whole. The calendar will display tasks that have not been worked on at the end of each week and move them up in priority based on how much of it has been completed.

# Data Abstraction

The program will contain lists and dictionaries for each task. Every task will have a number assigned to it that can be set by the user and that number will be called on by the calendar and checked if the task is completed to calculate how much of each task category is completed.

# Managing Complexity

The lists and dictionaries will manage complexity by containing all of the values of the user input.

# Procedural Abstraction

A function will be created to check if each task is completed or not completed for each category and looped to add up the numbers for each completed task and see how much out of the whole of the task category is completed. Another function will be used to check if there are any uncompleted tasks that are in a task category that is under a certain percent completed (that can be set by the user) and will raise that task category in importance if that is true.

# Algorithm Implementation

The function called will iterate through each task in the calendar saved in a database or dictionary.

# Testing

When the user marks a task as completed the function will be called to update percentages completed and move up tasks on the calendar.