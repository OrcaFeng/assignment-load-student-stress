# The Association Between Assignment Load and Stress Among University Students

## Project Overview

Student stress is an important issue in higher education. Academic workload, including assignment load, may be associated with students' stress experiences. This project uses the University Student Stress Dataset to examine the relationship between assignment load and student stress among undergraduate students.

### Research Question

Is assignment load associated with student stress among university students?

### Hypothesis

Students with a higher assignment load are expected to report higher stress scores.

### Researcher

Kewen Feng

ORCID: https://orcid.org/0009-0006-4936-1730

### Metadata Standard

This project uses the Data Documentation Initiative (DDI) as the metadata standard. This DDI was selected because it is designed for documenting survey and observational data in the social and behavioral sciences. Since this dataset contains survey responses from university students, DDI provides an appropriate framework for describing the dataset, methodology, variables, and data access information.

---

## Data & File Overview

The dataset used in this project is the **University Student Stress Dataset**.

The dataset contains responses from 3,000 undergraduate students and includes 18 variables related to demographic characteristics, academic experiences, lifestyle habits, socioeconomic factors, psychological factors, and stress.

### Dataset File

| File Name | Format | Observations | Variables | Description |
|---|---|---:|---:|---|
| university_student_stress_dataset.csv | CSV | 3,000 | 18 | Contains student-level survey responses and stress-related measures |

The dataset contains no missing values.

### Key Variables for This Project

The two main variables used in this project are:

- **Assignment_Load**: A measure of students' academic assignment load.
- **Stress_Score**: A derived measure representing student stress.

---

## Sharing and Access Information

The dataset was obtained from Mendeley Data.

**Dataset Title:** University Student Stress Dataset

**DOI:** https://doi.org/10.17632/rc5htd5dfr.1

**Version:** 1

**Publication Date:** December 25, 2025

**Institution:** University of Rajshahi

### License

The dataset is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.

This license allows users to share and adapt the dataset as long as appropriate credit is given to the original creators.

---

## Methodological Information

The original dataset was collected from undergraduate students attending public, private, and national universities in Bangladesh.

Data were collected using a structured Google Form survey distributed by email. The survey was sent to 3,710 students, and 3,000 complete and anonymous responses were included in the final dataset.

The dataset includes demographic, academic, lifestyle, socioeconomic, and psychological variables related to student stress.

Because the data were collected using a survey rather than an experimental design, relationships identified between assignment load and stress should be interpreted as associations rather than causal effects.

---

## Data Dictionary

The following data dictionary describes the 18 variables included in the cleaned dataset. Variable definitions are based on the documentation provided with the original dataset.

| Variable Name | Readable Variable Name | Measurement Unit | Allowed Values | Definition |
|---|---|---|---|---|
| Age | Age | Years | 19–24 | Student's age in years. |
| Gender | Gender | N/A | Male, Female, Other | Student's reported gender. |
| University_Type | University Type | N/A | Public, Private, National University | Type of university attended by the student. |
| Study_Hours | Study Hours | Hours per day | Numeric | Number of hours the student studies per day. |
| Class_Attendance | Class Attendance | Percent (%) | Numeric | Percentage of class attendance per semester. |
| Tuition | Extra Coaching | N/A | Yes, No | Indicates whether the student receives extra coaching. |
| Exam_Frequency | Exam Frequency | Rating scale | 1–10 | Student's reported exam frequency rated on a 1–10 scale. |
| Assignment_Load | Assignment Load | Rating scale | 1–10 | Student's reported assignment load rated on a 1–10 scale. |
| Sleep_Hours | Sleep Hours | Hours per day | Numeric | Number of hours the student sleeps per day. |
| Social_Media_Use | Social Media Use | Hours per day | Numeric | Number of hours the student spends on social media per day. |
| Screen_Time | Screen Time | Hours per day | Numeric | Total number of screen hours per day. |
| Physical_Exercise | Physical Exercise | N/A | Yes, No | Indicates whether the student reports engaging in physical exercise. |
| Family_Income_Level | Family Income Level | N/A | Low, Medium, High | Student's reported family income level. |
| Peer_Pressure | Peer Pressure | Rating scale | 1–10 | Student's self-rated level of peer pressure. |
| Family_Support | Family Support | Rating scale | 1–10 | Student's self-rated level of family support. |
| Anxiety_Level | Anxiety Level | Rating scale | 1–10 | Student's self-rated anxiety level. |
| Stress_Score | Stress Score | Derived score | Numeric | A derived combined score representing student stress. |
| Stress_Level | Stress Level | N/A | Low, Medium, High | Categorical classification of student stress level. |

**Note:** The original documentation describes `Physical_Exercise` as the number of days per week of exercise, but the cleaned dataset contains binary Yes/No values. This data dictionary reports the values observed in the cleaned dataset and notes the discrepancy.
