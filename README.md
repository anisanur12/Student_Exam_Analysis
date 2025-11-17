# student Performance Analysis 
## Analysis of Factors Affecting Student Performance 



### Dataset Content 
This project analyses a dataset of over 6,000 student exam score entries in respect of various factors that may contribute to exam outcome. Analysing these factors paints a clearer picture on what students need in order to support their learning and aid them in reaching their academic goals. 

The factors include but are not limited to:

- Hours studied
- Attendance
- Parental involvement
- Access to resources
- Sleep hours 
- Level of Motivation
- Access to Internet
- Tutoring Sessions
- School type
- Learning disabilties
- Exam score 

The dataset has 6607 rows, 27 columns and included missing values but no duplicates. This dataset was provided by Kaggle. 


### Hypotheses and Validation 

H1- Students who studied longer hours performed better in their exams compared to students who studied less. 

Validation: Selected the highest and lowest exam scores, created new function to visualise both features using bar and scatter plots. 

H2- Whether a pupil attends a private or public school has no effect on their exam outcome. 

Validation: Utilised information from H1, tested the exam scores against the school type. Visualised information using box plots. 

### Project Plan and Analysis Technique 

As a junior data analyst at Code Institute and former teacher, I was interested in analysing how various external factors contributed to academic performance. I was especially intrigued to assess how the hours spent revising and preparing for exams impacted the results. If a student were to study for longer hours, would it guarantee test success? What other factors could affect performance?

I retrieved the data, loaded the data and began the cleaning process to ensure there were no duplicates or missing data that could affect the analysis. I then began analysing the data using python coding, manipulation and visualisation tools such as matplotlib and plotly. 

### Tools and Libraries used:

- Python
- Pandas
- Jupyter Notebook
- Matplotlib



### Conclusion

Students who studied 14 or more hours generally performed better on the exams than those who studied for lesser hours. With the exception of one pupil, although this pupil studied for 14 hours, they scored lower marks. Upon further inspection, their data revealed lower parental involvement, lower access to resources, less motivation and no tutoring sessions compared to their peers who studied for a similar amount of time. 

As I hypothesised, the type of school a pupil attends has little to no impact on exam performance. What makes a difference are factors including motivation, study hours, parental involement and access to resources. Box plot confirmed minimal difference and deviation. 


### Ethical Considerations 

Students were anonymised and no personal details or identifiers were used including time and date exams were taken. GDPR with educational data is always complex and requires parental consent, authorised only access, oversight and approval from school. 


### Developer Roadmap

Analysing this dataset was very insightful, there are many questions that can be derived. The next steps would be to train and test machine learning models to predict the grades six months before their final exams. In addition, use these predictions for effective planning and provide early intervention to enhance academic performance. 


### Websites and Sources
- www.Kaggle.com 
- www.pandas.pydata.org
- www.geeksforgeeks.com
- www.w3schools.com
- stackoverflow.com
- ChatGPT for errors


