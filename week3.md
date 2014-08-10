## Type of Data Science Questions

* Descriptive
* Exploratory
* Inferential
* Predictive
* Causal
* Mechanistic


### Descriptive Analysis

Goal: Describe a set of data

* Can not be generalized


### Exploratory

Goal: Find relationships you didn't know about

* Should not generalized
* Correlation do not mean causation
 
 
### Inferential

Goal: Usa a relatively small sample of dat to say something about a bigger population

* Inference is commonly a goal of statistics models
* Inference involves estimating both the quantity you care about an your uncertainty about your estimate
* Inference depends heavily on both the population and the sampling scheme


### Predictive

Goal: To use the data on some objects to predict values for another object

* If *X* predicts *Y* it does not mean that *X* causes *Y*


### Causal

Goal: To find out what happens to one variable when you make another variable change

* Usually randomized studies are required to identify causation
* Causal relationships arae usually identfied as avverage effects, but may not apply to every individuals
* Causal models are usually the "gold standard" for data analysis

### Mechanistic

Goal: Understand the exact changes in variables that lead to changes in other variables for indiviual objects

* Physical and engineering science
* The random component of the data is measurement error

## What is Data?

**Data are values of qualitative or quantitative variables, belonging to a set of items.**

Set of items sometimes called the population.
Variables: A measuremnt or characteristics of an item.

### The data is the second most important thing

The most important thign in data science is the question
Often the data will limit or enable the question
But having data can't save you if you don't have a question

### Big Data

Big or small - you need the right data

Tukey: "The data may not contain the answer. The combination of some data and
an aching desire for an answer does not ensure thta a reasonable answer can be
extracted from a given body of data..."

## Experimental Design

Share data:
http://figshare.com/
https://github.com/jtleek/datasharing

### Formulate your question in advance

http://www.gs.washington.edu/academics/courses/akey/56008/lecture/lecture1.pdf

http://www.gs.washington.edu/academics/courses/akey/56008/lecture/lecture2.pdf

### Confounding

Correlation is not causation

* If you can (and want to) fix a variable
* If you don't fix a variable, stratify it
* If you can't fix a variable, randomize it

### Prediction

Prediction key quantities

* Test +  Disease + : True Positive
* Test +  Disease - : False Positive
* Test -  Disease + : False Negative
* Test -  Disease - : True Negative


* Sensitivity -> Pr(test positive / disease positive)
* Specifity   -> Pr(test negative / disease negative)
* Positive Predictive Value -> Pr(disease positive / test positive)
* Negative Predcitive Value -> Pr(disease negative / test negative)
* Accuracy Pr(correct outcome)

**Beware Data dredging**





