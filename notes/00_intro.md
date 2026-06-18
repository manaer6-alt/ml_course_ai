# 00 Intro - mlcourse.ai structure and study rules

## 1. What mlcourse.ai is

mlcourse.ai is an open Machine Learning course by OpenDataScience, led by Yury Kashnitsky.

The course is focused on classic Machine Learning. It combines theory, math, practical coding, notebooks, assignments and Kaggle-style competitions.

The main idea of the course is not passive watching. The correct way to study is to read materials, run code, solve assignments, review mistakes and write conclusions.

## 2. How the course is organized

The course is organized as a Jupyter Book.

This format is useful because it can combine:

- text explanations;
- Python code;
- mathematical formulas;
- plots;
- executed outputs;
- links to notebooks and assignments.

For each topic the usual workflow is:

1. Read the article.
2. Watch the video lecture if needed.
3. Run the notebook.
4. Solve the demo assignment.
5. Compare with the official solution.
6. Do bonus assignment or Kaggle practice if needed.
7. Write notes and update progress.

## 3. Main course topics

The course covers approximately these topics:

1. pandas and basic data analysis;
2. visual data analysis;
3. decision trees, KNN, supervised learning and cross-validation;
4. linear models and logistic regression;
5. bagging and random forest;
6. feature engineering;
7. unsupervised learning: PCA and clustering;
8. stochastic gradient descent and large-scale learning;
9. time series analysis;
10. gradient boosting.

## 4. How I should approach theory

The course contains math, but I should not get blocked by formulas.

For each theoretical concept I should understand:

- what it is;
- why it is needed;
- simple intuition;
- main formula if important;
- how it appears in Python or sklearn;
- typical mistake;
- how it connects with my projects.

Important concepts to track:

- target variable;
- features;
- supervised learning;
- train/test split;
- validation;
- cross-validation;
- leakage;
- baseline;
- metric;
- loss function;
- overfitting;
- underfitting;
- regularization;
- feature engineering;
- model comparison;
- hyperparameter tuning;
- final evaluation;
- reproducibility.

## 5. How I should approach assignments

Assignments are mandatory for real understanding.

My workflow:

1. Read the task carefully.
2. Identify what concept is trained.
3. Load the data.
4. Check shape, columns, data types and missing values.
5. Solve step by step.
6. Do not open the solution too early.
7. Compare my answer with the official solution.
8. Write down mistakes.
9. Save useful code patterns.
10. Update notes and progress.

An assignment is completed only if I can explain:

- what the task was;
- what data was used;
- what operations were performed;
- why these operations were needed;
- what result was obtained;
- what mistakes were made;
- what can be reused later.

## 6. How I should approach Kaggle and practice

Kaggle practice is not only about leaderboard score.

It is useful for:

- baseline creation;
- validation design;
- feature engineering;
- experiment tracking;
- model comparison;
- error analysis;
- reproducibility.

Rules:

1. Start with a simple baseline.
2. Do not jump directly to complex models.
3. Track every experiment.
4. Change one important thing at a time when possible.
5. Compare local validation score and leaderboard score separately.
6. Do not overfit to the public leaderboard.
7. Keep code reproducible.
8. Write final conclusions.

## 7. My note-taking format

For every topic I will use this structure:

- goal of the topic;
- main concepts;
- important definitions;
- code patterns;
- practical ML meaning;
- typical mistakes;
- links with my projects;
- questions to review;
- final summary.

For every important concept I will write:

- what it is;
- why it matters;
- simple intuition;
- formula or technical detail if needed;
- Python or sklearn connection;
- typical mistake;
- how I can use it in my projects.

## 8. My progress reporting format

After every major stage I will prepare a report in the reports folder.

Report structure:

- stage;
- what was studied;
- key conclusions;
- practical work completed;
- files updated;
- problems or blockers;
- Git status;
- latest commit;
- next step.

## 9. Study rules

Rule 1. A topic is not completed after only watching a video.

Rule 2. Every topic must produce an artifact: note, notebook, solved assignment, report, experiment table or reusable code snippet.

Rule 3. Baseline first.

Rule 4. Validation before tuning.

Rule 5. Always check for leakage.

Rule 6. Every important plot must have a conclusion.

Rule 7. Track experiments.

Rule 8. Connect course topics with my own projects.

Rule 9. Use Git after every meaningful stage.

Rule 10. If I do not understand something, write it down as a question.

## 10. Preparation for Topic 1: pandas and basic EDA

Before Topic 1 I should be ready to work with tabular data.

I need to focus on:

- DataFrame and Series;
- reading CSV files;
- head, tail, shape, info, describe;
- selecting columns;
- filtering rows;
- sorting;
- value_counts;
- groupby;
- aggregation;
- missing values;
- data types;
- basic plots;
- writing conclusions.

Expected result after Topic 1:

- I can load a dataset with pandas.
- I can inspect its structure.
- I can answer simple questions about the data.
- I can perform basic EDA.
- I can write conclusions from the analysis.
- I can save notes and update progress.

## 11. Final conclusion

Stage 1 defines how I will study mlcourse.ai.

The main principle:

I do not just consume course materials. I reproduce code, solve tasks, write conclusions, connect concepts with my ML projects and track progress through Git.

Next step:

Proceed to Topic 1 - pandas and basic EDA.
