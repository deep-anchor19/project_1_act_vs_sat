# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Overview

The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

In this study, we seek to use data from the ACT and SAT participation rates across the states, as well as their respective composite and total scores, to understand the influence they have on the percentage of high school graduates in each state that are able to gain direct admission into colleges.



### Problem Statement

While colleges do not discriminate between applicants who have taken the SATs or ACTs, the state mandate means that all state-administered SATs/ACTs are mandatory for eleventh-grade students. They are paid-for and administered by the respective State Boards of Education, and the results are used to determine statewide academic achievement. While this is good news especially for children from low-income backgrounds, the downside is that the state makes the choice of whether to administer the SATs or ACTs. If a state mandates all students take the SATs, students who would additionally like to take the ACTs have do so on their own expenses. The same applies for students in ACT-mandated states who wish to sit for the SATs.

We believe that the choice of deciding between the SATs and ACTs should be given to students instead of the state as both tests are formatted and scored differently. If a student is more comfortable taking the SAT over the ACT, or vice versa, the state should pay for one attempt of the the chosen test.

Since both tests are influencial in a student's college application, it is critical that students are allowed to take the test that they think is more suited to their learning style and way of thinking, instead of one that is mandated by the state.

We seek to establish that a state's preference for mandating one test over the other has no bearing on the likelihood of high school graduates successfully gaining admission into college. We aim to do this by studying the relationships between (1) Test participation (either SAT or ACT) and (2) percentage of high school graduates that gained admission into college. If there is no correlation between either test and college admission, this means that mandating an entire state to take one kind of test is not made in the interest of students.



### Datasets

#### Provided Data

There are 10 datasets included in the [`data`](./data/) folder for this project. You are required to pick **at least two** of these to complete your analysis. Feel free to use more than two if you would like, or add other relevant datasets you find online.

* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`act_2019_ca.csv`](./data/act_2019_ca.csv): 2019 ACT Scores in California by School
* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))
* [`sat_2019_by_intended_college_major.csv`](./data/sat_2019_by_intended_college_major.csv): 2019 SAT Scores by Intended College Major ([source](https://reports.collegeboard.org/pdf/2019-total-group-sat-suite-assessments-annual-report.pdf))
* [`sat_2019_ca.csv`](./data/sat_2019_ca.csv): 2019 SAT Scores in California by School
* [`sat_act_by_college.csv`](./data/sat_act_by_college.csv): Ranges of Accepted ACT & SAT Student Scores by Colleges ([source](https://www.compassprep.com/college-profiles/))

**Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Additional Data

[`college_going_rates_of_high_school_graduates_2018.csv`](./my_data/college_going_rates_of_high_school_graduates_2018.csv):
College-Going Rates of High School Graduates - Directly from High School
([source](http://www.higheredinfo.org/dbrowser/index.php?submeasure=63&year=2018&level=nation&mode=data&state=))

[`https://blog.prepscholar.com/act-vs-sat`] ACT vs SAT: 11 Key Differences to Help You Pick the Right Test ([source](https://blog.prepscholar.com/act-vs-sat))
