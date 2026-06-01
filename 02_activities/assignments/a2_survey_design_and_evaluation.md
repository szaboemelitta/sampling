# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: 3

Describe the purpose of your survey:
The purpose of the survey is to measure the relation between music taste and age. It examines Canadian citizens' taste of music and its changes as people age through a stratified quota sampling, with different age groups (e.g., 18-30, 31-40, 41-50, 51-60, 61+) constituting non-overlapping strata. Since a longitudinal study tracing the changes in individuals' music taste would require extensive resources and would take a lot of time,  retrospective questions asking about the respondents' music preferences at different stages of their lives are used instead in addition to comparing the data across age groups. The survey will collect information online.

Describe your target population, sampling frame, sampling units, and observational units:
Target population: Canadian citizens aged 18 and older
Sampling frame: Canadian adults who could be reached through online survey distribution (e.g, social media recruitment)
Sampling units: Individual respondents
Observational units: Individual respondents


Your 5-10 question survey:
```
1. What is your current age?
2. What genres do you listen to most often?
3. Do you listen to popular music?
4. What genres did you listen to when you were 15-17 years old? 
5. What genres did you listen to when you were 18-30 years old? (If applicable)
6. What genres did you listen to when you were 31-40 years old? (If applicable)
7. What genres did you listen to when you were 41-50 years old? (If applicable)
8. What genres did you listen to when you were 51-60 years old? (If applicable)
9. How would you compare today's popular music to the popular music of your earlier years?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

1. Sample type: stratified two-phase, multi-stage cluster probability sample
2. Sample size: 80,000 individuals (60,000 regular sample, 20,000 oversample).
3. Target population: Persons aged 15 years and over living in private households in Canada, excluding residents of the Yukon, Northwest Territories and Nunavut and full time residents of institutions
4. Sampling frame: Private households
5. Survey mode(s): Observational studies (using earlier census data) + questionnaire through telephone or electronically
6. Timeline: 2004-2023, but the data collection period is indicated as 2023-09-15 to 2024-03-30
7. Response rate: 40.9%, (42.2% for the regular sample and 37.1% for the oversample)
8. Weights: Estimates were weighted to represent all persons in the target population and to account for non-response cases.
9. Data processing: Conducted by using the Social Survey Processing Environment (SSPE), a set of generalized processing steps and utilities. Edits were performed automatically and manually at various stages of processing at macro and micro levels. Data verification was carried out using consistency and flow edits. A series of checks were done to ensure the consistency of the survey data, for example, checking the respondent's reported age against the date of birth coming from the sample file. Flow edits were used to ensure respondents followed the correct path and fix off-path situations.
10. Cleaning, imputation, etc: Edits/cleaning were automated as well as double-checked by the head office manually. Missing records were also completed or imputed. Imputations were made through donor imputation (filling the missing information by finding the most similar respondent's corresponding entry), and were made separately for different groups of variables: personal/family income, donation-related variables, formal volunteering variables, informal volunteering variables.
11. Sources of error: Sampling errors (due to sampling persons); non-sampling errors:  imperfect coverage and non-response, processing errors.
12. Limitations, known biases, etc.: Efforts were made to reduce other non-sampling biases by using a well-tested questionnaire, an apt methodology, interviews, and quality control. 
13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=4430#a3

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [x] Create a branch called `assignment-2`.
- [x] Ensure that the repository is public.
- [x] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
