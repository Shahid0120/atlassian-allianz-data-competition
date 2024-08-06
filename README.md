# Atlassian Allianz Data Competition

<img src="/pictures/pic5.JPG" alt="Home Page Pictures">

I've had the privilege to compete in the UNSW Atlassian Allianz Data Competition at their respective headquarters! This 3-day event required my team to classify fraudulent customers from insurance data collected by Allianz customers.

Luckily, we made it to the final round, comprising 4 teams, and ended up coming 3rd out of 75 teams! 

Check our my blog post about the [Atlassian x Alliance Datathons! Lesson I've Learnt](https://shahid0120.github.io/datathons/Atlassian-Allianz-data-soc/) 

## The Team
Had the pleasure to work along side my friends [Keith Tang](https://www.linkedin.com/in/tzekwongtang/), [Yil Seung Aaron Jeong](https://www.linkedin.com/in/yil-seung-aaron-jeong-260123198/) and 
[Sammi Liu](https://www.linkedin.com/in/jiaying-sammi-liu/)! 

## Task Objectives and Overview

Insurance company ABC has been experiencing a surge in fraudulent claims, resulting in significant
financial losses. To address this issue, they have approached you, a team of Data Scientists, to help
identify key areas where fraudulent claims are most likely to occur and to develop a solution to
mitigate these financial losses.

Additionally, it is crucial to consider the ethical implications of your data analysis methods. ABC wants
you to evaluate these ethical aspects and propose strategies to mitigate potential biases in your
solution.

You will be presenting your findings and proposed solution to ABC’s stakeholder, a semi-technical
marketing manager.

## Dataset Overview 

You will be working with a dataset comprising ~1700 rows and 38 columns, containing detailed information
about insurance claims. The dataset includes various features such as customer demographics, policy
details, incident specifics, claim amounts, and fraud reports.

## Marking Rubric

- *Data Analysis*: Examines the ability to explore and communicate key patterns, trends, and anomalies in the dataset. High-quality data visualization and clear interpretation of the data are crucial.
- *Model Development / Solution development*: Assesses the technical proficiency and effectiveness of the proposed solution. A solution does not have to be a model: it can be a set of ideas on how to solve the given problem.
- *Ethical Considerations* - Evaluates awareness and handling of ethical issues related to analysis and solutions. The goal is to create solutions that are not only effective but also ethically sound.
- *Adaptation to the Target Audience & Background*
- *Innovation and Creativity*
- *Clarity & Organisation of Presentation / Engaging & Persuasive Delivery*
- *Effective Use of Visuals & Supportive Materials*

## Workflow

<img src="/workflow/datasoc-workflow.png" alt="Workflow diagram">

## Solution Overview

1. **Data Profiling and Data Cleaning**: Identified data types, data ranges, and handled missing values and inconsistencies. Transformed categorical variables into dummy variables.

2. **Exploratory Data Analysis (EDA)**: Conducted a thorough EDA to understand the data distribution, identify patterns, detect any missing data through K-nearest neighbor, and address imbalanced labels using SMOTE-N.

3. **Feature Engineering**: Simplified features with similar levels (e.g., combining education levels such as high school, college, master, PhD, university, and doctor into degree or non-degree). Additionally, removed highly collinear data types.

4. **Model Selection and Training**: Experimented with various machine learning models such as LightGBM, Random Forest, and CatBoost. Used cross-validation to tune hyperparameters and select the best model, creating two sets of models: one with ethical considerations and one without.

5. **Evaluation and Validation**: Validated the model using a separate validation set to ensure it generalized well to unseen data. Evaluated performance using different metrics, including R².

6. **Presentation**: Prepared and delivered a presentation to the data science teams at Allianz and Atlassian, showcasing our methodology, results, and the impact of our solution. Addressed ethical concerns, ranked feature importance, and strategized to reduce business funds by dividing solutions based on fraud amounts into two categories: above 20k and below 20k. Using Bayes Theorem we found the likilooh of fraudulent cases under 20k is small, thus the team recommended focusing on investigating insurance claims over 20k to maximize fraud detection, although this may be challenging in reality, this would be implemented via a pipeline where the model is optimized with new data, reducing the potential fraudulent market.


## Few more Pictures!

<img src="/pictures/pic1.JPG" alt="Home Page Pictures">

<img src="/pictures/pic6.jpg" alt="Home Page Pictures">

<img src="/pictures/pic3.jpg" alt="Home Page Pictures">
