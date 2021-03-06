---
title: "Syllabus - MSCR596 - Advanced Data Management in R"
---
<h1><style scoped>h1 { color: navy; }</style>
Course Syllabus - MSCR596 - Advanced Data Management in R</h1>

Time/Location
------------

Time: Thursdays 10:00-11:50 am Eastern (U.S.) Time
Room: GCR 107 or remote

Instructor
--------

Beau B. Bruce, MD, PhD  
Deputy Branch Chief and Acting Analytics Team Lead, Enteric Diseases Epidemiology Branch
<br/>Division of Foodborne, Waterborne, and Environmental Diseases
<br/>National Center for Emerging and Zoonotic Infectious Diseases
<br/>Centers for Disease Control and Prevention

Adjunct Assistant Professor of Ophthalmology, Neurology, and Epidemiology  
Emory University  
E-mail: <bbbruce@emory.edu>  
Office Hours: By appointment

Disclaimer
----------

The statements contained throughout this course are solely those of the instructor and do not necessarily reflect the views or policies of the Centers for Disease Control and Prevention.

Course Description
----------

R is the most popular statistical programming language in the world. R is used for data analytics and visualization in numerous fields, including medicine, and by some of the most successful companies and organizations in the world. Amazingly, R is open-source and freely available! However, many students in the biomedical sciences have limited experience with programming and this creates a barrier to their adoption of tools like R in favor of less flexible and less powerful graphical user interface-based systems. Avoiding coding also hampers one’s ability to process and analyze data effectively, efficiently, and reproducibly.

The overarching objective of this elective course is to introduce the R statistical programming language with a focus on data management tasks (importing, cleaning, reshaping, transforming, and exploring data) and reproducible statistical analysis. R packages for the creation of publication-quality figures and tables will be introduced further extending the student’s capabilities to create a complete and reproducible data-processing pipeline from raw data to presentation and publication. While we intend to introduce some of the statistics available in R along with packages for logistic and time-to-event modeling, we will not spend much time on how to perform a given statistical analysis in R nor will we cover the underlying statistical theory of analyses. Nevertheless, anyone who successfully completes the course will have acquired the skills to find and run any common statistical analysis available in R while gaining the much more valuable skills of creatively solving challenging data management problems.



Course Competencies
-------------------

As an elective course, this course extends the core competencies of the MSCR program by providing basic education in statistical programming which will make the student better able to perform their own data analyses, summaries, and visualizations.

Learning Objectives/Outcomes
----------------------------

At the end of the course, students will be able to:

1.   Use R for the importing, cleaning, reshaping, and transforming of data
2.   Use R to create basic programs for consistent and reproducible data management and analysis
3.   Produce publication ready figures and tables directly with R


Prerequisites
-----------
1. Completion of or concurrent enrollment in a basic statistics course covering at least linear regression (BIOS/MSCR 500 or equivalent)
2. A readiness to tackle problems and to think creatively to solve them

