# LMS-Sentiment: Scenario

> **Note**: entirely hypothetical

In order to encourage thoughtful discourse and more frequent writing, students
at a large and overcrowded public high school are required to participate in an
online discussion forum for their English class.

Given an eighteen-week semester, the school expects each student to contribute
to classroom discussions at least ten times. The student will be loosely graded
the quality of their participation. Actively constructive comments earn more
points than mere participation. A distinctly negative ("trolling") comment,
however, will be treated as worse than failing to participate.

| Points | Interpretation |
| ------ | -------------- |
| -1     | Trolling       |
| 1      | Participated   |
| 2      | Constructive   |

At the end of the semester, grades will be assigned based on the total points earned.

| Total Points | Grade    |
| ------------ | -------- |
| 20           | 100 (A+) |
| 19           | 98 (A+)  |
| 18           | 96 (A)   |
| ..           | ..       |
| 15           | 90 (A-)  |
| 14           | 88 (B+)  |
| ..           | ..       |
| 10           | 80 (B -)  |
| ..           | ..       |
| 5            | 70 (C-)  |
| 4            | 68 (D+)  |
| 3            | 66 (D)   |
| 2            | 63 (D)   |
| 1            | 60 (D-)  |
| 0            | 57 (F)   |

This grade will then be weighted equal to one exam.

The program is treated as a pilot in the first year, enrolling only the tenth
grade class. At the end of the year, the school district's staff data scientist
analyzes the grades and finds a small, positive, correlation between discussion
participation grade and improved classroom grades through the course of the
semester (that is, students with good participation also improved their scores
over the course of the semester).

Based on this analysis, the instructional leadership team decides to implement
the program in all grades throughout the high school.

And is summarily faced with a small revolt among the teachers.

"Doesn't leadership realize how much extra time this takes? On top of my regular
classroom workload, I had to rate one comment from most of my students, on most
weeks of the school year. That might not sound like much, but it really adds
up!"

Getting wind of this, the data scientist offers a solution: "provide me with all
of the student comments and classifications from the prior year, and I'll build
an algorithm for grading this next year's comments. No intervention required -
unless a student thinks the grade has been unfair. That is the one condition I
ask: no automated system is foolproof. If a student thinks the system has been
unfair, then the teacher should review and have the ability to override the
algorithm."
