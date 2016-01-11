# Computer Programming for Biologists

* **Course:** [BIOL 7800, LSU](http://catalog.lsu.edu/preview_course_nopop.php?catoid=1&coid=1001)
* **Time/Location:** T/Th, 10:30 - 11:50 AM | 0206 Williams
* **Instructor:** [Brant Faircloth](https://github.com/brantfaircloth/)
* **Need help?**
    * [Slack](https://biolprogramming.slack.com), don't email
    * Problem with the syllabus? File an [issue](https://github.com/biolprogramming/syllabus/issues)
* **Office Hours** T/Th 12:00 - 1:30 PM | 220 Life Sciences

## Course description

The analysis of large data sets in biological research is becoming common, particularly as new sequencing technologies and data collection strategies exponentially increase the amount of data that can be collected by an individual researcher.  Programmatic approaches are often needed to format and analyze these large data sets, yet few biologists receive training in applying programming languages to these tasks.  Programming for Biologists is meant to _introduce_ graduate or advanced undergraduate students to the practice of computer programming as it is applied to biological problems using a common programming language (Python, R) and programmatic techniques and algorithms.

## Course credo

This course **is** going to challenge _and_ frustrate you.  A lot.  I promise.  You are learning a new language really quickly - that's a hard thing to do.  Along with the hard parts of learning a new language, in this case, comes having to learn a number of new tools that you have not (likely) been exposed to.  That's also really hard.  You're also going to have to actually **think** on top of all that. But, if you think, and work, and collaborate with your classmates to understand what's going on, you **will** end up learning much, much more in a shorter period of time than you expected.

## Prerequisites

An interest in programming and a willingness to learn.

## Textbook

**Think Python: How to Think Like a Computer Scientist** by [Allen Downey](http://www.allendowney.com/wp/)
[html](http://www.greenteapress.com/thinkpython2/html/index.html)
[pdf](http://www.greenteapress.com/thinkpython2/thinkpython2.pdf)

This is a freely-avialable textbook.  We will follow parts of it for the class.  It is also an invaluable reference text when you need to remind yourself of relatively simple Python details.

## Primary language

[Python](https://www.python.org/) 3.5.1

We are actually using the [Anaconda Python Distribution](http://docs.continuum.io/anaconda/index).  You want to **be sure** to download and installed Python 3.5.x for your operating system (Linux/OSX/Windows).  The [Anaconda](http://docs.continuum.io/anaconda/index) installers are linked, below:

* [OSX Installer](https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda3-2.4.1-MacOSX-x86_64.pkg)
* [Windows Installer](https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda3-2.4.1-Windows-x86_64.exe)
* [Linux Installer](https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda3-2.4.1-Linux-x86_64.sh)

### Why are we using Python 3.5.x?

There exists a weird schism in the world where a now (much) older version of a programming language (Python 2.7.x) is used by many developers versus the newers (and mostly improved) version of that same language (Python 3.5.x).  The reasons for this are many and varied, but they largely dealt with the unavailability of many important packages in Python 3.5.x until "recently".

I would argue that the time is right for scientists to make the move to Python 3.5.x from Python 2.7.x.  So, we're starting that movement.  I also need to teach myself what has changed, and this is a pretty good way to do that.

### Why are we using Anaconda?

1. Because it generally "just works"
2. Offers package manager for installing packages it's missing
3. Has convenient "virtual" environments for testing
4. Comes with many important, precompiled/preinstalled packages (ipython, numpy, requests, etc.)

## Grading

In accordance with the LSU grading policy, grades will be assigned using an A-F scale and the +/- system.  Grading is pretty simple:

                    | Value           | # of assignments  | % of grade
-------------       | -------------   | ----------------- | -------------
Class assignments   | 20 points/each  | 16                |
Code reviews        | 20 points/each  | 16                |
Project Proposal    | 100 points      | 1                 |
Software Project    | 200 points      | 1                 |

Your [Software Project][] grade will be assigned based on (1) my assessment of your work according to a rubric we will discuss in class (50 %) and (2) your classmates assessment of your work based on this same rubric (50%).

## Grading expectations

A significant portion of this course requires you to read, evaluate, and score the work of others.  The points that you earn for [Code reviews][] are based on how well you do this code-review.  If you fail to conduct that review or your review is sloppy, you will receive reduced (or zero) points for that [Code review][] assignment.

### Grading scale

Points Letter Grade Assigned
970-1000 A+
930-969 A
900-929 A-
870-899 B+
830-869 B
800-829 B-
770-799 C+
730-769 C
700-729 C-
670-699 D+
630-669 D
600-629 D-
< 600   F


## Course Overview

The course will be a mix of lecture, in-class "active" learning, individual assignments, group assignments, and group projects.  That keeps it fun for all of us.  You will be expected to participate and complete the assignments given to you or your group.  You will also be expected to contribute equally during any and all group work.  **If you do not, I will ensure your grade reflects that lack of participation**.  See [Commitment to Community][] and [Academic Integrity][] regarding my expectations with respect to being civil to your classmates and doing your own work.

### Lecture

Some portions of our class will be lecture-based.  These lectures will, for the most part, derive from the [Textbook][].  I, of course, will elaborate on certain items and focus less on others - as I feel they are appropriate.   It would be wise for you to **read any chapter of our [Textbook][] prior to coming to class**.  You may even want to read the same chapter, again, after lecture.  Repetition is one key to learning a new language efficiently and effectively.

### Class Assignments

We will have assignments associated with almost every class period.  To receive credit for those assignments, you will need to turn them in on time. Your grade will be assigned by your classmates, who will be doing a majority of the [Code Reviews][] for each of your assignments.

### Code Reviews

One good way to learning how to write computer code is to read, understand, and test the computer code of others.  To facilitate this learning experience, you are going to be doing "in-house" [code reviews](https://en.wikipedia.org/wiki/Code_review) of each other's assignments.

Two code-reviewers will be assigned systematically to review a given assignment (for a given person). Once a reviewer finishes each code review, they will assigning a "grade" to the classmate they are grading, based on a rubric I provide.

### Software Project Proposal

For your final assignment, you will be responsible for putting together a [Software Project][] for this class that builds upon what you've learned during the course.

Prior to starting your [Software Project][] (or your group's [Software Project][]), and about half-way through the course, you will write a 2-page proposal that:

* Describes the problem your [Software Project][] will attempt to solve
* Gives the rational for the solution you propose
* Explains how (roughly) you plan to go about implementing a solution
* Lists potential user-groups of the code you will write

This proposal should be heavy on the description of the problem you intend to solve; why it's important; and why it will benefit other people.  The details can be lighter on implementation.

### Software Project

As mentioned above, your final assignment of this course will be to complete the [Software Project][] you proposed for this class.  This [Software Project][] should build upon what you've learned during class but it is also **very important** that the [Software Project][] incorporate things that we did not explicitly cover in class - your goal here is to grow beyond what I can teach you.  That could mean using a new package that we never covered, creating a new package to use, scraping parts of the web in interesting ways, etc.

## Conduct

### Commitment to Community

You should be familiar with the LSU Commitment to Community, which is outlined [here](http://saa.lsu.edu/code-1-commitment). You should also be familiar with the LSU Code of Student Conduct, which is available [here](http://saa.lsu.edu/code).  You are expected to follow the Commitment to Community during your time in this class and when working on assignments outside of class.  Students who do not respect the instructor(s) or other members of the class will be asked to leave the lecture immediately.  This includes using the telephone, texting, or using the internet for non-class-related purposes during the lecture.

### Academic Integrity

I take academic integrity seriously.  You are expected to reference sources appropriately in your written work.  **You are _absolutely expected_ to reference _any_ third party computer code that you include in your assignments.** You may reference sources in your writing using any method that you prefer (footnotes, Chicago-style, MLA-format), although I expect any referenced material to be paraphrased and cited appropriately.  You may reference any computer code that you use using a URL link to the source of the code.

If you need guidance relative to appropriately paraphrasing sources, please see http://saa.lsu.edu/about-paraphrasing.  If you need guidance relative to appropriately citing sources, please see http://www.chicagomanualofstyle.org/tools_citationguide.html.  If you have remaining questions or concerns, I am happy to help you during my office hours.

You are expected to submit your own work for evaluation (or the work of your group, if a group assignment).

### Academic Misconduct

If I suspect that you have committed Academic Misconduct, I am required to report the incident to the Student Advocacy and Accountability office, and they will follow-up. Definitions of academic misconduct are provided [here](https://saa.lsu.edu/code-10_2-academic-misconduct).

## Schedule

| Date              | Subject                       | Chapter | Assignment Due
--------------------| ------------------------------| ------- | ---------------
14 Jan              | Syllabus; Prep; Installations |         |               
19 Jan              |                               |         |


21 Jan
26 Jan
28 Jan
2 Feb
4 Feb
9 Feb (Mardi Gras)
11 Feb
16 Feb
18 Feb
23 Feb
25 Feb
1 Mar
3 Mar
8 Mar
10 Mar
15 Mar
17 Mar
22 Mar (Spring Break)
24 Mar (Spring Break)
29 Mar
31 Mar
5 Apr
7 Apr
12 Apr
14 Apr
19 Apr
21 Apr
26 Apr
28 Apr
30 Apr (Classed end)
4 May
