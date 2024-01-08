---
layout: page
title: Syllabus and Course Policy
description: >-
    CS 4650. Course policies and information.
---

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## Resources

- [Piazza](https://piazza.com/gatech/spring2024/cs7650a) (announcements, questions, discussion)
- [Gradescope](https://www.gradescope.com/courses/697909) (homework assignments, submission, and grading)
- [Canvas](https://canvas.gatech.edu/) (we will use Gradescope/Piazza instead of Canvas) 
- [Tentative Course Schedule](https://docs.google.com/spreadsheets/d/1YPCGxG5w7meDsA2ysbG4C5ZFPd89nseoih5SP3wBVjU/edit?usp=sharing)


## Textbook(s) and Computing Resources

There are two excellent NLP textbooks that are freely available online. Readings will be assigned from both. There is value in seeing multiple perspectives on the same material. If a concept you encounter seems confusing at first, try reading about it in the other book to get a different perspective.

- [Dan Jurafsky and James H. Martin. Speech and Language Processing (3rd Edition)](https://web.stanford.edu/~jurafsky/slp3/)
- [Jacob Eisenstein Natural Language Processing](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
- There will be other assigned readings as well.

While the textbooks are free, this class will incur a cost of $20-50 for course materials (i.e., GPU computing using [Google Colab](http://colab.research.google.com/)). 

The programming assignments will ask you to implement state-of-the-art natural language processing algorithms using neural networks. For this purpose we will use Pytorch, and you will require access to GPUs. The class will use Google Colab, which provides easy access to GPUs. We recommend signing up for Colab Pro (once you start working on the part of the homework that uses PyTorch). This costs $10/month, which is roughly equivalent to the cost of a textbook over the course of the semester. This will provide a better experience working on the homework assignments by providing you access to better GPUs, etc. We have investigated other options to provide students access to GPUs for the homework assignments (Google cloud credits and PACE/ICE), and have found that Colab Pro is the best solution for a class such as this.


## Prerequisites

This is an advanced-level AI class that covers deep learning and other machine learning models in the context of processing text data. To succeed in this class, you will need a very strong math and programming background that can sufficiently make you feel at ease in the machine learning class (CS 4641/7641). It would be even more ideal, if you have taken the deep learning class (CS 4644/7643). The course assumes mastery of mathematical concepts in probability, linear algebra, and multivariable calculus. You should be comfortable working on medium-to-large software projects in Python, learning and using new libraries (in particular, PyTorch) independently very quickly, and debugging code when there is no clear error messages. Nearly all programming assignments will be in PyTorch for this class, working extensively with vectors/matrices/tensors. If you have not used PyTorch before but plan to take this class, we recommend [start learning it now](https://cocoxu.github.io/CS4650_spring2023/slides/PyTorch_tutorial.pdf) as you read this message. 

There will be a math background test (due in the 1st week) and a programming homework (due in the 2nd week) at the beginning of the semester. If you have difficulty to handle them, you should expect a lot of extra work and challenges to catch up -- we strongly suggest you wait and take this class in a later semester. 

(**For students on the wait list:** we don’t have any additional information on whether you will be able to enroll in the course, but if you plan to take the class, please complete and submit Problem Set 0 by the due time (late penalty will apply if submitted later). If you get off the wait list, you will be automatically added to Gradescope after about a day. You can also post a private message on [Piazza](https://piazza.com/class/l6vgipz0vsm1kk) to get the access code to Gradescope. If you still cannot access Gradescope by the due date, please email your submission to the instructor and all TAs.)


## Assignments / Grading

Graded work will include both written and programming assignments. Assignments should be submitted to Gradescope by 11:59pm on the day they are due. Please email your homework to the instructor in case of any technical issues with submission. 

Each student will have 6 flexible days to turn in late homework throughout the semester. The late days will be applied to homework assignments in the order of submission. As an example, you could turn in the first homework 2 days late and the second homework 3 day late without any penalty. After that you will loose 5% for each day an assignment is handed in late. These 6 late days are meant for personal emergencies; if you use late days for non-emergency situations but later encounter emergencies in the semester, you will not be given extra late days. No late days will be allowed for the final project, due to the tight deadline for posting the final grades as required by the university. Late days will be counted in 24-hour chunks to the entire homework and rounded up, i.e., if you are late for 10 hours for a homework, that will count as 1 late day. 

All homework will be rescaled proportionally into the final numerical grade, which will then be mapped to letter grade according to a cutoff based on the overall class grade distribution. The standard cutoff is 90/80/70% for A/B/C, but we may curve up (never down), i.e., use lower cutoffs than these. The cutoffs will only be determined after we grade the final project at the end of the semester. Students must obtain at least 50% overall grades to pass the class. 



### Programming Assignments (Projects) - 30%

We plan to assign three programming assignments (besides a programming background test) that provide hands-on experience implementing algorithms discussed during lecture.  The assignments are in Python, and make use of [Numpy](https://numpy.org/) and [Pytorch](https://pytorch.org/).  These will require non-trivial computation to complete; we recommend using Google's [Colab](http://colab.research.google.com/) platform which provides easy access to GPUs. Completing these projects will require waiting for your models to train (this can range from about 30 minutes to hours depending on the efficiency of your implementation), so we strongly recommend starting work on these programming assignments well in advance of the deadline.  If you start working on an assignment the day before it is due, it is unlikely you will be able to complete it on time.


### Written Assignments (Problem Sets) - 20%

The written assignments will mostly be mathematical/computational.  You can scan and upload your solution to Gradescope. Please write answers clearly, since we won't be able to provide credit for answers that we are not legible.

### Midterm Exam - 15%

The midterm will be similar in format to the written assignments (problem sets). It will be in-class and close-book after the spring break (there will be no make-up exam). Students are expected to attend every class during the semester, unless they have obtained official approval for absense from the Office of the Dean of Students.  We will set the exact date for midterm exam one month before the exam based on the class progress (e.g., student homework completion). 


### Final Project - 30%

The final project is an open-ended assignment, with the goal of gaining experience applying the techniques presented in class to real-world datasets. Students should work in groups of 2-4. It is a good idea to discuss your planned project with the instructor to get feedback. The final project report should be 2-4 pages. The report should describe the problem you are solving, what data is being used, the proposed technique you are applying in addition to what baseline is used to compare against.


The grading rubric for the final project is as follows:

* Clarity (1-5) For the reasonably well-prepared reader, is it clear what was done and why? Is the report well-written and well structured?
* Originality / Innovativeness (1-5) How original is the approach? Does this project break new ground in topic, methodology, or content? How exciting and innovative is the work that it describes?
* Soundness / Correctness (1-5) First, is the technical approach sound and well-chosen? Second, can one trust the claims of the report – are they supported by proper experiments, proofs, or other argumentation?
* Meaningful Comparison (1-5) Does the author make clear where the problems and methods sit with respect to existing literature? Are any experimental results meaningfully compared with the best prior approaches?
* Substance (1-5) Does this project have enough substance, or would it benefit from more ideas or results?  Note that this question mainly concerns the amount of work; its quality is evaluated in other categories.
* Overall (1-5) 


Students will also give presentations on recent research in class. 


### Participation - 5%

You will receive credits for engaging in discussion in class, and answering questions related to the homework on Piazza, acting politely and respectfully towards the teaching staff and other students in the class. 


## Academic Integrity

Any assignment or exam that you hand in must be your own work (with the exception of the final group project). However, talking with others to better understand the material is strongly encouraged. Copying a solution or letting someone copy your solution (intentionally or accidentally) is considered cheating. Everything you hand in must be your own work. Code you hand in must be written by you, with the exception of any code provided as part of the assignment. Any collaboration during an exam is considered cheating. Any student who is caught cheating will be given a zero grade and will be reported to the Office of Student Integrity. Please don't take a chance - if you are having trouble understanding the material, let us know and we will be happy to help.
