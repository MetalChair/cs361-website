---
title: Syllabus
keyword: syllabus
---

# Overview

This class is about two things. First, it's about the abstractions of the
operating system that sit between your code and the hardware of the computer.
Understanding how these features work allows you to make your programs fast and
efficient beyond their Big-O runtime. 

Second, this class is about critical thinking abd problem solving about
practical computer science problems. The engineers who designed the operating
systems we use today had to solve hundreds of hard engineering problems that no
one had ever solved before. This course is designed to help you gain the
problem solving skills necessary to solve hard practical computer science
problems. This is directly appicable to three domains:

1. You will be ready to reason about and design performant software systems, as
   well as diagnose and solve problems throughout the software stack that
   supports modern software (the software itself, along with its libraries,
   operating system, computer hardware, and how those pieces interact).
2. You will be ready to decompose and solve the types of questions that are
   asked in technical interviews at many of the best employers of software
   engineers.
3. By practicing technical problem solving within a specific context, you train
   yourself to better decompose, communicate about, reason about, and solve
   technical problems more broadly.

In addition to oral and written problem solving exercises, there are also a
collection of programming assignments. Completing these assignments will give
you experience with the many steps along the path from source code to running
program, memory management and virtual memory, process creation, communication
and control, and a healthy dose of concurrent programming.

By the end of this course, you will have a good understanding of the main
elements that work together to form modern computing environments. You will
have acquired some familiarity with standard diagnostic tools, debuggers,
dynamic memory allocation, concurrent programming, and file I/O both with
physical files and network sockets.


# Prerequisites
The main conceptual prerequisites for this class are CS 211 (the C part), CS 261
(machine organization), and CS 251 (data structures). A solid understanding of
the theory of how things are stored in the computer, as well as the theory of
how a processor executes instructions, as well as a basic understanding of
programming (and specifically programming in C) are the tools you'll need to
succeed in this class.

# Course Announcements
Whenever possible, course information will be conveyed using this website.
Course discussion will happen via Piazza. Course assignments and assignment
grades will be collected and returned through Gradescope. We will use
(TBD) for synchronous class sessions. You are responsible
for checking this website for the reading schedule and ensuring that you
complete all assignments, and keeping up to date on Piazza for any
corrections/clarifications regarding assignments or other important
information.

# Peer Instruction 
Typically, this course is taught using [Peer Instruction][pi], a teaching model
which places stronger emphasis on classroom discussion and student interaction.
This doesn't map so well onto remote instruction, but we will be trying to
approximate it the best we can. Typical peer instruction consists of readings
before class, a short beginning of class quiz, and a collection of discussion
questions during class that you complete by yourself, discuss in small groups,
and then discuss with the entire class.

This semester, the regularly scheduled activities for class are:

1. Throughout the week: there will be assigned readings and video lectures.
1. Mondays: there is a synchronous, online, required lab session with a short
   activity and a Gradescope quiz based on that activity that must be completed
   by 5pm.
2. Tuesdays: open Q&A office hours. During exam weeks, these will be exam review.
3. Thursdays: Content quizzes are due at 12:30pm. Discussion questions are due at 12:30pm.
   Discussion questions are **loosely** based on exam question style, structure, and content. During
   class, we will **either** do an in class activity, or do the exam.
1. Fridays: Homework assignments are due at 5pm. This will usually be on
   Fridays but there are some exceptions to give you time to complete the
   relevant homework before the related exam.

Like peer instruction, we will still have required readings and required
videos. Rather than having a quiz at the beginning of class, there will be a
quiz graded for correctness each week based on that content. These will be
released on Mondays and due at 12:30pm on Thursdays.

Each week there will also be one set of discussion questions. These questions
are meant to be considered by yourself, but you are encouraged to discuss the
questions in small groups. You must answer these questions on Gradescope as
well, but you will only be graded on completeness and effort, not on
correctness. Each week's discussion question is only worth .13% of your grade,
so don't stress if you miss them. However, thinking through the answers to
these questions will help a lot on the exams.


{% capture homework_policy %}{% include homework_policy.md %}{% endcapture %}
{{ homework_policy | markdownify }}


# Evaluation
Grades are curved based on an aggregate course score. This means that the
course score cut-offs for an A, B, C etc. are not defined ahead of time: these
will be set after the end of the course. There is no quota for grade
assignments, and there will be a hard "ceiling" for the curve of 90/80/70/60
(i.e. the cutoff for an A will never be higher than 90% of all points possible
in the course). Each individual quiz/problem set/homework/exam is worth the
same as each other quiz/problem set/homework/exam - i.e. each of the 13 reading
quizzes is worth 10%/13 ≈ .77% of your final grade.

The course grade weighting is:

| Task | % of total grade     |
| ---- | ----------------     |
| Video/reading quizzes (15, lowest two dropped)          | 10  |
| Class activities (11, one dropped) | 8*  |
| Discussion questions (11, one dropped) | 2 |
| Lab activities (14, lowest two dropped)                  | 10  |
| Homeworks (6, lowest is dropped)     | 30  |
| Exams (5, lowest is dropped)         | 40  |
{: class="table table-striped"}

## Grade components

