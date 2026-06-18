# MLCOURSE.AI REPORT

## Stage

Stage 1 - Intro / Lecture 0.

## Goal

Understand how mlcourse.ai is structured and define a personal workflow for studying the course.

Main goals:

- understand course structure;
- understand how to navigate course materials;
- define note-taking rules;
- define progress reporting rules;
- prepare for Topic 1: pandas and basic EDA.

## What was studied

I analyzed the introductory material for mlcourse.ai.

The intro explains that mlcourse.ai is an open Machine Learning course created by Yury Kashnitsky.

The course is available in self-paced mode. It is organized as a Jupyter Book and combines:

- articles;
- code;
- formulas;
- plots;
- video lectures;
- demo assignments;
- bonus assignments;
- Kaggle competitions.

The course is designed as a balance between theory and practice. It is partly math-heavy, but also strongly focused on hands-on assignments and practical ML workflows.

## Course structure

The course consists of approximately 10 main topics:

1. pandas and basic data analysis;
2. visual data analysis;
3. decision trees, KNN, supervised learning and cross-validation;
4. linear models and logistic regression;
5. bagging and random forest;
6. feature engineering and different data types;
7. unsupervised learning: PCA and clustering;
8. stochastic gradient descent and large-scale learning;
9. time series analysis;
10. gradient boosting.

Each topic usually contains:

- article;
- optional video lecture;
- demo assignment;
- solution for self-check;
- bonus assignment or Kaggle-related practice.

## Key conclusions

1. The course should not be studied passively.
2. Watching a lecture is not enough to mark a topic as completed.
3. The correct workflow is: read article, run code, solve assignment, compare with solution, write conclusions.
4. Assignments and Kaggle competitions are central parts of the course.
5. The course focuses on classic Machine Learning.
6. Cross-validation, feature engineering, linear models and gradient boosting are central course topics.
7. Every topic should produce a practical artifact.
8. All progress should be tracked through notes, reports, learning log, progress file and Git commits.
9. Course materials should be connected with practical ML project workflow: EDA, baseline, preprocessing, feature engineering, validation, leakage control, metrics, model comparison, final evaluation and reproducibility.

## Personal study rules

During the course I will follow these rules:

- use develop branch for work;
- update notes after every topic;
- update learning_log.md after every meaningful learning stage;
- update progress.txt after every completed stage;
- prepare a report in reports/ after every stage;
- commit every meaningful completed stage;
- always build a baseline before complex models;
- always define a validation strategy before tuning;
- always check for leakage;
- always write conclusions after important plots;
- always track experiments;
- always connect course ideas with my ML projects.

## Note-taking format

For every topic I will track:

- goal of the topic;
- main concepts;
- important definitions;
- code patterns;
- practical ML meaning;
- typical mistakes;
- links with my projects;
- questions to review;
- final summary.

For every important ML concept I will track:

- what it is;
- why it matters;
- simple intuition;
- formula or technical detail if needed;
- Python or sklearn connection;
- typical mistake;
- how I can use it in my projects.

## Progress reporting format

After every major course stage I will prepare a report with:

- stage;
- what was studied;
- key conclusions;
- practical work completed;
- files updated;
- problems or blockers;
- Git status;
- latest commit;
- next step.

## Files updated

Updated files:

- notes/00_intro.md
- learning_log.md
- progress.txt
- reports/00_intro_report.md

## Git status

Expected after commit:

- branch: develop;
- remote branch: origin/develop updated;
- working tree clean.

## Latest commit

Expected commit message:

Complete mlcourse.ai intro notes

Actual commit hash should be checked with:

git log --oneline -1

## Problems / blockers

No critical blockers.

Potential risks for the next stages:

- passive watching instead of active practice;
- skipping assignments;
- weak pandas fluency;
- getting stuck on math instead of combining intuition and practice;
- not tracking experiments;
- not connecting course material with personal ML projects.

## Next step

Proceed to Topic 1 - pandas and basic EDA.

Focus for Topic 1:

- pandas DataFrame and Series;
- reading datasets;
- inspecting data;
- filtering and grouping;
- basic aggregations;
- missing values;
- basic EDA;
- writing conclusions from data.
