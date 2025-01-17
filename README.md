# Mobile Games A/B Testing Project
This is an A/B test with a mobile game, Cookie Cats. \
Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level. It also features singing cats. We're not kidding!

As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention and game rounds.

## Project Overview

This project focuses on applying A/B testing to analyze user behavior in a mobile gaming context. The goal is to determine whether specific changes or features introduced to a subset of users have a statistically significant impact on their engagement or revenue generation.

## Key Objectives

- Conduct A/B testing analysis on provided datasets.
- Assess user behavior and key performance indicators (KPIs).
- Draw actionable insights to improve decision-making in mobile game development and marketing.

## Methodology

1. **Data Loading and Exploration:**
   - Imported and cleaned datasets related to user activity and game performance.
   - Explored basic statistics and visualized data distributions.

2. **Data Preparation:**
   - Pre-processed data for compatibility with statistical tests.
   - Identified control and test groups. Control group - Gate 30, Test group - Gate 40.

3. **A/B Testing Procedure:**
   - Formulated hypotheses regarding user behavior changes.
   - Selected appropriate statistical tests (e.g., t-tests, chi-square test) to compare control and test group metrics.

4. **Analysis and Visualization:**
   - Conducted tests to assess statistical significance.
   - Visualized results to highlight trends and differences between groups.

## Results

- Key metrics analyzed include:
  - User engagement rates.
  - Retention rates.

- Findings suggest that the new product feature, didn't increase/decrese the retention rates. Many of the players haven't reached gate 30 to test the new feature and conclude that these results are accurate.

## Improvements
We should consider moving the gate from level 30 to level 20. Additionally, we need to explore new strategies to increase user engagement, encouraging players to continue playing until at least gate 30 rather than dropping off around gate 15.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy (for statistical tests)

## How to Use

1. Clone this repository.
2. Open the provided Jupyter Notebook to review the detailed analysis.
3. Modify and adapt the notebook for your own A/B testing needs.


