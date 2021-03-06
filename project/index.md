---
layout: page
title: "Project"
excerpt: "Project"
tags: ["project"]
context: project
---
<!--
image:
   feature: assignments.jpg
   credit: Delft University of Technology
   creditlink: http://repository.tudelft.nl/view/MMP/uuid:785a7433-f8b0-40b8-b420-b59d88fc2254
-->

In the project part of the course (CS4200-B), you build a compiler and IDE for MiniJava, a small subset of Java.
We split this task into three milestones, each consisting of smaller 'labs':

* [Milestone 1: Syntax Analysis](ms1)
  * [Testing Syntax Analysis](ms1/lab1.html)
  * [Syntax Definition](ms1/lab2.html)
  * [Simple Term Rewriting](ms1/lab3.html)
* [Milestone 2: Semantic Analysis](ms2)
  * [Testing Name Analysis](ms2/lab4.html)
  * [Name Analysis](ms2/lab5.html)
  * [Testing Type Analysis](ms2/lab6.html)
  * [Type Analysis](ms2/lab7.html)
  * [Data-Flow Analysis](ms2/lab8.html)
* [Milestone 3: Code Generation](ms3)
  * [Compiling Minimal Programs](ms3/lab9.html)
  * [Compiling Expressions and Statements](ms3/lab10.html)
  * [Compiling, Fields, Parameters, and Variables](ms3/lab11.html)

## Submission

We rely on GitLab for assignment submissions.
We assign a private GitLab repository to each student and encourage students to commit and push their work frequently.
To submit your assignment, you need to file a merge request.

To check your progress on an assignment, you can submit a *preliminary solution*.
We will provide limited early feedback on preliminary solutions.
This feedback typically comes with a tentative grade and points out areas where your solution is incomplete or insufficient, without giving any details on the reasons.
We do *not give any feedback on the day of a deadline*, since this will not be early at all.

We compute your *final grade* based on the last merged PR.
We will provide a detailed grading report on final solutions.
To ensure fairness and equal chances for all students, grading reports will not be published before the 1-day deadline extension has expired.
We do our best to hand out grading reports as quick as possible, but manual grading can be tedious and might result in longer waiting times for some assignments.

Early feedback and most parts of final grading are automated and supported in GitLab.
Each merge request triggers the launch of a build job which runs automated feedback and grading for your solution.
Be aware that feedback might be delayed due to submissions by other students, instance limits, server problems, etc.

## Grades

We grade the first final solution of each of your assignments.
Grades reflect on correctness, clarity, shown programming skills, and readability of your submission.
To pass the practical part of the course, you need to meet all of the following criteria:

1. You completed each assignment with a grade of 4.0 or better.
2. You completed the assignments of each milestone with an average grade of 5.0 or better.
3. You completed all the assignments with an average grade of 6.0 or better.

These rules allow you to compensate for lower grades in single assignments, but ensure a minimal quality in all your milestones as well as in your overall practical work.

## Deadlines 2018-2019

In Q1 and Q2 the lab is on Friday. The deadlines for the assignments (labs) are listed below and are at 23:59 on that date. All assignments except lab 10 have a 48 hour deadline extension with a penalty of 2 points (off the final grade). Lab 10 has an extension until 11/01 with a penalty of 1 point.

These dates are subject to change.
{: .notice .notice-warning}

* Milestone 1: Syntax Analysis
   - 28/09: Lab 1: Testing Syntax Analysis
   - 28/09: Lab 2: Syntax Definition
   - 05/10: Lab 3: Simple Term Rewriting
* Milestone 2: Semantic Analysis
   - 26/10: Lab 4: Testing Name Analysis
   - 26/10: Lab 5: Name Analysis
* Milestone 2: Semantic Analysis (continued)
   - 23/11: Lab 6: Testing Type Analysis
   - 23/11: Lab 7: Type Analysis
   - 30/11: Lab 8: Data-flow Analysis
* Milestone 3: Code Generation
   - 14/12: Lab 9: Compiling Minimal Programs
   - 21/12: Lab 10: Compiling Expressions and Statements
   - 18/01: Lab 11: Compiling, Fields, Parameters, and Variables

## Academic Misconduct

All actual, detailed work on assignments must be **individual work**.
You are encouraged to discuss assignments, programming languages used to solve the assignments, their libraries, and general solution techniques in these languages with each other.
If you do so, then you must **acknowledge** the people with whom you discussed at the top of your submission.
You should not look for assignment solutions elsewhere; but if material is taken from elsewhere, then you must **acknowledge** its source.
You are not permitted to provide or receive any kind of solutions of assignments.
This includes partial, incomplete, or erroneous solutions.
You are also not permitted to provide or receive programming help from people other than the teaching assistants or instructors of this course.
Any violation of these rules will be reported as a suspected case of fraud to the Board of Examiners and handled according to the EEMCS Faculty's fraud procedure.
If the case is proven, a penalty will be imposed: a minimum of exclusion from the course for the duration of one academic year up to a maximum of a one-year exclusion form all courses at TU Delft.
For details on the procedure, see Section 2.1.26 in the faculty's Study Guide for MSc Programmes.

## Retry

To ensure fairness and equal chances for all students, you are not allowed to take the same practical assignments in another edition of this course.
In case you participated in previous editions of the course, please contact the course manager to discuss an individual assignment.

{% include _toc.html %}
