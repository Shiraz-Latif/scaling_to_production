
# Production

## Contents:
1. [Description](https://github.com/rachaellam/dsi-workshop#description)
2. [Learning Outcomes](https://github.com/rachaellam/dsi-workshop#learning-outcomes)
3. [Logistics](https://github.com/rachaellam/dsi-workshop#logistics)
4. [Marking Scheme](https://github.com/rachaellam/dsi-workshop#marking-scheme)
5. [Policies](https://github.com/rachaellam/dsi-workshop#policies)
6. [Folder Structure](https://github.com/rachaellam/dsi-workshop#folder-structure)
7. [Acknowledgements and Contributions](https://github.com/rachaellam/dsi-workshop#acknowledgements-and-contributions)

## Description

**TODO**
The course was created by the University of Toronto's Data Science Institute. The beginning of the course will introduce the basic language of Unix shell including how to navigate and manipulate files and directories. Learners will then learn certain commands, how to create scripts and write basic functions using pipes, filters and loops. 

The next portion of the course will be dedicated to getting started with version control and GitHub, and how it connects to the ethical discussions of reproducibility. Learners will learn how to set up Git and initialize and utilize repositories, including recording, viewing and undoing changes. They will also learn how to create branches and collaborate with others with shared branches. This course will put it all together and introduce some more advanced commands such as de-bugging and history editing.

Finally, learners will determine how to problem-solve by identifying where the issue is and how to search with Google and Stack Overflow. This will then lead to the topic of reproducibility and how to contribute by commenting code and writing documentation.

This course is designed for those who have a degree in something other than Computer Science/Statistics who are looking to enhance their data science skills for their career.

## Learning Outcomes

**TODO**

By the end of this course, a student will be able to:

+ Describe the main components of a machine learning system.
+ Explain the methods to train and test models in production, including deployment of production systems.
+ Delinate solutions and implementations to data and machine learning engineering problems.
+ Contrast and evaluate different approaches to implementing machine learning systems.



## Logistics

### Course Contacts

+ Instructor: Jesús Calderón (he/him)

  * Email etiquette
  * [LinkedIn](https://www.linkedin.com/in/jcalderon/) 

+ TA: TBD

### Delivery instructions

The workshop will be held over two weeks, four days a week. Two of the three days will be 2-hours long and the last day will be 3-hours. Being mindful of online fatigue, there will be one break during each class where students are encouraged to stretch, grab a drink and snacks, or ask any additional questions.

### Technology Requirements

**TODO**

1. PC, connection, etc. Potentially, could VM.
2. Camera is optional although highly encouraged. We understand that not everyone may have the space at home to have the camera on.
3. Ability to install software (administrator priviliges)

# Course Schedule

## Session 1:	Introduction

### 1.1 Overview of ML Systems 
	
+ When to Use ML
+ ML in Production
+ ML vs traditional software
	
### 1.2 Introduction to ML System Design 
	
 + Business and ML Objectives
 + Requirements of Data-Driven Products: Reliability, Scalability, Maintainability, Adaptability
 + Iterative Process
 + Framing ML Problems 
	
### Assignment: Setting Up a Code Repository

 + Sign up for a GitHub Account
 + Install git.
 + Setup SSH Key.
 + Setup repo and do an initial commit.

	
## Session 2:	Data Engineering

### 2.3. Data Engineering Fundamentals 
	
+ Data Sources
+ Data Formats  
+ Data Models 
+ Data Storage and Processing
	
### Assignment

+ Download large data set
+ Write code to load it in dask
+ Write code to write parquet files in dask
+ Naming convention: easy to maintain


## Session 3:	Training

### 3.1. Training Data 
	
+ Sampling
+ Labeling
+ Class Imbalance
+ Data Augmentation
	
### Assignment

+ Implement different types of sampling
+ Some recoding exercise using sci-kit learn
+ Conformal prediction?

### Session 4:	Feature Engineering

#### 4.1. Feature Engineering 

+ Common Operations
+ Data Leakage
+ Feature Importance 
+ Feature Generalization
	

#### Assignment

+ Scikit learn pipelines
+ Time series cross validation
+ 1 scikit and 1 lime or shap


## Session 5:	Model Development and Evaluation

### 5.1. Model Development and Offline Evaluation (4 Units)

+ Model Development and Training 
+ Ensembles 
+ Experiment Tracking and Versioning 
+ Distributed Training
+ AutoML 
+ Model Offline Evaluation 

### Assignment

+ Implement DB with Docker
+ Experiment tracking


### Session 6:	Deployment

#### 6.1. Model Deployment and Prediction Service 

+ ML Deployment Myths
+ Batch Prediction vs Online Prediction
+ Model Compression
+ ML in the Cloud
	

#### Assignment

+ Connect to Power BI
+ What is a pipeline?



## Session 7:	Data Distribution Shifts

### 7.1. Data Distribution Shifts and Monitoring 

+ ML System Failures
+ Data Distribution Shifts
+ Monitoring and Observability
	
### 7.2. Continual Learning and Test in Production 

 + Continual Learning
 + Stateless vs Stateful Training
	
### Session 8:	Infrastructure and Organization

#### Topic 8.1. Infrastructure and Tooling for ML Ops
	
+ Infra 1
+ Infra 2


#### Topic 8.2. The Human Side of ML

+ Human 1
+ Human 2


## Policies

+ Assignment.
+ Reading.
+ Evaluation.
+ Attendance. 

+ The course has a live-coding component. 
+ Students are expected to follow along with the coding, creating files and folders to navigate and manipulate. Students should be active participants while coding and are encouraged to ask questions throughout. Although slides will be available for students to reference, they should be referenced before or after class, as during class will be dedicated to coding with the instructor.


+ [U of T Holiday Schedule](https://people.utoronto.ca/news/holiday-schedule-2022-23-and-2023-24/)
+ [Policy]
+ [Policy]


**TODO**: **How to submit assignments, late policy, academic integrity.**



## Folder Structure
Below are the folders contained in this repo with a description of what they contain and information on how to use them.

**TODO**

# Acknowledgements and Contributions

## Achnowledgements

* Who helped make theses slides
* We wish to acknowledge this land on which the University of Toronto operates. For thousands of years it has been the traditional land of the Huron-Wendat, the Seneca, and most recently, the Mississaugas of the Credit River. Today, this meeting place is still the home to many Indigenous people from across Turtle Island and we are grateful to have the opportunity to work on this land.

### Contributions 

* We welcomes issues, enhancement requests, and other contributions. To submit an issue, use [GitHub
issues](https://github.com/UofT-DSI/production/issues).