Reading quizzes, lab activities, homeworks, and exams are all graded for
correctness. Homeworks are autograded using a script, so it is important that
you submit your code early to (a) make sure you can successfully submit it and
(b) that your code can pass the autograder tests. We do not give partial credit
for incomplete or partially correct code. However, we do manually inspect and
give full credit for anyone whose code works correctly, but was graded
incorrectly due to the autograder. Please contact the instructors via Piazza if
you think your homework was graded incorrectly.

The Thursday session of this course is required; it is either the time we take
an exam, or when we do in-class activities. You can achieve full participation
credit for coming to class and participating in the activity (which will almost
always be Kahoot or something Kahoot-like). You won't get class points for
correct answers, only bragging rights. You can miss one of these sessions with
no penalty.

The exams are broken out by class module. The first four happen during the
semester, and the final exam slot is used for the fifth exam. While the exams
aren't technically cumulative (you will not be tested directly on the same
topic twice), the concepts in class build on each other and you are responsible
for remembering and applying concepts from the previous modules on later exams.


[pi]: https://en.wikipedia.org/wiki/Peer_instruction
[ckanich]: mailto:ckanich@uic.edu


#  Class Participation

Class participation is an incredibly important component of this course regardless of whether it is
online or in person. Unfortunately, "participation" is very hard to grade. The 8% that you get from
showing up on Thursdays is just from showing up - you're encouraged to participate, because it will
help you do well on the exams, but there's no requirement that you talk a certain amount of times or
anything like that. For the 2% that you get from the discussion questions, you aren't required to
get the questions correct or write several paragraph long answers to get full credit.

## Participation extra credit
Students who meaningfully engage with each other, either through Piazza or during
the class discussion sessions can raise their discussion grade up to a maximum of 18/8.
Additionally, I will consider high quality discussion question answers for students who are very
close to any grade cutoffs at the end of the semester. Submitting bug fixes or providing test cases
for homework assignments can also earn extra credit. 

# Textbook

We will be using **Computer Systems, a programmer's perspective** by Randal E.
Bryant and David R. O'Hallaron, 3rd edition, as our main textbook. We will be
covering the content from Chapter 7 through the remainder of the book.

You may also find **The C Programming Language** by Kernigan and Ritchie
(colloquially referred to as K&R) a helpful reference when writing C programs.

# Overcoming challenges enables growth

This is not a lecture-oriented class or one in which mimicking prefabricated
examples will lead you to success. You will be expected to work actively to
construct your own understanding of the topics at hand, with the readily
available help of the instructors and your classmates. Many of the concepts you
learn and problems you work will be new to you and ask you to stretch your
thinking. You will experience frustration and failure before you experience
understanding. This is part of the normal learning process. Your viability as a
professional in the modern workforce depends on your ability to embrace this
learning process and make it work for you. You are supported on all sides by the
professor and your classmates. But no student is exempt from the process and the
hard work it entails.


# Mental health

We value your mental health and emotional wellness as part of the UIC student
experience. The UIC Counseling Center offers an array of services to provide
additional support throughout your time at UIC, including workshops, peer
support groups, counseling, self-help tools, and initial consultations to speak
to a mental health counselor about your concerns. Please visit the Counseling
Center website for more information (https://counseling.uic.edu/). Further, if
you think emotional concerns may be impacting your academic success, please
contact your faculty and academic advisers to create a plan to stay on track.



# Student Disabilities

If you have a disability that might impact your performance in this course or
otherwise requires special accommodation, please contact me as soon as possible
so that appropriate arrangements can be made. Support is available through the
[Disability Resource Center](https://drc.uic.edu/). You will need to
contact them to get your disability documented before accommodations can be
made.



#  Academic Integrity

Consulting with your classmates on assignments is encouraged, except where
noted. However, turn-ins are individual, and copying code from your classmates
is considered plagiarism. For example, given the question "how did you do X?", a
great response would be "I used function Y, with W as the second argument. I
tried Z first, but it didn't work". An inappropriate response would be "here is
my code, look for yourself". **You should never look at someone else's code, or
show someone else your code.** Either of these actions are considered academic
dishonesty (cheating) and will be prosecuted as such.

To avoid suspicion of plagiarism, you must specify your sources together with
all turned-in materials. List classmates you discussed your homework with and
webpages from which you got inspiration. Plagiarism and cheating, as in copying
the work of others, paying others to do your work, etc, is obviously prohibited,
and will be reported.  We will be running MOSS, an automated plagiarism
detection tool, on all handins.

There are consequences to cheating on two levels - the consequences for your
grade, and the consequences at the university level.  Within class, the first
time cheating on a programming assignment or problem set will result in a 0 on
the assignment.  A second time on a programming assignment, or first time on an
exam will result in failing the class. Egregious cheating on a programming
assignment (including but not limited to purchasing a solution online) is also
grounds for failing the class.

I report all suspected academic integrity violations to the dean of students.
If it is your first time, the dean of students allows you to informally resolve
the case - this means the student agrees that my description of what happened is
accurate, and the only repercussions on an institutional level are that it is
noted that this happened in your internal, UIC files (i.e. the dean of students
can see that this happened, but no professors or other people can, and it is not
in your transcript).  If this has happened before, in any of your classes, this
results in a formal hearing and the dean of students decides on the
institutional consequences.  After multiple instances of academic integrity
violations, students may be suspended or expelled.  For all cases, the student
has the option to go through a formal hearing if they believe that they did not
actually violate the academic integrity policy.  If the dean of students agrees
that they did not, then I revert their grade back to the original grade, and the
matter is resolved.
