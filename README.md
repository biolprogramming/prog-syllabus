# Computer Programming for Biologists

* **Course:** [BIOL 7800, LSU](http://catalog.lsu.edu/preview_course_nopop.php?catoid=1&coid=1001)
* **Time/Location:** T/Th, 9:00 - 10:20 AM and W, 9:30 - 10:20 AM | 0118 Prescott
* **Instructor:** [Brant Faircloth](https://github.com/brantfaircloth/)
* **Need help?**
    * [Slack](https://biolprogramming.slack.com), don't email
    * Problem with the syllabus? File an [issue](https://github.com/biolprogramming/syllabus/issues)
* **Office Hours** T/Th 10:30 - 12:00 PM | 282 Life Sciences

## Course description

The analysis of large data sets in biological research is becoming common, particularly as new sequencing technologies and data collection strategies exponentially increase the amount of data that can be collected by an individual researcher.  Programmatic approaches are often needed to format and analyze these large data sets, yet few biologists receive training in applying programming languages to these tasks.  `Programming for Biologists` is meant to _introduce_ graduate or advanced undergraduate students to the practice of computer programming as it is applied to biological problems using a common programming language (Python) and programmatic techniques and algorithms.

## Course credo

This course **is** going to challenge _and_ frustrate you.  A lot.  I promise.  You are learning a new language really quickly - that's a hard thing to do.  Along with the hard parts of learning a new language, in this case, comes having to learn a number of new tools that you have not (likely) been exposed to.  That's also really hard.  You're also going to have to actually **think** on top of all that. But, if you think, and work, and work with your classmates to understand what's going on, you **will** end up learning much, much more in a shorter period of time than you expected.

## Teaching philosophy / Communication

I'm here to _help_ you learn to program a computer.  It's up to you to learn how to make that work _for you_.  I view my role as providing guidance and direction and your role as using that guidance and direction to get where you want/need to go.  If you decide that you like this sort of thing, you will be teaching yourself this way for the rest of your life.  Better to learn how to do that now.

Along those lines, I **am not** going to answer questions about this or that program/technique/assignment via email.  **All class communication should happen on [Slack](https://biolprogramming.slack.com)**, and almost all of that communication should happen in a open channel where your classmates can help you answer your question.  You should each be able to create additional #channels, if needed.  You should also take some time to learn about the features [Slack](https://biolprogramming.slack.com) offers, like code-formatting, etc.

Part of the learning process is figuring out **how** to search for and find the information you need to fix a problem that you are having.  I am unlikely to respond to requests on [Slack](https://biolprogramming.slack.com) that can be answered using a simple google search.  I'm not doing this to be mean, I'm doing it because formulating a good search strategy to help you answer these types of problems is in your best interest.

A wise person once said that **"99% of bioinformatics is learning how to google"**, and that idea is just as important when talking about computer programming.  Learn how to answer a question for yourself, test out some new ideas if you're close but not quite there, and you'll be kicking-ass in no time.

**THAT SAID**, a wise person also said that using these types of information without attribution is **plagiarism**.  So, **DO NOT** use these sources without attribution, and **DO NOT** use these sources as a crutch to help you succeed in this course.  I will notice is all of your assignments are using code from elsehere.  You will also learn much less, this way.

## What You Should Be Doing

In a word: **experimenting**.  The best way for you to learn what works is to try different things out.  For example, if I tell you that you have a list containing `[1,2,3,4]` and ask you how to drop the last number, you should look up several ways that you might go about doing this and try those in the REPL.  There are lots of solutions, like:

```python
# drop the last item from this list
l = [1,2,3,4]

# the smart
new_l = l[:3]
# or the redundant
new_l = [item for item in l[:3]]
# or the snarky
new_l = [1,2,3]
# or the "i read the documentation" and think this is smart
new_l = l.remove(4)
```
So, try them out and see what's what.  **You should be doing this for everything!!**

## Textbook

**Think Python: How to Think Like a Computer Scientist** by [Allen Downey](http://www.allendowney.com/wp/)

* [html](http://www.greenteapress.com/thinkpython2/html/index.html)
* [pdf](http://www.greenteapress.com/thinkpython2/thinkpython2.pdf)

This is a freely-available textbook.  We will follow parts of it for the class.  It is also an invaluable reference text when you need to remind yourself of relatively simple Python details.

## Primary language

[Python](https://www.python.org/) 3.6

This year, we're going to try something different from what we've done in previous years.  To get around most of the problems with learning a language on different computing platforms (which can be a pain), you will be learning Python using [repl.it](https://repl.it), which is a way to practice your Python skills without worrying about the details of differnt operating systems.

### Using Python on Your Own Machine

I am not, yet, sure how much of this we will be doing... However, you may want to install a version of Python on your own machine.  If you do, I suggest using the Conda Python Distribution.  Specifically, the `miniconda` distribution.  If you are using Windows 10, you will probably also benefit greatly from installing the Linux Subsystem.  On Windows and for bioinformatics/programming tasks, the Linux subsystem is the way to go.

* Here are installer packages for [Miniconda](https://conda.io/miniconda.html)
* And, here are some details regarding the [Linux subsystem on Windows 10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

### Why are we using Python 3.6.x?

There exists a weird schism in the world where a now (much) older version of a programming language (Python 2.7.x) is used by many developers versus the newer (and mostly improved) version of that same language (Python 3.6.x).  The reasons for this are many and varied, but they largely dealt with the unavailability of many important packages in Python 3.6.x until "recently".

I would argue that the time is right for scientists to make the move to Python 3.6.x from Python 2.7.x.  So, we're starting that movement.

### Why are we using repl.it?

1. Because teaching a programming language where everyone's laptop runs a different OS is difficult.
2. [repl.it](https://repl.it) can install packages we are missing
3. [repl.it](https://repl.it) makes it easier to grade assignments that you complete

### What if I want to use a code-editor/IDE?

Fine with me - you'll still need to upload your code to [repl.it](https://repl.it).  Speaking of, a good code editor is worth learning and something that we'll spend time on during on of the labs.  If you are after something free, I suggest:

* [Atom](https://atom.io/)
* [VS Code](https://code.visualstudio.com/)

## Software License

I am releasing the contents of this course (e.g. all my notes) under an [open-source license](https://en.wikipedia.org/wiki/Open_source) ([BSD](https://en.wikipedia.org/wiki/BSD_licenses)).

## Grading

In accordance with the LSU grading policy, grades will be assigned using an A-F scale and the +/- system.  Grading is pretty simple:

Item                                            | Points          | # of assignments  | Total Points  | % of grade
--------                                        | -------------   | ----------------- | ------------- | -------------
[Class assignments](#class-assignments)         | 25 each         | 22                | 550           | ~55%
[Class exams](#class-exams)                     | 150 each        | 3                 | 450           | ~45%
Total                                           |                 |                   | 1000 points   | 100%


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

If you are in the field during the first portion of class, I will work with you.  Otherwise, if you don't turn in the assignments on time, you will lose all of the points for that assignment.  Class is technically optional.  But, it will greatly benefit you to show up in class for the discussion and exercises that will give you a head-start on your assignments.  It will also help you prepare for the exams, which will be paper-based and for which you will not use a computer.

## Course overview

The course will be a mix of lecture, in-class "active" learning, individual assignments, and exams.  That keeps it fun for all of us.  You will be expected to contribute to discussions in class.  **If you do not, I will ensure your grade reflects that lack of participation**.  Also, see [Commitment to Community](#commitment-to-community) and [Academic Integrity](#academic-integrity) regarding my expectations with respect to being civil to your classmates and doing your own work.

### Lecture

Some portions of our class will be lecture-based.  These lectures will, for the most part, derive from the [Textbook](#textbook) chapter or the URL provided in the [Schedule](#schedule) .  I, of course, will elaborate on some items and focus less on others - as I feel they are appropriate.   It would be wise for you to **read the assigned reading _prior_ to coming to class**.  You may want to read the same chapter, again, after lecture.  Repetition is one key to learning a new language efficiently.

### Laboratory

There is a _laboratory_ section of this class that is meant to provide time for me to assist you with problems that you may be encountering as you learn to program or for us to review materials we've covered during the course.  The laboratory section is mandatory, although it may not always use the fully allotted period of time.  During lab, be prepared to review code from your previous assignments, ask implementation questions, and discuss problems you are having.  The laboratory is meant to directly help you with each part of your assignment - that's not the goal.  The goal is to get you over minor obstacles that are keeping you from completing your assignments.

I added the laboratory section to this class on the advice of previous students who have enrolled.

### Class assignments

We will have assignments associated with almost every class period, and **assignments are to be submitted before the class period at which they are due**.  To receive credit for those assignments, you will need to turn them in on time. Late assignments will receive a score of zero.

Assignment and exam scores will post to [moodle](https://moodle.lsu.edu). The score that you receive on any given assignment will be based on a rubric that is associated with each assignment.  Generally, this means that your function or program produces the expected output by following the expected progression of steps.  For example, if I ask you to write a computer program to compute the value of the constant `e`, but you simply output the value of `math.e` without specifically computing `e`, you will not receive credit for that portion of the assignment.

### Exams

You will have three exams associated with this class.  These will be in-class exams that focus on what you've learned during the previous few weeks.  **These will not be open-book**.  I have decided to hold exams for this course to ensure that everyone in the class is taking the time to study the material we cover.  The types of questions on the exam will range from general ("Who was Ada Lovelace?") to specific ("What is the difference between an integer and a float? Why is a tuple better to hold data?").  These tests should be challenging.


## Schedule



| Week |  Date  |                                                                    Subject                                                                     |                                                                             Chapter                                                                             | Assignment Due |
|------|--------|------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
|    1 | 21 Aug | Syllabus; Intro                                                                                                                                |                                                                                                                                                                 |                |
|      | 22 Aug | LAB (Intro to Repl and repl.it)                                                                                                                |                                                                                                                                                                 |                |
|      | 23 Aug | [Python Variables/Expressions](http://biolprogramming.s3.amazonaws.com/Lecture3.pdf)                                                           | Chap [1](http://www.greenteapress.com/thinkpython2/html/thinkpython2002.html) & [2](http://www.greenteapress.com/thinkpython2/html/thinkpython2003.html)        |                |
|    2 | 28 Aug | [Functions Part I & PEP8](http://biolprogramming.s3.amazonaws.com/Lecture4.pdf)                                                                | Chap [3](http://www.greenteapress.com/thinkpython2/html/thinkpython2004.html) & [PEP 8](https://www.python.org/dev/peps/pep-0008/)                              |              1 |
|      | 29 Aug | LAB (Function practice)                                                                                                                        |                                                                                                                                                                 |                |
|      | 30 Aug | [Conditionals and Recursion](http://biolprogramming.s3.amazonaws.com/Lecture5.pdf)                                                             | Chap [5](http://www.greenteapress.com/thinkpython2/html/thinkpython2006.html)                                                                                   |              2 |
|    3 | 4 Sep  | [Functions Part II](http://biolprogramming.s3.amazonaws.com/Lecture6.pdf)                                                                      | Chap [6](http://www.greenteapress.com/thinkpython2/html/thinkpython2007.html)                                                                                   |              3 |
|      | 5 Sep  | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 6 Sep  | [Iteration](http://biolprogramming.s3.amazonaws.com/Lecture7.pdf)                                                                              | Chap [7](http://www.greenteapress.com/thinkpython2/html/thinkpython2008.html)                                                                                   |              4 |
|    4 | 11 Sep | [Strings & Lists](http://biolprogramming.s3.amazonaws.com/Lecture8.pdf)                                                                        | Chap [8](http://www.greenteapress.com/thinkpython2/html/thinkpython2009.html) & [10](http://www.greenteapress.com/thinkpython2/html/thinkpython2011.html)       |              5 |
|      | 12 Sep | **NO LAB**                                                                                                                                     |                                                                                                                                                                 |                |
|      | 13 Sep | **NO CLASS**                                                                                                                                   |                                                                                                                                                                 |                |
|    5 | 18 Sep | [Dictionaries & Tuples](http://biolprogramming.s3.amazonaws.com/Lecture9.pdf)                                                                  | Chap [11](http://www.greenteapress.com/thinkpython2/html/thinkpython2012.html) & [12](http://www.greenteapress.com/thinkpython2/html/thinkpython2013.html)      |              6 |
|      | 19 Sep | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 20 Sep | [Files](http://biolprogramming.s3.amazonaws.com/Lecture10.pdf)                                                                                 | Chap [14](http://www.greenteapress.com/thinkpython2/html/thinkpython2015.html)                                                                                  |              7 |
|    6 | 25 Sep | Input/Output/Stdin/Stdout/Logging                                                                                                              |                                                                                                                                                                 |              8 |
|      | 26 Sep | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 27 Sep | **EXAM 1** (in class)                                                                                                                          |                                                                                                                                                                 |             9  |
|    7 | 2 Oct  | [Classes & objects](http://biolprogramming.s3.amazonaws.com/Lecture11.pdf)                                                                     | Chap [15](http://www.greenteapress.com/thinkpython2/html/thinkpython2016.html) & Chap [16](http://www.greenteapress.com/thinkpython2/html/thinkpython2017.html) |                |
|      | 3 Oct  | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 4 Oct  | **NO CLASS (FALL BREAK)**                                                                                                                      |                                                                                                                                                                 |                |
|    8 | 9 Oct  | [Classes & methods](http://biolprogramming.s3.amazonaws.com/Lecture12.pdf)                                                                     | Chap [17](http://www.greenteapress.com/thinkpython2/html/thinkpython2018.html) & Chap [18](http://www.greenteapress.com/thinkpython2/html/thinkpython2019.html) |             10 |
|      | 10 Oct | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 11 Oct | [The Kitchen Sink](http://biolprogramming.s3.amazonaws.com/Lecture13.pdf)                                                                      | Chap [19](http://www.greenteapress.com/thinkpython2/html/thinkpython2020.html)                                                                                  |             11 |
|    9 | 16 Oct | [The Kitchen Sink (Part 2)](http://biolprogramming.s3.amazonaws.com/Lecture14.pdf)                                                             |                                                                                                                                                                 |             12 |
|      | 17 Oct | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 18 Oct | [TDD and Documentation](http://biolprogramming.s3.amazonaws.com/Lecture15.pdf)                                                                 |                                                                                                                                                                 |             13 |
|   10 | 23 Oct | [Python Modules](http://biolprogramming.s3.amazonaws.com/Lecture16.pdf) and [BioPython](http://biolprogramming.s3.amazonaws.com/Lecture17.pdf) | [BioPython Cookbook](http://biopython.org/DIST/docs/tutorial/Tutorial.html)                                                                                     |             14 |
|      | 24 Oct | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 25 Oct | **EXAM 2** (in class)                                                                                                                          |                                                                                                                                                                 |             15 |
|   11 | 30 Oct | [BioPython + NCBI](http://biolprogramming.s3.amazonaws.com/Lecture18.pdf)                                                                      | [BioPython Cookbook](http://biopython.org/DIST/docs/tutorial/Tutorial.html)                                                                                     |                |
|      | 31 Oct | **NO CLASS**                                                                                                                                   |                                                                                                                                                                 |                |
|      | 1 Nov  | **NO CLASS**                                                                                                                                   |                                                                                                                                                                 |                |
|   12 | 6 Nov  | [numpy + pandas](http://biolprogramming.s3.amazonaws.com/Lecture19.pdf)                                                                        | [numpy user guide](hhttps://docs.scipy.org/doc/numpy/) & [pandas user guide](http://pandas.pydata.org/pandas-docs/stable/pandas.pdf)<sup>[1](#fnote1)</sup>     |             16 |
|      | 7 Nov  | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 8 Nov  | [numpy + pandas](http://biolprogramming.s3.amazonaws.com/Lecture19.pdf)                                                                        | [numpy user guide](hhttps://docs.scipy.org/doc/numpy/) & [pandas user guide](http://pandas.pydata.org/pandas-docs/stable/pandas.pdf)<sup>[1](#fnote1)</sup>     |             17 |
|   13 | 13 Nov | [subprocess](http://biolprogramming.s3.amazonaws.com/Lecture20.pdf)                                                                            |                                                                                                                                                                 |             18 |
|      | 14 Nov | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 15 Nov | [subprocess](http://biolprogramming.s3.amazonaws.com/Lecture20.pdf)                                                                            | [subprocess](https://docs.python.org/3.6/library/subprocess.html)                                                                                               |             19 |
|   14 | 20 Nov | [sqlite3](http://biolprogramming.s3.amazonaws.com/Lecture22.pdf)                                                                               | [sqlite3](https://docs.python.org/3.6/library/sqlite3.html)                                                                                                     |             20 |
|      | 21 Nov | **NO CLASS (THANKSGIVING)**                                                                                                                    |                                                                                                                                                                 |                |
|      | 22 Nov | **NO CLASS (THANKSGIVING)**                                                                                                                    |                                                                                                                                                                 |                |
|   15 | 27 Nov | [speed, timing, and multiprocessing](http://biolprogramming.s3.amazonaws.com/Lecture23.pdf)                                                    | [timeit](https://docs.python.org/3.6/library/timeit.html) & [multiprocessing](https://docs.python.org/3.6/library/multiprocessing.html)                         |             21 |
|      | 28 Nov | LAB                                                                                                                                            |                                                                                                                                                                 |                |
|      | 29 Nov | **Currently open**                                                                                                                             |                                                                                                                                                                 |             22 |
|   16 | 6 Dec  | **EXAM 3** (12:30 - 2:30 in 118 Prescott)                                                                                                      |                                                                                                                                                                 |                |

 <sup><a name="fnote1">1</a></sup> No, I do not expect you to read all 1800+ pages.  Read Chapters 5, 6, 8, 9, 10.  Experiment w/ the examples.

## Conduct

### Academic Integrity

I take academic integrity seriously.  You are expected to reference sources appropriately in your written work.  **You are _absolutely expected_ to reference _any_ third party computer code that you include in your assignments.  You should also not copy the work of others**. Simply copying someones work and changing variable names **is still plagiarizing** their work.

In previous years, I caught several students in this course for plagiarizing - ask around.  All of them were found to have plagiarized, and all suffered several penalties including a note on their transcript that they plagiarized.  You need to be very, very careful not to inappropriately use the work of others.

I will always assume the work you submit is your own, so you are responsible for its content.

### Working Together

You may ask your classmates about general ideas related to the course, and you are free to demonstrated to one another how this or that idea works.  **HOWEVER**, you are expected to complete your assignments on your own, without help from anyone else.  If you use other sources, please cite.  If I determine that you are citing too many sources rather than doing your own work, your score for that assignment will indicate that you have not shown mastery of the material.

### Academic Misconduct

If I suspect that you have committed Academic Misconduct of any form (plagiarizing, cheating, etc.), I am required to report the incident to the Student Advocacy and Accountability office, and they will follow-up. Definitions of academic misconduct are provided [here](https://saa.lsu.edu/code-10_2-academic-misconduct).

### Commitment to Community

You should be familiar with the LSU Commitment to Community, which is outlined [here](http://saa.lsu.edu/code-1-commitment). You should also be familiar with the LSU Code of Student Conduct, which is available [here](http://saa.lsu.edu/code).  You are expected to follow the Commitment to Community during your time in this class and when working on assignments outside of class.  Students who do not respect the instructor(s) or other members of the class will be asked to leave the lecture immediately.  This includes using the telephone, texting, or using the internet for non-class-related purposes during the lecture.