---
author:
- Raffi Khatchadourian
date: August 2016
title: 'CSCI 499 §002 \# 12092 Fall 2016, The Capstone Course'
---

Finding Me {#finding-me .unnumbered}
==========

 

  --------------- ------------------------------------------------------------
          E-mail: raffi.khatchadourian@hunter.cuny.edu
           Phone: Please call the Computer Science office at (212) 772-5213.
          Office: 1000C, Hunter North Building
    Office Hours: Monday and Wednesday 12:00–1:00pm
  --------------- ------------------------------------------------------------

\
In addition, messages can be left for me at the Computer Science
Department office, which is located in N-1008 and is reachable at
(212)772-5213.

Please note that I will only read and reply to email sent from CUNY
email addresses for FERPA reasons.

Text {#text .unnumbered}
====

There will be no text book for this course.

Goals {#goals .unnumbered}
=====

There are two related goals for this class. The first is to assess the
students’ mastery of the department’s stated learning goals. The second
is to assess the department’s effectiveness in addressing these goals.
For a complete list of these goals, see\
http://ww5.hunter.cuny.edu/csci/for-students/learning-goals-for-hunter-college-students.

Grades {#grades .unnumbered}
======

Grades will be based on a project, presentations, attendance, etc. The
project, worth 35% of your grade, will involve programming a
client-server distributed application. The server must support a RESTful
web service. The client can be built on a technology of your choosing
that supports the HTTP/S protocol and must communicate with the
aforementioned server via REST calls. Moreover, there must be an aspect
of security or privacy in your application, e.g., two-factor
authentication or encrypted data. You will work with a team of 2 to 4
other students. This grade will be determined in part by my evaluation
of the project and in part by your team members evaluation of your
contribution. See the appendix for a complete description. Periodic
presentations and written reports, reporting on tools and progress, will
account for 55% of your grade. Professional presence (5%) and attendance
(5%) will account for the rest of your grade.

Listed below is the complete breakdown:

  ---------------------------------------- ------
  Project                                  35%
  Presentations (expect: 2 for progress)   25%
  Written assignments (progress reports)   20%
  Periodic peer reports                    5%
  Final peer report                        5%
  Professional presence                    5%
  Attendance                               5%
  Total                                    100%
  ---------------------------------------- ------

Academic Integrity {#academic-integrity .unnumbered}
==================

Hunter College regards acts of academic dishonesty (e.g., plagiarism,
cheating on examinations, obtaining unfair advantage, and falsification
of records and official documents) as serious offenses against the
values of intellectual honesty. The college is committed to enforcing
the CUNY Policy on Academic Integrity and will pursue cases of academic
dishonesty according to the Hunter College Academic Integrity
Procedures.

ADA Compliance {#ada-compliance .unnumbered}
==============

In compliance with the American Disability Act of 1990 (ADA) and with
Section 504 of the Rehabilitation Act of 1973, Hunter College is
committed to ensuring educational parity and accommodations for all
students with documented disabilities and/or medical conditions. It is
recommended that all students with documented disabilities (Emotional,
Medical, Physical and/ or Learning) consult the Office of AccessABILITY
located in Room E1124 to secure necessary academic accommodations. For
further information and assistance please call (212-772-4857)/TTY
(212-650-3230).

Cell Phones, &c. {#cell-phones-c. .unnumbered}
================

I expect all cell phones, computers, etc. to be inaudible during class.
I expect running computers to be used for class-related purposes only,
like code development or appropriate research. Any student with an
electronic device that disrupts the class or that is used
inappropriately (e.g. talking, texting, tweeting, emailing, mu\*ing,
surfing, etc.) during class will lose two (2) points from their final
average (per occurrence).

Projected Project Time Line {#projected-project-time-line .unnumbered}
===========================

Day 3

:   (Sep 1) Groups and projects must be finalized.

Day 5

:   (Sep 12) Group details due. This should contain a “group authored”
    section detailing what each group member is expecting to do.

Day 9

:   (Sep 26) Progress reports start. These should be roughly 10 minute
    presentations, one per group per week, delivered by a different
    member of the group each week.

Day 28

:   (Dec 8) Final demonstration of completely working project.

Final Day

:   (Dec 21) Final written report including your reflections on the
    project and the final demo and your evaluation of co-group-members.

Appendix A-Project grade {#appendix-a-project-grade .unnumbered}
========================

The number you receive for your project grade is calculated as follows:
Let ${\cal G}$ be the set of people in your group, and $G$ be the
overall grade of the final project (a number between 0 and 30). Let
$g_{i,j}, i\neq j, i,j\in{\cal G}$ be the grade $i$ gives to $j$. Then
$j$’s grade on the project is
$$G_j =  G \times \sum_{\substack{i\neq j\\i\in{\cal G}}}\left(\frac{g_{i,j}}{\sum_{\substack{i\neq j\\j\in {\cal G}}} g_{i,j}}\right)$$
