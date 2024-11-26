# Reproducibility Project of Enhancement of E-Learning Student’s Performance Based on Ensemble Techniques by Alsulami et al. (2023, Electronics)
Amy Tan

## Project Overview

This project takes inspiration from the open science movement and consequently attempts to reproduce the results from the 2023 paper, [Enhancement of E-Learning Student’s Performance Based on Ensemble Techniques](https://www.researchgate.net/publication/369489648_Enhancement_of_E-Learning_Student's_Performance_Based_on_Ensemble_Techniques) by Abdulkream A. Alsulami, Abdullah S. AL-Malaise AL-Ghamdi, & Mahmoud Ragab (2023, Electronics), which can also be found in the original_paper folder.


## Installation and Setup
### Codes and Resources Used

- **Editor Used:**  Anaconda
- **Python Version:** Python 3.11.5

- Full notebook and code can be found in the writeup folder

### Python Packages Used

- **Data Manipulation:** `pandas`
- **Data Visualization:** `matplotlib`
- **Machine Learning:** `sklearn`
  
## Data
### Source Data
The data used in this project is `xAPI-Edu-Data.csv`, initially downloaded from where the authors' originally uploaded on [Kaggle](https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data), saved into the variable `edu` in the Juypter Notebook. This csv is saved in the `data` folder.

### Cleaned Data
All categorical variables in the dataset were cleaned and transformed into corresponding numerical values to run subsequent classifier models - this dataframe is saved in the `data` folder under the name `edu_dummy` (and it stored under the same variable name in the notebook). The dictionary of cleaned/transformed variables is as follows for reference:


| **Column**               | **Category** | **Numerical Representation** |
|:-------------------------|:-------------|:-----------------------------|
| Gender                   | Male         | 0                            |
|                          | Female       | 1                            |
| Nationality              | Kuwait       | 0                            |
|                          | Lebanon      | 1                            |
|                          | Egypt        | 2                            |
|                          | Saudiarabia  | 3                            |
|                          | Usa          | 4                            |
|                          | Jordan       | 5                            |
|                          | Venzuela     | 6                            |
|                          | Iran         | 7                            |
|                          | Tunis        | 8                            |
|                          | Morocco      | 9                            |
|                          | Syria        | 10                           |
|                          | Palestine    | 11                           |
|                          | Iraq         | 12                           |
|                          | Lybia        | 13                           |
| Stageid                  | lowerlevel   | 0                            |
|                          | middleschool | 1                            |
|                          | highschool   | 2                            |
| Gradeid                  | G-02         | 2                            |
|                          | G-04         | 4                            |
|                          | G-05         | 5                            |
|                          | G-06         | 6                            |
|                          | G-07         | 7                            |
|                          | G-08         | 8                            |
|                          | G-09         | 9                            |
|                          | G-10         | 10                           |
|                          | G-11         | 11                           |
|                          | G-12         | 12                           |
| Sectionid                | A            | 0                            |
|                          | B            | 1                            |
|                          | C            | 2                            |
| Topic                    | IT           | 0                            |
|                          | Math         | 1                            |
|                          | Arabic       | 2                            |
|                          | Science      | 3                            |
|                          | English      | 4                            |
|                          | Quran        | 5                            |
|                          | Spanish      | 6                            |
|                          | French       | 7                            |
|                          | History      | 8                            |
|                          | Biology      | 9                            |
|                          | Chemistry    | 10                           |
|                          | Geology      | 11                           |
| Semester                 | F            | 0                            |
|                          | S            | 1                            |
| Relation                 | Father       | 0                            |
|                          | Mum          | 1                            |
| Parentansweringsurvey    | No           | 0                            |
|                          | Yes          | 1                            |
| Parentschoolsatisfaction | Bad          | 0                            |
|                          | Good         | 1                            |
| Studentabsencedays       | Under-7      | 0                            |
|                          | Above-7      | 1                            |
| Class                    | M            | 0                            |
|                          | L            | 1                            |
|                          | H            | 2                            |

## Results and evaluation

## References
- Parts of code adapted from [Umberto Mignozzetti's](https://umbertomig.com/) CSS 201/202 course - umbertomig@ucsd.edu
- 
  
## Future work
- 

## License
[MIT License](https://opensource.org/license/mit/)
