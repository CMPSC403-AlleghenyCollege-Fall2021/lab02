# Lab 02 in CMPSC 403 Fall 2021

## Deadline: October 1, 2021 by 3pm

## Table of Contents

- [Summary](#summary)
- [Objectives](#objectives)
- [Code of Conduct](#code-of-conduct)
- [Assignment Specification](#assignment-specification)
- [Required Deliverables](#required-deliverables)
- [Assignment Assessment](#assignment-assessment)
- [Receiving Assistance](receiving-assistance)

## Summary

Designed for use with [GitHub Classroom](https://classroom.github.com/), this repository contains the assignment for Laboratory 2 assignment in Computer Science 403.

This laboratory assignment invites you to work individually to participate in the assembly cracking challenge, to complete "Buffer Overflow" room on TryHackMe, and to manufacture and exploit a buffer overflow in a C program. You are also responsible for writing a detailed reflection, stored in the file `reflection.md`. This is a Markdown file that must adhere to the standards described in the [Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/).

## Objectives

To practice inspecting assembly code. To further learn and examine the idea of buffer overflows to be able to identify how that specific vulnerability can be exploited. To exprience working in both Linux and Windows machines.

## Code of Conduct

Throughout the completion of this project you must adhere to the [community guidelines](https://github.com/CMPSC403-AlleghenyCollege-Fall2021/community_guidelines) that we developed as a class. In addition to reporting any violations of the code of conduct, please make sure that you have followed the code of conduct during this lab. Students who think that the class should revise some aspect of the guidelines must use the GitHub issue tracker for that repository to suggest, discuss, and implement any required changes.

## Assignment Specification

In this lab you will continue with the assembly exploration, specifically by learning how to crack passwords by inspecting assembly code. You are then invited to explore the concept of buffer overflows by completing a TryHackMe room connected to this topic and to design your own buffer overflow exploitation example. Finally, you are invited to reflect on your experiences in a Markdown file given in this repository.

1. Lab 2.1: [Assembly CrackMe Challenge]()
2. Lab 2.2: [Buffer Overflow Walkthrough]()
3. Lab 2.3: Create a C program that displays student grade of F with an intentional buffer overflow vulnerability. Then, demontrate the exploitation of this vulnerability. Use the VM on TryHackMe from Lab 2.1 or Lab 2.2 to test your program and its exploitation.

## Required Deliverables

This assignment invites you to submit the following deliverables.

1. Lab 2.1 on TryHackMe.
2. Lab 2.2 on TryHackMe. Take screenshots and submit them in your report. Submit final Python programs via GitHub.
3. Lab 2.3: A C program with a buffer overflow vulnerability that displays a student grade of F (see below for a sample output), and then provide an exploitation solution that uses the vulnerability to change to grade to an A (use class example as a motivation). The original C program submitted via your lab 02 repository. The exploitation must be either demonstrated in the report (for example, what is inputted to create an exploitation, how it is exploited, etc.) and/or a shell code must be submitted via lab02 repository.

Sample output:

```
What is your name?
>> Janyl
Janyl, your current grade in CMPSC 403 is F
```

5. Reflection document submitted via your lab02 repository.

## Recommended Timeline

To take the best advantage of the content covered in class, it is recommended that you scaffold the completion of lab 2 in the following manner:

1. Complete Lab 2.1 before class on Tuesday, September 21st.
2. Complete Lab 2.2 before lab on Friday, September 24th.
3. Complete Lab 2.3 before lab on Friday, October 1st.

## Assignment Assessment

The grade that a student receives on this assignment will have the following components.

- **Mastery of Technical Writing [up to 25%]:**: Students will receive a part of their grade when the responses to the writing questions presented in the `reflection.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

- **Mastery of Technical Knowledge and Skills [up to 75%]**: Students will receive a full portion of this part of their assignment grade when their completed assignments on TryHackMe for this lab reveal that they have mastered all of the technical knowledge and skills developed during the completion of this lab. As a part of this grade, the instructor will assess aspects of the lab including, but not limited to, the number of questions completed and the points received on TryHackMe platform.

All grades for this project will be reported through a student's gradebook GitHub repository and the feedback pull request in this repository.

## Receiving Assistance

If you are having trouble completing any part of this project, then please talk with the course instructor during the lab session. Alternatively, you may ask questions in the Discord channel for this course. Finally, you can schedule a meeting during the course instructor's office hours.
