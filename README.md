# Phase 2 Code Challenge

# Phase 2 Code Challenge

This code challenge is designed to test your understanding of the Phase 2 material. It covers:

- SQL
- Bayesian Statistics
- Normal Distribution
- Statistical Tests

_Read the instructions carefully_. You will be asked both to write code and to answer short answer questions.

## Code Tests

We have provided some code tests for you to run to check that your work meets the item specifications. Passing these tests does not necessarily mean that you have gotten the item correct - there are additional hidden tests. However, if any of the tests do not pass, this tells you that your code is incorrect and needs changes to meet the specification. To determine what the issue is, read the comments in the code test cells, the error message you receive, and the item instructions.

## Short Answer Questions 

For the short answer questions...

* _Use your own words_. It is OK to refer to outside resources when crafting your response, but _do not copy text from another source_.

* _Communicate clearly_. We are not grading your writing skills, but you can only receive full credit if your teacher is able to fully understand your response. 

* _Be concise_. You should be able to answer most short answer questions in a sentence or two. Writing unnecessarily long answers increases the risk of you being unclear or saying something incorrect.

---
## Part 1: SQL [Suggested time: 20 minutes]
---
In this part, you will create and execute three SQL queries on the Chinook database. For this challenge **you will need to access the `Album` and `Artist` tables**.

### 1.1) Connect to the Database.

### 1.2) Write a query to return the last ten artists alphabetically.

### 1.3) Write a query to return all the albums in the database from Led Zeppelin.

### 1.4) Write a query to return both the artist with the most albums in the database and the number of albums.

---
## Part 2: Bayesian Statistics [Suggested time: 15 minutes]
---

A medical test is designed to diagnose a certain disease. The test has a false positive rate of 10%, meaning that 10% of people without the disease will get a positive test result. The test has a false negative rate of 2%, meaning that 2% of people with the disease will get a negative result. Only 1% of the population has this disease.

### 2.1) Create a numeric variable `p_pos_test` containing the probability of a person receiving a positive test result.

Assume that the person being tested is randomly selected from the broader population.

### 2.2) Create a numeric variable `p_disease_given_pos` containing the probability of a person actually having the disease if they receive a positive test result.

Assume that the person being tested is randomly selected from the broader population.

Hint: Use your answer to the previous question to help answer this one.

---
## Part 3: Normal Distribution [Suggested time: 20 minutes]
---
In this part, you will analyze check totals at a TexMex restaurant. We know that the population distribution of check totals for the TexMex restaurant is normally distributed with a mean of \\$20 and a standard deviation of \\$3. 

### 3.1) Create a numeric variable `z_score_26` containing the z-score for a \\$26 check. 

### 3.2) Create a numeric variable `p_under_26` containing the approximate proportion of all checks that are less than \\$26.

Hint: Use the answer from the previous question along with the empirical rule, a Python function, or this [z-table](https://www.math.arizona.edu/~rsims/ma464/standardnormaltable.pdf).

### 3.3) Create numeric variables `conf_low` and `conf_high` containing the lower and upper bounds (respectively) of a 95% confidence interval for the mean of one waiter's check amounts using the information below. 

One week, a waiter gets 100 checks with a mean of \\$19 and a standard deviation of \\$3.

### 3.4) Short Answer: Interpret the 95% confidence interval you just calculated in Question 1.3.

# Your answer here



---
## Part 4: Statistical Testing [Suggested time: 20 minutes]
---
The TexMex restaurant recently introduced queso to its menu.

We have a random sample containing 2000 check totals, all from different customers: 1000 check totals for orders without queso ("no queso") and 1000 check totals for orders with queso ("queso").

In the cell below, we load the sample data for you into the arrays `no_queso` and `queso` for the "no queso" and "queso" order check totals, respectively.

### 4.1) Short Answer: State null and alternative hypotheses to use for testing whether customers who order queso spend different amounts of money from customers who do not order queso.

# Your answer here



### 4.2) Short Answer: What would it mean to make a Type I error for this specific hypothesis test?

Your answer should be _specific to this context,_  not a general statement of what Type I error is.

# Your answer here



### 4.3) Create a numeric variable `p_value` containing the p-value associated with a statistical test of your hypotheses. 

You must identify and implement the correct statistical test for this scenario. You can assume the two samples have equal variances.

Hint: Use `scipy.stats` to calculate the answer - it has already been imported as `stats`. Relevant documentation can be found [here](https://docs.scipy.org/doc/scipy/reference/stats.html#statistical-tests).

### 4.4) Short Answer: Can you reject the null hypothesis using a significance level of $\alpha$ = 0.05? Explain why or why not.

# Your answer here
