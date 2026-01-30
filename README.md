# Researching Fairness in Resume Screening AI

### 1. Project Overview
Investigated potential racial and gender biases in automated AI resume screening tools to determine if algorithmic scoring unfairly penalizes candidates based on demographic indicators.

### 2. Dataset
* **Racial Bias Test:** 40 resumes with names associated with different racial backgrounds (20 White-associated, 20 African American-associated).
* **Gender Bias Test:** 80 samples from a **Kaggle inmate dataset** to provide a diverse pool of names.

### 3. Approach
* **Tools:** ResumeScreening.AI (Web Application).
* **Techniques:** Systematic black-box testing. I inputted identical job descriptions and resumes, only varying the names, to observe changes in the "Similarity Score."

### 4. Results
* **Metrics:** Observed a slight gender gap where women's names scored **0-1% lower** on average than men's.
* **Insights:** While no massive racial bias was detected in this specific tool, I found that specific names triggered unexplained score fluctuations, highlighting the "black-box" nature of proprietary HR tech.

### 5. Key Learnings
This project taught me the ethics of AI and the difficulty of auditing closed-source models. I learned how to design a controlled experiment to isolate variables (like names) while keeping all other data points constant. It made me a more critical developer regarding "Algorithm Transparency", understanding that a model can be biased even if the developer didn't intend it to be.
