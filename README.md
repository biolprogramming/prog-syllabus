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

## Teaching philosophy / Communication

I'm here to _help_ you learn to program a computer.  It's up to you to learn how to make that work _for you_.  I view my role as providing guidance and direction and your role as using that guidance and direction to get where you want/need to go.  If you decide that you like this sort of thing, you will be teaching yourself this way for the rest of your life.  Better to learn how to do that now.

Along those lines, I **am not** going to answer questions about this or that program/technique/assignment via email.  **All class communication should happen on [Slack](https://biolprogramming.slack.com)**, and almost all of that communication should happen in a open channel where your classmates can help you answer your question.  You should each be able to create additional #channels, if needed.  You should also take some time to learn about the features [Slack](https://biolprogramming.slack.com) offers, like code-formatting, etc.

A wise person once said that **"99% of bioinformatics is learning how to google"**, and that idea is just as important when talking about computer programming.  Learn how to answer a question for yourself, test out some new ideas if you're close but not quite there, and you'll be kicking-ass in no time.

## Textbook

**Think Python: How to Think Like a Computer Scientist** by [Allen Downey](http://www.allendowney.com/wp/)

* [html](http://www.greenteapress.com/thinkpython2/html/index.html)
* [pdf](http://www.greenteapress.com/thinkpython2/thinkpython2.pdf)

This is a freely-available textbook.  We will follow parts of it for the class.  It is also an invaluable reference text when you need to remind yourself of relatively simple Python details.

## Primary language

[Python](https://www.python.org/) 3.5.1

We are using the [Anaconda Python Distribution](http://docs.continuum.io/anaconda/index).  You want to **be sure** to download and installed Python 3.5.x for your operating system (Linux/OSX/Windows).  The [Anaconda](http://docs.continuum.io/anaconda/index) installers are linked, below:

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

## Software License

We are releasing the contents of this course (e.g. all my notes, all of our code) under an [open-source license](https://en.wikipedia.org/wiki/Open_source) ([BSD](https://en.wikipedia.org/wiki/BSD_licenses)).  As a member of this course, you agree to make your assignments, code review comments, and your final projects open-source, as well.  The reasons we are doing this are many, but it's one (very small) way that we can repay the debt we owe everyone else contributing to open source projects.

One requirement of your [Software Project](#software-project) is that you release it on [github](https://github.com/) as an open-source project.

## Grading

In accordance with the LSU grading policy, grades will be assigned using an A-F scale and the +/- system.  Grading is pretty simple:

Item                                            | Points          | # of assignments  | % of grade
--------                                        | -------------   | ----------------- | -------------
[Class assignments](#class-assignments)         | 15 each         | 25                | 37.5 %
[Code reviews](#code-reviews)                   | 15 each         | 25                | 37.5 %
[Project Proposal](#software-project-proposal)  | 50 points       | 1                 | 5.00 %
[Software Project](#software-project)           | 200 points      | 1                 | 20.0 %
Total                                           | 1000 points     | 32                | 100 %

Your [Software Project](#software-project) grade will be assigned based on:

1. my assessment of your work according to a rubric we will discuss in class (50 %)
2. your classmates assessment of your work based on this same rubric (50%)

There is no extra-credit.

## Grading expectations

A significant portion of this course requires you to read, evaluate, and evaluate the work of others.  The points that you earn for [Code reviews](#code-review) are based on how well you do this code-review.  If you fail to conduct that review or your review is sloppy, you will receive reduced (or zero) points for that [Code review](#code-review) assignment.

Although your classmates will be evaluating your assignments, I will assess the code review that your perform, as well as your performance on the assignment.  I will assign a final grade for both the assignment and code review, and I will post the grades for each assignment (your submission and your code review) to [moodle](https://moodle.lsu.edu), so that you can track your grade.

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

## Absentee policy

If you are in the field during the first portion of class, I will work with you.  Otherwise, if you don't turn in the assignments on time, you will lose points.  Class is optional, I guess.  But it will greatly benefit you to show up in class for the discussion and exercises that will give you a head-start on your assignments.

There are no tests.  There are no exams.

## Course overview

The course will be a mix of lecture, in-class "active" learning, individual assignments, group assignments, and group projects.  That keeps it fun for all of us.  You will be expected to participate and complete the assignments given to you or your group.  You will also be expected to contribute equally during any and all group work.  **If you do not, I will ensure your grade reflects that lack of participation**.  See [Commitment to Community](#commitment-to-community) and [Academic Integrity](#academic-integrity) regarding my expectations with respect to being civil to your classmates and doing your own work.

### Lecture

Some portions of our class will be lecture-based.  These lectures will, for the most part, derive from the [Textbook](#textbook) chapter or the URL provided in the [Schedule](#schedule) .  I, of course, will elaborate on some items and focus less on others - as I feel they are appropriate.   It would be wise for you to **read the assigned reading _prior_ to coming to class**.  You may want to read the same chapter, again, after lecture.  Repetition is one key to learning a new language efficiently.

### Class assignments

We will have assignments associated with almost every class period.  To receive credit for those assignments, you will need to turn them in on time. Your submission will be assessed by your classmates, who will be doing [Code Reviews](#code-review) for each of your assignments.  

I will assign final grades for all assignments and code reviews, and I will post those to [moodle](https://moodle.lsu.edu). The score that you receive on any given assignment will be based on a rubric that is located in each assignments directory.

### Code reviews

One good way to learn how to write computer code is to read, understand, and test the computer code of others.  To facilitate this learning experience, you are going to be doing "in-house" [code reviews](https://en.wikipedia.org/wiki/Code_review) of each other's assignments.

Two code-reviewers will be assigned systematically to review a given assignment (for a given person). A reviewer will assess the work of the classmate they are grading, based on a rubric I provide.  The rubric will be provided along with the assignment when it is posted on [github][https://github.com] (e.g. [assingment-1 rubric](https://github.com/biolprogramming/assignment-1/blob/master/RUBRIC.md)).

I will assess the quality of each code review and assign you a grade for your review.  These reviews will start out relatively simple and get more complex as the course proceeds.

### Software project proposal

For your final assignment, you will be responsible for putting together a [Software Project](#software-project) for this class that builds upon what you've learned during the course.

Prior to starting your [Software Project](#software-project) (or your group's [Software Project](#software-project)), and about half-way through the course, you will write a 2-page proposal that:

* Describes the problem your [Software Project](#software-project) will attempt to solve
* Gives the rational for the solution you propose
* Explains how (roughly) you plan to go about implementing a solution
* Lists potential user-groups of the code you will write

This proposal should be heavy on the description of the problem you intend to solve; why it's important; and why it will benefit other people.  The details can be lighter on implementation.

### Software project

As mentioned above, your final assignment of this course will be to complete the [Software Project](#software-project) you [proposed](#software-project-proposal) for this class.  This [Software Project](#software-project) should build upon what you've learned during class but it is also **very important** that the [Software Project](#software-project) incorporate things that we did not explicitly cover in class - your goal here is to move beyond only those things we covered in class.  That could mean writing a software package that uses a new package that we never covered, creating a new package to use, scraping parts of the web in interesting ways, etc.

As part of your software project, you will make a short presentation on the last day of class that described the problem your software package solves, your rational for the approach you used, how you implemented a solution, and gives a (live) example of the program in action.

You will have several days after the live demo to fix any remaining problems with the package and address any comments from your classmates prior to the review of your final project code (your [Software Project](#software-project) is due 4 May).

## Submitting assignments

1. Fork and clone the appropriate Assignment repository (e.g. [assingment-1](https://github.com/biolprogramming/assignment-1)) to your computer
1. Open that repository in [Github Desktop](https://desktop.github.com/)
1. Create a directory, nested in the **answers** directory **in the cloned, forked assignment repository** that is your **username on github**
1. Navigate to this directory on your computer
1. Add the answers to the assignment questions in the README.md (e.g. https://github.com/biolprogramming/assignment-1)
1. Commit all of the changes to your repository
1. Push/Sync that to Github
1. Make a pull request to the main [biolprogramming](https://github.com/biolprogramming) repository

## Schedule

Date                  | Subject                           | Chapter Due | Assignment Due  |  Code Review
--------------------  | ------------------------------    | ----------- | --------------- | ---------------
14 Jan                | Syllabus; Prep; Installations     | ---         | ---             | ---
19 Jan                | [Introduction to the CLI & REPL](https://github.com/biolprogramming/syllabus/blob/master/lectures/Lecture1.pdf)    | [This](https://github.com/jlevy/the-art-of-command-line) [OSX] or [This](http://powershell.com/Mastering-PowerShell.pdf) [Win]| Assign 1        |
21 Jan                | [Regular Expressions & Pseudocode](https://github.com/biolprogramming/syllabus/blob/master/lectures/Lecture2.pdf)  | [This](http://regexone.com/) and [re module](https://docs.python.org/3.5/library/re.html)                                               | Assign 2        | Assign 1
26 Jan                | [Python Variables/Expressions](https://github.com/biolprogramming/syllabus/blob/master/lectures/Lecture3.pdf)      | Chap [1](http://www.greenteapress.com/thinkpython2/html/thinkpython2002.html) & [2](http://www.greenteapress.com/thinkpython2/html/thinkpython2003.html)  | Assign 3 | Assign 2
28 Jan                | [Functions Part I](https://github.com/biolprogramming/syllabus/blob/master/lectures/Lecture4.pdf)                  | Chap [3](http://www.greenteapress.com/thinkpython2/html/thinkpython2004.html)      | Assign 4 | Assign 3
2 Feb                 | [Conditionals and Recursion](https://github.com/biolprogramming/syllabus/blob/master/lectures/Lecture5.pdf)        | Chap [5](http://www.greenteapress.com/thinkpython2/html/thinkpython2006.html)      | Assign 5 | Assign 4
4 Feb                 | Functions Part II                 | Chap [6](http://www.greenteapress.com/thinkpython2/html/thinkpython2007.html)      | Assign 6 | Assign 5
9 Feb                 | **(Mardi Gras)**                  | ---         | ---   | ---
11 Feb                | Iteration                         | Chap [7](http://www.greenteapress.com/thinkpython2/html/thinkpython2008.html)      | Assign 7 | Assign 6
16 Feb                | Strings & Lists                   | Chap [8](http://www.greenteapress.com/thinkpython2/html/thinkpython2009.html) & [10](http://www.greenteapress.com/thinkpython2/html/thinkpython2011.html) | Assign 8 | Assign 7
18 Feb                | Dictionaries & Tuples             | Chap [11](http://www.greenteapress.com/thinkpython2/html/thinkpython2012.html) & [12](http://www.greenteapress.com/thinkpython2/html/thinkpython2013.html)| Assign 9 | Assign 8
23 Feb                | Files                             | Chap [14](http://www.greenteapress.com/thinkpython2/html/thinkpython2015.html)     | Assign 10 | Assign 9
25 Feb                | Classes & objects                 | Chap [15](http://www.greenteapress.com/thinkpython2/html/thinkpython2016.html)     | Assign 11 | Assign 10
1 Mar                 | Classes & functions               | Chap [16](http://www.greenteapress.com/thinkpython2/html/thinkpython2017.html)     | Assign 12 | Assign 11
3 Mar                 | Classes & methods                 | Chap [17](http://www.greenteapress.com/thinkpython2/html/thinkpython2018.html)     | Assign 13 | Assign 12
8 Mar                 | Inheritance                       | Chap [18](http://www.greenteapress.com/thinkpython2/html/thinkpython2019.html)     | Assign 14 | Assign 13
10 Mar                | The Kitchen Sink                  | Chap [19](http://www.greenteapress.com/thinkpython2/html/thinkpython2020.html)     | Assign 15 | Assign 14
15 Mar                | PEP8, programs, modules, practices| [PEP 8](https://www.python.org/dev/peps/pep-0008/) | Assign 16 | Assign 15
17 Mar                | TDD and Documentation             |             | Assign 17 | Assign 16
22 Mar                | **(Spring Break)**                | ---         | ---   | ---
24 Mar                | **(Spring Break)**                | ---         | ---   | ---
29 Mar                | BioPython                         | [BioPython Cookbook](http://biopython.org/DIST/docs/tutorial/Tutorial.html)   | Project proposal | ---
31 Mar                | BioPython                         | [BioPython Cookbook](http://biopython.org/DIST/docs/tutorial/Tutorial.html)   | Assign 18 | Assign 17
5 Apr                 | numpy                             | [numpy user guide](http://docs.scipy.org/doc/numpy-1.10.1/user/)     | Assign 19 | Assign 18
7 Apr                 | numpy + pandas                    | [pandas user guide](http://pandas.pydata.org/pandas-docs/version/0.17.1/pandas.pdf)<sup>[1](#fnote1)</sup>| Assign 20 | Assign 19
12 Apr                | requests                          | [requests manual](http://docs.python-requests.org/en/latest/)        | Assign 21 | Assign 20
14 Apr                | BioPython + NCBI                  | ---         | Assign 22 | Assign 21
19 Apr                | subprocess                        | [subprocess](https://docs.python.org/3.5/library/subprocess.html)    | Assign 23 | Assign 22
21 Apr                | itertools & sqlite3               | [itertools](https://docs.python.org/3.5/library/itertools.html) & [sqlite3](https://docs.python.org/3.5/library/sqlite3.html) | Assign 24 | Assign 23
26 Apr                | speed, timing, and multiprocessing| [timeit](https://docs.python.org/3.5/library/timeit.html) & [multiprocessing](https://docs.python.org/3.5/library/multiprocessing.html)| Assign 25 | Assign 24
28 Apr                | Software Project Demos            | ---         | Software project demo | Assign 25
30 Apr                | **(Classes end)**                 | ---         | --- | ---
4 May                 | Final Software Projects Due       | ---         | Software project | ---

 <sup><a name="fnote1">1</a></sup> No, I do not expect you to read all 1800+ pages.  Read Chapters 5, 6, 8, 9, 10.  Experiment w/ the examples.

## Conduct

### Commitment to Community

You should be familiar with the LSU Commitment to Community, which is outlined [here](http://saa.lsu.edu/code-1-commitment). You should also be familiar with the LSU Code of Student Conduct, which is available [here](http://saa.lsu.edu/code).  You are expected to follow the Commitment to Community during your time in this class and when working on assignments outside of class.  Students who do not respect the instructor(s) or other members of the class will be asked to leave the lecture immediately.  This includes using the telephone, texting, or using the internet for non-class-related purposes during the lecture.

### Academic Integrity

I take academic integrity seriously.  You are expected to reference sources appropriately in your written work.  **You are _absolutely expected_ to reference _any_ third party computer code that you include in your assignments.** You may reference sources in your writing using any method that you prefer (footnotes, Chicago-style, MLA-format), although I expect any referenced material to be paraphrased and cited appropriately.  You may reference any computer code that you use using a URL link to the source of the code.

If you need guidance relative to appropriately paraphrasing sources, please see [this link](http://saa.lsu.edu/about-paraphrasing).  If you need guidance relative to appropriately citing sources, please see [this link](http://www.chicagomanualofstyle.org/tools_citationguide.html).  If you have remaining questions or concerns, I am happy to help you during my office hours.

You are expected to submit your own work for evaluation (or the work of your group, if a group assignment).

### Academic Misconduct

If I suspect that you have committed Academic Misconduct, I am required to report the incident to the Student Advocacy and Accountability office, and they will follow-up. Definitions of academic misconduct are provided [here](https://saa.lsu.edu/code-10_2-academic-misconduct).
