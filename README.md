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

* [html](http://www.greenteapress.com/thinkpython2/html/index.html)
* [pdf](http://www.greenteapress.com/thinkpython2/thinkpython2.pdf)

This is a freely-avialable textbook.  We will follow parts of it for the class.  It is also an invaluable reference text when you need to remind yourself of relatively simple Python details.

## Primary language

[Python](https://www.python.org/) 3.5.1

We are actually using the [Anaconda Python Distribution](http://docs.continuum.io/anaconda/index).  You want to **be sure** to download and installed Python 3.5.x for your operating system (Linux/OSX/Windows).  The [Anaconda](http://docs.continuum.io/anaconda/index) installers are linked, below:

* [OSX Installer](https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda3-2.4.1-MacOSX-x86_64.pkg)
* [Windows Installer](https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda3-2.4.1-Windows-x86_64.exe)
* [Linux Installer](https://3230d63b5fc54e62148e-c95ac804525aac4b6dba79b00b39d1d3.ssl.cf1.rackcdn.com/Anaconda3-2.4.1-Linux-x86_64.sh)

### Why are we using Python 3.5.x?

There exists a weird schism in the world where a now (much) older version of a programming language (Python 2.7.x) is used by many developers versus the newer (and mostly improved) version of that same language (Python 3.5.x).  The reasons for this are many and varied, but they largely dealt with the unavailability of many important packages in Python 3.5.x until "recently".

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

Your [Software Project](#software-project) grade will be assigned based on (1) my assessment of your work according to a rubric we will discuss in class (50 %) and (2) your classmates assessment of your work based on this same rubric (50%).

## Grading expectations

A significant portion of this course requires you to read, evaluate, and score the work of others.  The points that you earn for [Code reviews](#code-review) are based on how well you do this code-review.  If you fail to conduct that review or your review is sloppy, you will receive reduced (or zero) points for that [Code review](#code-review) assignment.

### Grading scale

Points        | Letter Grade Assigned
--------------|----------------------
970-1000      | A+
930-969       | A
900-929       | A-
870-899       | B+
830-869       | B
800-829       | B-
770-799       | C+
730-769       | C
700-729       | C-
670-699       | D+
630-669       | D
600-629       | D-
< 600         | F


## Course Overview

The course will be a mix of lecture, in-class "active" learning, individual assignments, group assignments, and group projects.  That keeps it fun for all of us.  You will be expected to participate and complete the assignments given to you or your group.  You will also be expected to contribute equally during any and all group work.  **If you do not, I will ensure your grade reflects that lack of participation**.  See [Commitment to Community][] and [Academic Integrity][] regarding my expectations with respect to being civil to your classmates and doing your own work.

### Lecture

Some portions of our class will be lecture-based.  These lectures will, for the most part, derive from the [Textbook][].  I, of course, will elaborate on certain items and focus less on others - as I feel they are appropriate.   It would be wise for you to **read any chapter of our [Textbook][] prior to coming to class**.  You may even want to read the same chapter, again, after lecture.  Repetition is one key to learning a new language efficiently and effectively.

### Class Assignments

We will have assignments associated with almost every class period.  To receive credit for those assignments, you will need to turn them in on time. Your grade will be assigned by your classmates, who will be doing a majority of the [Code Reviews](#code-review) for each of your assignments.

### Code Reviews

One good way to learning how to write computer code is to read, understand, and test the computer code of others.  To facilitate this learning experience, you are going to be doing "in-house" [code reviews](https://en.wikipedia.org/wiki/Code_review) of each other's assignments.

Two code-reviewers will be assigned systematically to review a given assignment (for a given person). Once a reviewer finishes each code review, they will assigning a "grade" to the classmate they are grading, based on a rubric I provide.

### Software Project Proposal

For your final assignment, you will be responsible for putting together a [Software Project](#software-project) for this class that builds upon what you've learned during the course.

Prior to starting your [Software Project](#software-project) (or your group's [Software Project](#software-project)), and about half-way through the course, you will write a 2-page proposal that:

* Describes the problem your [Software Project](#software-project) will attempt to solve
* Gives the rational for the solution you propose
* Explains how (roughly) you plan to go about implementing a solution
* Lists potential user-groups of the code you will write

This proposal should be heavy on the description of the problem you intend to solve; why it's important; and why it will benefit other people.  The details can be lighter on implementation.

### Software Project

As mentioned above, your final assignment of this course will be to complete the [Software Project](#software-project) you proposed for this class.  This [Software Project](#software-project) should build upon what you've learned during class but it is also **very important** that the [Software Project](#software-project) incorporate things that we did not explicitly cover in class - your goal here is to grow beyond what I can teach you.  That could mean using a new package that we never covered, creating a new package to use, scraping parts of the web in interesting ways, etc.

## Conduct

### Commitment to Community

You should be familiar with the LSU Commitment to Community, which is outlined [here](http://saa.lsu.edu/code-1-commitment). You should also be familiar with the LSU Code of Student Conduct, which is available [here](http://saa.lsu.edu/code).  You are expected to follow the Commitment to Community during your time in this class and when working on assignments outside of class.  Students who do not respect the instructor(s) or other members of the class will be asked to leave the lecture immediately.  This includes using the telephone, texting, or using the internet for non-class-related purposes during the lecture.

### Academic Integrity

I take academic integrity seriously.  You are expected to reference sources appropriately in your written work.  **You are _absolutely expected_ to reference _any_ third party computer code that you include in your assignments.** You may reference sources in your writing using any method that you prefer (footnotes, Chicago-style, MLA-format), although I expect any referenced material to be paraphrased and cited appropriately.  You may reference any computer code that you use using a URL link to the source of the code.

If you need guidance relative to appropriately paraphrasing sources, please see [this link](http://saa.lsu.edu/about-paraphrasing).  If you need guidance relative to appropriately citing sources, please see [this link](http://www.chicagomanualofstyle.org/tools_citationguide.html).  If you have remaining questions or concerns, I am happy to help you during my office hours.

You are expected to submit your own work for evaluation (or the work of your group, if a group assignment).

### Academic Misconduct

If I suspect that you have committed Academic Misconduct, I am required to report the incident to the Student Advocacy and Accountability office, and they will follow-up. Definitions of academic misconduct are provided [here](https://saa.lsu.edu/code-10_2-academic-misconduct).

## Schedule

| Date                | Subject                           | Chapter Due | Due
--------------------  | ------------------------------    | ----------- | ---------------
14 Jan                | Syllabus; Prep; Installations     |             |               
19 Jan                | Introduction to the CLI           |             | Assignment 1
21 Jan                | Regular Expressions & Pseudocode  |             | Assignment 2
26 Jan                | Python Variables/Expressions      | Chap 1 & 2  | Assignment 3
28 Jan                | Functions Part I                  | Chap 3      | Assignment 4
2 Feb                 | Conditionals and Recursion        | Chap 5      | Assignment 5
4 Feb                 | Functions Part II                 | Chap 6      | Assignment 6
9 Feb (Mardi Gras)    | ---                               | ---         | ---         
11 Feb                | Iteration                         | Chap 7      | Assignment 7
16 Feb                | Strings & Lists                   | Chap 8 & 10 | Assignment 8
18 Feb                | Dictionaries & Tuples             | Chap 11 & 12| Assignment 9
23 Feb                | Files                             | Chap 14     | Assignment 10
25 Feb                | Classes & objects                 | Chap 15     | Assignment 11
1 Mar                 | Classes & functions               | Chap 16     | Assignment 12
3 Mar                 | Classes & methods                 | Chap 17     | Assignment 13
8 Mar                 | Inheritance                       | Chap 18     | Assignment 14
10 Mar                | The Kitchen Sink                  | Chap 19     | Assignment 15
15 Mar                | PEP8, programs, modules           | PEP 8       | Assignment 16
17 Mar                | TDD and Documentation             |             |
22 Mar (Spring Break) | ---                               | ---         | ---         
24 Mar (Spring Break) | ---                               | ---         | ---         
29 Mar                | BioPython                         | [BioPython Cookbook](http://biopython.org/DIST/docs/tutorial/Tutorial.html)   | Project proposal
31 Mar                | BioPython                         | [BioPython Cookbook](http://biopython.org/DIST/docs/tutorial/Tutorial.html)   | Assignment 17
5 Apr                 | numpy                             | [numpy user guide](http://docs.scipy.org/doc/numpy-1.10.1/user/)     | Assignment 18
7 Apr                 | numpy + pandas                    | [pandas user guide](http://pandas.pydata.org/pandas-docs/version/0.17.1/pandas.pdf)<sup>*</sup> | Assignment 19
12 Apr                | requests                          | [requests manual](http://docs.python-requests.org/en/latest/)        | Assignment 20
14 Apr                | BioPython + NCBI                  | ---         | Assignment 21
19 Apr                | subprocess                        | [subprocess](https://docs.python.org/3.5/library/subprocess.html)    | Assignment 22
21 Apr                | itertools & sqlite3               | [itertools](https://docs.python.org/3.5/library/itertools.html) & [sqlite3](https://docs.python.org/3.5/library/sqlite3.html) | Assignment 23
26 Apr                | speed, timing, and multiprocessing| [timeit](https://docs.python.org/3.5/library/timeit.html) & [multiprocessing](https://docs.python.org/3.5/library/multiprocessing.html)| Assignment 24
28 Apr                | Software Project Demos            | ---         | Software project demo
30 Apr (Classed end)  | ---                               | ---         | ---
4 May                 | Final Software Projects Due       | ---         | Software project

<sup>*</sup> No, I do not expect you to read all 1800+ pages.  Check Chapters 5,6,8,9,10.
