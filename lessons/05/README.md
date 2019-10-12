# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Experiments and Hypothesis Testing

> Unit 2: Required

---

## Materials

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Experiments and Hypothesis Testing Lesson | [Here](./experiments-hypothesis-tests.ipynb)|
| Practice | Individual Practice Activity | [Here](./practice/eda-with-music-data-lab.ipynb)|
|  | Optional Practice Activity | [Here](./practice/AB-testing.ipynb)|
|  | Group Practice Activity | [Here](./practice/telecomm-eda-group-lab.ipynb)|
| Solutions | Sample Solutions for Lesson Sections | [Here](./solutions/experiments-hypothesis-tests-solutions.ipynb)|
|  | Optional Practice Activity Solutions| [Here](./practice/solutions/AB-testing-solutions.ipynb)|
|  | Individual Practice Activity Solutions | [Here](./practice/solutions/eda-with-music-data-lab-solutions.ipynb)|
> NOTE 1: Solutions will not be made available until each class is complete.
>
> NOTE 2: In this lesson, we'll use an online CSV file about advertising data, taken from the book "An Introduction to Statistical Learning". This dataset is easy to understand. It allows students to easily compare sales data across three advertising mediums.


---

## Learning Objectives

By the end of this lesson, students will be able to:
- Explain the difference between causation and correlation
- Determine causality and sampling bias using Directed Acyclic Graphs
- Identify what missing data is and how to handle it
- Test a hypothesis using a sample case study

---

## Student Requirements

Before this lesson(s), students should already be able to:
- Perform basic data analysis in Pandas
- Have a basic understanding of bias, variance, and correlation
- Create basic visualizations in Seaborn
- Have some exposure to major considerations within experimental design

----

## Lesson Outline

### Lesson Guide
- Data source
	- Exploring the advertising data
- Descriptive statistics fundamentals
    - Math review
        - Independent exercise 1
        - Measures of central tendency
        - Independent exercise 2
        - Anscombe's quartet
        - Box Plots: Show quartiles (and outliers) for one or more numerical variables
    - Math review continued
    - Measures of dispersion: Standard deviation and variance
        - Independent exercise 3
    - Understanding distributions
        - The normal distribution
        - Sampling bias
    - Measuring relationships
        - Covariance
        - Correlation
        - The variance-covariance matrix
        - Independent exercise 4
        
#### Optional:
- Missing data
	- Types of missing data
	- De minimis
	- Class imbalance
    - Relation to machine learning
- Introduction to hypothesis testing
	- Validate your findings
	- Confidence intervals
	- Error types
- Additional practice materials

---

## Additional Resources

### Safari Resources

+ [Book: "Chapter 2: Data and Sampling Distributions" (from "Practical Statistics for Data Scientists")](https://www.safaribooksonline.com/library/view/practical-statistics-for/9781491952955/ch02.html#Chapter_2)

+ [Book: Chapter "Statistical terminology for model building and validation" (from "Statistics for Machine Learning")](https://www.safaribooksonline.com/library/view/statistics-for-machine/9781788295758/c3c0917b-6f5d-4c16-9d6e-eb80ccb0ff03.xhtml)]

+ [Book: Chapter "Machine learning terminology for model building and validation" (from "Statistics for Machine Learning")](https://www.safaribooksonline.com/library/view/statistics-for-machine/9781788295758/1528f340-95fd-4456-b018-e804320e54b1.xhtml)]


For more information on this topic, check out the following resources:
- [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
- [The more advanced book: Elements of Statistical Learning](http://web.stanford.edu/~hastie/ElemStatLearn/)
- [Spurious Correlations](http://www.tylervigen.com/spurious-correlations)