Textbook
--------
The course will provide all necessary materials through the
[course website, https://advdatamgmt.github.io](http://advdatamgmt.github.io), but the following
optional books are suggested if you would like a book to supplement
your studies:

- Free books:
    - [Analysis of Epidemiological Data using R and Epicalc](https://cran.r-project.org/doc/contrib/Epicalc_Book.pdf)
    - [A Little Book of R for Biomedical Statistics
](http://a-little-book-of-r-for-biomedical-statistics.readthedocs.org/en/latest/index.html)

- Paid books:
    - [R for Dummies](http://www.amazon.com/R-Dummies-Andrie-Vries/dp/1119055806/)
    - [A Beginner's Guide to R](http://www.amazon.com/Beginners-Guide-Use-Alain-Zuur/dp/0387938362/)

There is also an enormous amount of material within the R software and in the
[CRAN Contributed Documentation, https://cran.r-project.org/other-docs.html](https://cran.r-project.org/other-docs.html)
where you will find tutorials and other documentation in 20 different languages.

Evaluation
----------
Class participation (40%)
<br/>Homework assignments (40%)
<br/>Final project (20%)

Grades will be assigned as follows with partial points rounded up for all levels:

-	A = 94 or above
-	A- = 87-93
-	B+ = 80-86
-	B = 74-80
-	C = 60-73
-	F = below 60


Course Structure
----------------

As much as possible we will try to have a "flipped classroom" where we spend 
the majority of class time answering questions that arise outside of class and
on working problems and programming challenges together.  However, depending on
the appropriateness of material for studying at home, timing, and progress we 
will cover some elements didactically.

Class will generally consist of students working on swirl lessons at home 
through R/RStudio.  This will be explained.  Homework grades will be based on
successful completion of these lessons submitted via Google Forms. 

In addition, there will be a final project where you transform a raw
data file into a well-formatted, programmatically created report using
the principles learned throughout the class.  The final product
requires at least one "substantial" figure and one "substantial" table
produced directly by R.

COURSE POLICIES
-	Unexcused absences 3% off final grade after first
-	Excused absences will be allowed with rare exception if you contact the instructor BEFORE class with an explanation
-	If you contact the instructor DURING/AFTER class, your absense will only be excused in the case of extraordinary circumstances (e.g., your illness or that of someone you care about)
-	Assignments should be submitted prior to the start of the following week’s class

As the instructor of this course I endeavor to provide an inclusive learning environment. However, if you experience barriers to learning in this course, do not hesitate to discuss them with me and the Office for Equity and Inclusion, 404-727-9877.  

Laney Graduate School Policies
------------------------------

### Accessibility and Accommodations

Accessibility Services works with students who have disabilities to provide reasonable accommodations. In order to receive consideration for reasonable accommodations, you must contact the Office of Accessibility Services (OAS). It is the responsibility of the student to register with OAS. Please note that accommodations are not retroactive and that disability accommodations are not provided until an accommodation letter has been processed. 

Students who registered with OAS and have a letter outlining their academic accommodations are strongly encouraged to coordinate a meeting time with me to discuss a protocol to implement the accommodations as needed throughout the semester. This meeting should occur as early in the semester as possible.  

Contact Accessibility Services for more information at (404) 727-9877 or accessibility@emory.edu. Additional information is available at the OAS website at http://equityandinclusion.emory.edu/access/students/index.html

Honor Code
----------

*You are bound by Emory University’s Student Honor and Conduct Code.* The Georgia CTSA MSCR Program requires that all material submitted by a student fulfilling his or her academic course of study must be the original work of the student.  Violations of academic honor include any action by a student indicating dishonesty or a lack of integrity in academic ethics. Academic dishonesty refers to cheating, plagiarizing, assisting other students without authorization, lying, tampering, or stealing in performing any academic work, and will not be tolerated under any circumstances. 

The Laney Graduate School Honor Code states: “A writer’s data, facts, ideas, and phraseology should be regarded as his/her property. Any person who uses a writer’s data, facts, ideas, or phraseology without giving due credit is guilty of plagiarism.” 

Link: http://gs.emory.edu/handbook/honor-conduct-grievance/honor/index.html



## *Tentative* Schedule

<table>
<style scoped>
table {
  border: solid;
  border-collapse: collapse;
}

td, th {
  border: solid;
  padding: 5px;
  }

td[colspan="2"] {
	text-align: center;
}

ul {
  margin: 0;
}
</style>
<tr><th>Date</th><th>Title</th><th>Topics</th></tr>
<tr><td>Aug 29</td><td>The Realm of R: A Gentle Introduction</td><td><ul><li>course introduction</li><li>arithmetic
		operators</li><li>atomic data types</li></ul></td></tr>
<tr><td>Sep 5</td><td>The Care and
	Feeding of the Realm's Creatures</td><td><ul><li>vectors &
	factors</li><li>lists & data.frames</li><li>formatting code</li></ul></td></tr>
<tr><td>Sep 12</td><td>Creating New Creatures: Functions</td><td><ul><li>functions</li><li>importing data (csv,
		Excel)</li></ul></td></tr>
<tr><td>Sep 19</td><td>Branching Out and Feeling Loopy</td><td><ul><li>branch logic</li><li>loop logic</li></ul></td></tr>
<tr><td>Sep 26</td><td>Food Prep: Slicing & Dicing Data</td><td><ul><li>concatenation</li><li>merging</li><li>subsetting</li><li>transforming</li></ul></td></tr>
<tr><td>Oct 3</td><td>Postcards from Your Visit: R Base
	Graphics</td><td><ul><li>high-level plotting
		functions</li><li>low-level plotting</li><li>saving plots</li></ul></td></tr>
<tr><td>Oct 10</td><td>Well-dressed R: Rmd and
	knitr</td><td><ul><li>reproducible research</li><li>R markdown</li><li>knitr</li></ul></td></tr>
<tr><td>Oct 17</td><td>Delicacies of the Realm: Specialized Data
	Types</td><td><ul><li>text
		processing</li><li>dates</li><li>missing and invalid data</li></ul></td></tr>
<tr><td>Oct 24</td><td>Applying yourself</td><td><ul><li>apply family
		of functions</li><li>dplyr</li><li>table creation</li></ul></td></tr>
<tr><td>Oct 31</td><td>Masterpieces of the
Realm</td><td><ul><li>ggplot</li><li>layers</li><li>facets</li><li><b>PROJECT
PROPOSAL DUE</b></li></ul></td></tr>
<tr><td>Nov 7</td><td>On the catwalk: Advanced Modeling in
	R</td><td><ul><li>rms</li><li>linear regression</li><li>logistic
		regression</li><li>time-to-event analysis</li></ul></td></tr>
<tr><td>Nov 14</td><td>Outside the lines: More Advanced Modeling in
	R</td><td><ul><li>non-linear
	terms</li><li>interactions</li><li>modeling
	strategy</li><li><b>APPROVED PROPOSAL DUE</b></li></ul></td></tr>
<tr><td>Nov 21</td><td colspan="2">Catch-up/Review</td></tr>
<tr><td>Nov 28</td><td colspan="2"><b>NO CLASS MEETING - THANKSGIVING</b></td></tr>
<tr><td>Dec 5</td><td colspan="2">Catch-up/Review</td></tr>
<tr><td>Dec 13</td><td colspan="2"><b>NO CLASS MEETING - FINAL PROJECT DUE</b></td></tr>
</table>
