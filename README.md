# 🎓 Student Performance Analysis

This project explores the **Student Performance Dataset** to understand how various factors—such as gender, parental education, lunch type, and test preparation—affect students' scores in **math**, **reading**, and **writing**. The analysis involves data cleaning and statistical testing using Python.

## 📊 Dataset

- **Source**: [Student Performance Dataset on Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Attributes**:
  - `gender`
  - `race/ethnicity`
  - `parental level of education`
  - `lunch`
  - `test preparation course`
  - `math score`
  - `reading score`
  - `writing score`

## 📌 Objectives

- Explore the dataset and perform preprocessing
- Statistically test hypotheses about:
  - Gender-based performance differences
  - Influence of lunch type on scores
  - Effect of test preparation on performance
  - Impact of parental education level
  - Relationships between categorical features using Chi-Square tests

## 🛠 Tools & Libraries

- Python
- pandas
- scipy.stats (for ANOVA, t-tests, Chi-Square)

## 📈 Key Findings

1. Do male and female score differently?

    Yes, there is a significant difference in scores by gender:
    Males tend to score higher in math
    Females tend to score higher in reading and writing.
2. Does type of lunch influence score?

    Yes, there is a statistically significant difference in all three scores based on lunch type.Students with standard lunch performed better on average.
3. Does parent level education affect child's performance?

    Yes, there is a statistically significant difference in student performance. Those whose parents have higher education, score better. 
4.  Is test prep course completion necessary for good score?
  
    Yes, completing the test prep significantly improves performance. The p-value < 0.05, so the result is statistically significant. On average, students who completed the prep score ~7.6 points higher.
5. Are race and gender of students related in some way?
    
    There is no statistically significant relationship between race and gender at the 5% level.
6. Which gender is more likely to complete the test prep course?

    There is no statistically significant relationship between test prep completion and gender at the 5% level.
7. Which subject has the highes avg?

    Reading


8. Is there a relation between the parent level  of education and the gender of student ?

    There is no statistically significant relationship between parent level  of education and the gender of student at the 5% level.

9. Is there a relation between the parent level  of education and the ethnicity of student ?

    There is no statistically significant relationship between parent level  of education and the ethnicity of student at the 5% level


## 📁 Project Structure
- student_performance_analysis.ipynb
- readme.md
- student performance dataset

## 🧪 Statistical Methods Used

- ✅ **Independent t-tests** for comparing group means (e.g., gender)
- ✅ **One-way ANOVA** for multi-group comparisons (e.g., parent education levels)
- ✅ **Chi-Square tests** for checking association between categorical variables

## 🙋‍♀️ Author

**Divya Bansal**  
📧 bansaldivya20082005@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/divya-bansal01) | [GitHub](https://github.com/Divyabansal20)


