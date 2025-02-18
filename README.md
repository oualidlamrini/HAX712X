# HAX712X: Software development for data science

(Almost) everything you need to know as an applied mathematician / statistician concerning coding and system administration.

## Teachers

- Joseph Salmon : joseph.salmon@umontpellier.fr,
- Benjamin Charlier : benjamin.charlier@umontpellier.fr

This course material was improved with the help of some students including:

- Amelie Vernay
- Tanguy Lefort


## Prerequisite

Students are expected to know basic notions of probabilities, optimization, linear algebra and statistics for this course.
Some rudiments on coding is also expected (if, for, while, functions) but not mandatory.

## Course description

This course focuses on discovering good coding practices (the language used being Python, but some element of bash and git will also be useful) for professional coding.
A special focus on data processing and visualization will be at the heart of the course.
We will mostly focus on basic programming concepts, as well as on discovering the Python scientific libraries, including ```numpy, scipy, pandas, matplotlib, seaborn```.
Beyond `pandas` ninja skills, we will also introduce modern practices for coders : (unitary) tests, version control, documentation generation, etc.


1. BC : (09/09/2022) [Introduction to linux essentials and command line tools: regexp, grep, find, rename](Courses/Bash/)

2. BC : (16/09/2022) [IDE: VScode](Courses/IDE/), [Python virtual env: Anaconda](Courses/Venv/), [Python virtual environment](Courses/Venv/), terminal, etc.

3. BC : (23/09/2022) [Git: a first introduction, `github`, ssh key creation, various git commands, conflict, pull request](Courses/Git/); see also [Bonus/](Bonus/), [hands on git](Courses/Git/)

4. BC (quiz 1) + JS : (30/09/2022) [Create a Python Module](Courses/Python-modules/), [classes (`__init__`, `__call__`, etc...), operator overloading, files handling](Courses/Classes_n_Exceptions/),

5. JS : (03/10/2022 + 07/10/2022)  [unit tests](Courses/Test/)

6. JS : (10/10/2022 + 14/10/2022)  [Pandas: first steps / missing data](Courses/Pandas/)

7. JS : (17/10/2022 + 21/10/2022) [`scipy, numpy`: Images/channel](Courses/ScipyNumpy/)

8. JS (quiz 2) : (28/10/2022) [Sparse matrices,](Courses/TimeMemory/) [graphs and memory](Courses/TimeMemory/)

9. BC : (18/11/2022) [Documentation with Sphinx](Courses/Docs/)

10. JS + BC : (09/12/2022) The end:  Project presentations


## Grading


### Tests: 20 % of the final grade
Short quiz of 20 min each (on Moodle). This will be a personal work.

- Quiz 1 BC (**30/09/2022**, 10%)
- Quiz 2 JS (**28/10/2022**, 10%)


### Project: 80% of the final grade


**Warning:** the precise details of the projects might evolve before the allocation phase, and a precise grid will be given in the project section.

**Warning:** the project repository must show a balanced contribution between group members and intra-group grades variation could be made to reflect issues on the intra-group workload balance.

### Bonus

**1 supplementary point** on the final grade of the course can be obtained for contributions improving the course material (practicals, Readme, etc.).
See the [Bonus](Bonus/) section for more details on how to proceed.



## Books and other resources

The resources for the course are available on the present `github` repository. Additional elementary elements (**in French**) on Python are available in the course [HLMA310](http://josephsalmon.eu/HLMA310.html) and the associated lectures notes [IntroPython.pdf](http://josephsalmon.eu/enseignement/Montpellier/HLMA310/IntroPython.pdf).

### Additional resources

- (General) : [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)
- (Data Science) : J. Van DerPlas, *Python Data Science Handbook, With Application to Understanding Data*, 2016<https://jakevdp.github.io/PythonDataScienceHandbook/>
- (General) Skiena, *The algorithm design manual*, 1998
- (General) Courant et al. , *Informatique pour tous en classes préparatoires aux grandes écoles : Manuel d'algorithmique et programmation structurée avec Python*,
2013, (french)
- (General/data science) Guttag, *Introduction to Computation and Programming*,
2016

    Associated videos: <http://jakevdp.githubio/blog/2017/03/03/reproducible-data-analysis-in-jupyter/>

- (Code and style) Boswell et Foucher, *The Art of Readable Code*, 2011
- (Scientific computing tools for Python) <http://www.scipy-lectures.org/>
- (Visualization) <http://openclimatedata.net/>
