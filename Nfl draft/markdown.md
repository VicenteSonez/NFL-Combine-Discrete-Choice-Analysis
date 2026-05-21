# Homework Assignment No. 2
**Universidad de Concepción**  
**Departamento de Ingeniería Industrial**  
*Course:* Understanding Consumer Behavior through Discrete Choice Models  

---

## 📋 Academic Integrity Policy
* **Group Size:** This assignment can be done in groups of **1 or 2 people**. While general concepts can be discussed with other groups, the coding, modeling, and written report must be entirely your own original work.
* **Plagiarism:** Any form of plagiarism—including copying code or text from classmates, previous years' assignments, or online sources—will be heavily penalized and reported to the corresponding department authorities according to university regulations.
* **Use of Generative AI:** The use of Generative AI tools (e.g., ChatGPT, Gemini, Claude) to write, draft, or generate the text of your report is **strictly prohibited**. Your interpretations and conclusions must reflect your own critical thinking and genuine understanding of the subject matter.

---

## 📅 Key Details
* **Deadline:** Monday, May 4th at 13:59 hrs (before class).
* **Format & Grading:** 
  * Written Report: **50%**
  * Presentation: **50%**

---

## 🎯 Objective
Identify a relevant discrete choice phenomenon, find a suitable dataset for its study, and perform an exhaustive exploratory data analysis (EDA).  
*This task lays the foundation and defines the estimation sample you will use in Assignment 3 to estimate econometric models based on consumer utility maximization.*

---

## 📝 Written Report (50%)
The report must cover the following fundamental points:

### A. Identification of the Study Phenomenon
Clearly define the behavior or decision you want to analyze (e.g., technology adoption, mode choice, product purchase, etc.). Explain why it is important to understand consumer decisions in this specific context (public policy applications, product design, marketing, predicting behavior, etc.).

### B. Data Selection and Source
Identify and describe the source of your dataset. Ensure that the dataset contains the essential elements for discrete choice models:
* A clear set of mutually exclusive alternatives.
* The choice variable (which alternative the individual chose).
* Attributes of the alternatives (e.g., price, time, quality).
* Characteristics of the decision-makers (e.g., income, age).

### C. Exploratory Data Analysis (EDA)
Using R (or any other software), perform an exhaustive analysis to understand the behavior of your sample. 
* Present tables or graphs summarizing the main variables (distribution of choices, averages of socioeconomic variables, and attributes).
* Discuss whether the obtained sample is representative of the general population your study targets.
* Are there biases in the data collection?
* Identify the presence of outliers or missing values and explain how you decided to handle them in your code.

### D. Definition of the Estimation Sample
Based on your exploratory analysis, make and justify decisions about filtering the original dataset. Clearly specify how many observations make up your final sample and why these observations are ideal for estimating your future utility maximization models.

> [!IMPORTANT]
> You must include a link to a shared folder with your data and scripts (codes).

---

## 🗣️ Presentation (50%)
* **Submission:** Must be uploaded to Canvas by the specified deadline (**Monday, May 4th, 13:59 hrs**).
* **Duration:** Should not exceed **8 minutes**.
* **Language:** Should preferably be delivered in **English**.
* **Preparation:** Be prepared to receive and answer questions regarding your study.
* **Focus:** While the structure of the presentation is flexible, it must strictly focus on the four key areas required in the report:
  1. Problem identification
  2. Data source
  3. Exploratory analysis
  4. Definition of the estimation sample

---

## 📊 Rubrics

### Rubric 1: Written Report

| Criterion | Weight | Description of Excellence |
| :--- | :---: | :--- |
| **1. Phenomenon Identification** | **20%** | Defines the discrete choice problem with absolute clarity. Convincingly and exhaustively justifies the practical or theoretical relevance of studying this behavior. |
| **2. Data Selection and Source** | **15%** | Accurately describes the data source. The chosen dataset perfectly meets the requirements: mutually exclusive alternatives, a clear choice variable, attributes of the alternatives, and individual characteristics. |
| **3. Exploratory Data Analysis (EDA)** | **30%** | Presents a deep and relevant statistical and visual analysis (tables/graphs). Critically discusses the representativeness of the sample. Logically and transparently identifies and handles outliers and missing values. |
| **4. Definition of the Estimation Sample** | **15%** | Explains in detail the filtering criteria applied. Justifies why the final sample is ideal for future utility maximization model estimation, specifying the final sample size. |
| **5. Code Quality (R)** | **10%** | The R script (or other software code) is fully functional, reproducible, and excellently structured. It includes clear comments explaining each step of the data cleaning and analysis process. |
| **6. Format and Writing** | **10%** | The report has an impeccable structure, with no spelling or grammatical errors. It presents an appropriate academic tone (whether in English or Spanish) and strictly follows the requested PDF format. |

### Rubric 2: Oral Presentation

| Criterion | Weight | Description of Excellence (Full Score) |
| :--- | :---: | :--- |
| **1. Synthesis and Coverage** | **30%** | The presentation evenly and clearly covers the 4 key required points: phenomenon, data source, exploratory analysis, and sample definition. It does not digress into irrelevant information. |
| **2. Subject Mastery and Q&A** | **35%** | The student demonstrates a deep knowledge of their dataset. Answers questions precisely, with well-founded arguments and confidence, demonstrating analytical mastery. |
| **4. Supporting Material** | **20%** | Slides are visually appealing, readable, and not overloaded with text. The graphs presented (derived from the EDA) are clear and effectively support the oral speech. |
| **5. Communication and Language** | **15%** | Maintains eye contact, an appropriate voice volume, and a good pace. Adapts to the preference for presenting in English with fluency and clarity, communicating ideas smoothly. |
