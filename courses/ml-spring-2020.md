# CS 360/530: Foundations of Machine Learning

**Spring 2020**

This course gives an introduction to foundations of machine learning and statistical learning. Please see [Schedule of Classes](#schedule-of-classes) for topics covered in this course.

> - Keynote by C. Bishop on [Model-based machine learning](https://www.microsoft.com/en-us/research/video/keynote-talk-model-based-machine-learning/). A must watch!
> - Midterm is on Thursday, Feb 27, 2020 at 10am-12pm  
> - Lectures will be conducted online from March 16, 2020 to March 31, 2020. Please check the [Classroom](https://classroom.google.com/) for more details.  

**Outline**
- [CS 360/530: Foundations of Machine Learning](#cs-360530-foundations-of-machine-learning)
	- [Instructor](#instructor)
	- [Teaching Assistants](#teaching-assistants)
	- [Meetings](#meetings)
	- [Recommended Books](#recommended-books)
	- [Course Eligibility and Requirements](#course-eligibility-and-requirements)
	- [Grading Policy (tentative)](#grading-policy-tentative)
	- [Academic Honesty](#academic-honesty)
	- [Schedule of Classes](#schedule-of-classes)
	- [Schedule of Homeworks, Quizzes, Exams](#schedule-of-homeworks-quizzes-exams)
	- [Other relevant courses and resources](#other-relevant-courses-and-resources)

## Instructor

[Clint P. George](https://www.iitgoa.ac.in/~clint) — clint [at] iitgoa [dot] ac [dot] in — Office: F9, New Academic Block A

## Teaching Assistants

- Abhilasha Gupta
- Shruti Shet
- Shivam Kumar
- Nitish Shah

## Meetings

- Class meetings (**LT3**, Admin Block):
  - 10:30am-11:25am, Mon
  - 10:30am-11:25am, Tue
  - 10:30am-11:25am, Wed

- Instructor office hours (**F-9**, New Academic Block):
  - 4-4:30pm, Mon
  - 2-3pm, Tue

- TA office hours (**Computing Center**, Admin Block, 1st floor)
  - **Abhilasha Gupta**, Thu, 3-4pm
  - **Shivam Kumar**, TBA  
  - **Nitish Shah**, TBA  
  
- Tutorial/Lab hours (**Computing Center**, Admin Block, 1st floor): 4-4:45pm, Mon  

## Recommended Books

1. Elements of Statistical Learning by *Hastie, Tibshirani, and Friedman (2017)*

2. [Machine Learning](http://www.cs.cmu.edu/afs/cs.cmu.edu/user/mitchell/ftp/mlbook.html) by *Mitchell (2009)*

3. [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) (Information Science and Statistics) by *Bishop (2010)*

4. Foundations of Data Science by *Blum, Hopcroft, and Kannan (2018)*

5. R for Data Science: Import, Tidy, Transform, Visualize, and Model Data by *Wickham and Grolemund (2016)*

## Course Eligibility and Requirements

This is a *core course* designed for undergraduate (CS 360; six semester Computer Science and Engineering) and graduate (CS 530) students. Familiarity with the following is recommended.

- Basic computer programming—we use R/Python.

- Probability theory (CS 215, MA 605)

- Multivariable calculus and linear algebra (MA 105, MA 106, EE 611)

## Grading Policy (tentative)

- *CS360*: Quiz 1 (15%) — Midterm (20%) — Quiz 2 (15%) — Homeworks and Classroom participation (15%) — Final (35%)

- *CS530*: Quiz 1 (10%) — Midterm (20%) — Quiz 2 (10%) — Projects/Term paper (15%) — Homeworks and Classroom participation (15%) — Final (30%)

## Academic Honesty

We expect that every student follows the highest standards of integrity and academic honesty. Copying/sharing code in exams, homeworks, lab sessions are not permitted. See the IIT Goa policy for academic malpractices.

## Schedule of Classes

Note: This is a tentative course schedule. It will be updated often. Also, *log on to [Classroom](https://classroom.google.com/)* to see lecture slides, additional course materials, and announcements.

|  S/N  |  Date  | Topic                                                                                                                                | Resources                                                                                                                                                                                                                                                                |
| :---: | :----: | :----------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1   | Jan 07 | Course Introduction                                                                                                                  | [lecture 01](ml-spring-2020/FML-lecture-01.pdf)                                                                                                                                                                                                                          |
|   2   | Jan 08 | Data science basics: data visualization, data transformations                                                                        | [R vs. Python](https://www.r-bloggers.com/python-vs-r-for-data-science-whats-the-difference/) for data science; [data visualization](https://r4ds.had.co.nz/data-visualisation.html); [data transformations](https://r4ds.had.co.nz/transform.html)                      |
|   3   | Jan 13 | Understanding the data: expected value, variance, covariance, visualizing distributions                                              | [St. Petersbug paradox](https://plato.stanford.edu/entries/paradox-stpetersburg); [exploratory data analysis](https://r4ds.had.co.nz/exploratory-data-analysis.html)                                                                                                     |
|   4   | Jan 14 | [Hypothesis testing](https://en.wikipedia.org/wiki/Statistical_hypothesis_testing)                                                   | [video 1](https://www.youtube.com/watch?v=z0Ry_3_qhDw); [one-vs-two tailed tests](https://revisionmaths.com/advanced-level-maths-revision/statistics/one-and-two-tailed-tests); [$t$-test example](https://statistics.berkeley.edu/computing/r-t-tests)                  |
|   5   | Jan 15 | Hypothesis testing: crtical region, $p$-value, examples                                                                              | [one-sample test](http://www.sthda.com/english/wiki/one-sample-t-test-in-r); [normality test](http://www.sthda.com/english/wiki/normality-test-in-r); [boxplots](http://www.sthda.com/english/wiki/ggplot2-box-plot-quick-start-guide-r-software-and-data-visualization) |
|   6   | Jan 20 | Supervised learning, linear models, ordinary least-squares                                                                           | [cs229 notes 1](http://cs229.stanford.edu/notes/cs229-notes1.pdf)                                                                                                                                                                                                        |
|   7   | Jan 21 | The least mean square (LMS) algorithm: batch and stochastic gradient approaches; The normal equations for the least squares problem. |
|   8   | Jan 22 | Polynomial curve fitting and similarities with least squares                                                                         | [comic](https://xkcd.com/2048); C. Bishop's [Slides](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/05/prml-slides-1.pdf) 3-13                                                                                                                         |
|   9   | Jan 27 | Linear regression: probabilistic view, Maximum Likelihood Estimate                                                                   |                                                                                                                                                                                                                                                                          |
|  10   | Jan 29 | Locally weighted linear regression, introduction to logistic regression                                                              | [cs229 notes 1; Section 4](http://cs229.stanford.edu/notes/cs229-notes1.pdf)                                                                                                                                                                                             |
|  11   | Feb 03 | Tutorial on Linear regression and homework 3                                                                                         |                                                                                                                                                                                                                                                                          |
|  12   | Feb 04 | Logistic regression                                                                                                                  | [logistic regression tutorial](https://www.machinelearningplus.com/machine-learning/logistic-regression-tutorial-examples-r/); [cs229 notes 1; Section 5](http://cs229.stanford.edu/notes/cs229-notes1.pdf)                                                              |
|  13   | Feb 04 | $k$-Nearest Neighbours: discussion and workshop by *A. Gupta*, *S. Kumar*                                                            |                                                                                                                                                                                                                                                                          |
|  14   | Feb 05 | Discussion on softmax regression, the perceptron algorithm                                                                           |                                                                                                                                                                                                                                                                          |
|  15   | Feb 10 | Discussion on Gradient Descent, the Newton's method                                                                                  | Lectures by Gibert Strang on [Gradient Descent](https://www.youtube.com/watch?v=AeRwohPuUHQ); [Newton's method](https://www.youtube.com/watch?v=U0xlKuFqCuI)                                                                                                             |
|  16   | Feb 11 | Introduction to Neural Networks                                                                                                      | Example: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html); reading: [linear classifier](http://cs231n.github.io/linear-classify)                                                                                                                                  |
|  17   | Feb 12 | Neural networks, the back-propagation algorithm                                                                                      | [cs231n](http://cs231n.github.io/optimization-2/) notes                                                                                                                                                                                                                  |
|  18   | Feb 17 | The back-propagation algorithm: aspects of implementation                                                                            | Notes by [R. Grosse](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/readings/L06%20Backpropagation.pdf), U. Toronto                                                                                                                                              |
|  19   | Feb 18 | Discussion on the backprop algorithm | |
|  20   | Feb 19 | Introduction to the Convolutional Neural Networks | cs231n [notes](http://cs231n.github.io/convolutional-networks/) |
|  21   | Feb 24 | Overview of deep autoencoders |  |
|  22   | Mar 16 | Generative models |  |
|  23   | Mar 17 | Gaussian discriminant analysis | Andrew Ng's [notes](http://cs229.stanford.edu/notes/cs229-notes2.pdf) (Section 1); [relevant lecture](https://www.youtube.com/watch?v=qRJ3GKMOFrE) |
|  24   | Mar 23 | Gaussian discriminant analysis vs logistic regression |  |
|  25   | Mar 24 | Bias/variance tradeoff |  |
|  26   | Mar 25 | Model selection | Andrew Ng's [lecture](https://www.youtube.com/watch?v=0kWZoyNRxTY) (from 35th minute); [more](https://www.youtube.com/watch?v=MyBSkmUeIEs) |

## Schedule of Homeworks, Quizzes, Exams  

*Log on to [Classroom](https://classroom.google.com/)* to see more details.

|  S/N  |  Date  | Title                                                    | Remarks                |
| :---: | :----: | :------------------------------------------------------- | :--------------------- |
|   1   | Jan 09 | **Homework 01**: Getting started with R and data science | Due date: Jan 14, 9am  |
|   2   | Jan 14 | **Homework 02**: CLT and Standard Error                  | Due date: Jan 20, 10am |
|   3   | Jan 21 | **Homework 03**: Linear regression                       | Due date: Jan 27, 10am |
|   4   | Jan 28 | **Quiz 01**                                              | LT3, Admin Block       |
|   5   | Feb 08 | **Homework 04**: Logistic regression                     | Due date: Feb 18, 10am |

## Other relevant courses and resources

1. [CS229: Machine Learning](http://cs229.stanford.edu)
2. [Machine learning](http://www.cs.cmu.edu/~tom/mlbook-chapter-slides.html) by Tom Mitchel
3. [COS 324 - Introduction to Machine Learning](https://www.cs.princeton.edu/courses/archive/fall17/cos324)
