# BoonmeeLab Data Assignment: Thai Travel Thailand (TTT)
![BoonmeeLab Logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.boonmeelab.com%2F&psig=AOvVaw0NV58ZQlNHkSOB4VvW5G-l&ust=1740891652726000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCIjKj_aM6IsDFQAAAAAdAAAAABAQ)

This repository contains the code and analysis for the data assignment provided by **BoonmeeLab**:bar_chart:. The task involves analyzing user travel data from the Thai Travel Thailand (TTT) app to derive insights and answer specific business questions.

## Project Overview

The goal of this project is to process and analyze travel data to answer the following questions:

1. What is the total number of trips?
2. How many provinces are there in the trip with the most number of provinces?
3. What are the most common province pairs that people travel to in the same trip?
4. How can we use the data to support our client’s business?

## Data

The input data consists of user travel logs with timestamps and locations. The output is a CSV file with trip details, including trip ID, user ID, start date, end date, and a list of provinces visited.

## Code

The code for this project is written in Python and is available in the Jupyter Notebook `Boonmee_DA_test.ipynb`.

### Dependencies

To run the code, you need the following Python libraries:

- pandas
- numpy
- datetime

You can install these dependencies using pip:

```bash
pip install pandas numpy
```
### Running the Code on Google Colab

1. Open the notebook in Google Colab by clicking the button below:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kopmean/BoonmeeLab_Test/blob/main/Boonmee_DA_test.ipynb)

2. Once the notebook is open, run the first few cells to install the necessary libraries and download the data using `gdown`:
```bash
!gdown ljVwj14b2fndW3Uj9smTUnfbdhLnF9g9t  # Download transaction.csv
!gdown itfZZlnYFdtOTrlr_xD86FFGwgZzsREQ6  # Download user.csv
```
3. Continue running the remaining cells in the notebook to process the data and generate the output.

## Output

The output is a CSV file named `output.csv` with the following columns:

- `trip_id`
- `user_id`
- `start_date`
- `end_date`
- `province_list`

## Questions and Answers

The answers to the assignment questions are provided in the notebook and can be exported as a PDF for submission.

## Submission

- **Code**: The Jupyter Notebook and any additional scripts.
- **Output**: The generated CSV file.
- **Answers**: A PDF document with the answers to the assignment questions.

## Acknowledgments

- Thanks to **BoonmeeLab**:bar_chart: for providing the data and the assignment.
- Special thanks to the open-source community for the libraries used in this project.

## Contact

For any questions or further information, please contact **Sira Attawanich** at kopsira@gmail.com.
