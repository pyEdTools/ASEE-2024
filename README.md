# Code for Shailja et al. American Symposium on Engineering Education (ASEE) 2024
Code for the paper on "Scaffolding AI research projects increases self-efficacy of high school students in learning neural networks (Fundamental)" published at ASEE 2024.

## Important note
The code is provided on this repository to maximize the reproducibility of our study. However, since we cannot post the student data publicly, only template of the code is provided. You may need to fix the file paths and use the code as a guideline to fix other errors depending on the way you have stored your data. Use the jupyter notebook's cached output as guidance.

## Installation
From your terminal or any other package manager compatible with PyPi, run `pip install requirements.txt`

## How to run the code?

1. Run the `gpt_survey_analysis.ipynb` with your open-ended survey data. Make sure to store all student responses in `all_responses.json`. The GPT rated responses according to your criteria specified in the `gpt_survey_analysis.ipynb` will be stored in the `rated_responses.json`.

2. For the inter rater reliability analysis, run the `inter_rater_reliability.ipynb` with the GPT and expert rated files available.

3. For other data analysis skeleton, check out the `data_analysis_skeleton.ipynb`.

Contact ayushpandey at ucmerced dot edu for any questions.
