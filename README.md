# Predicting-Students-Admission-Outcome
Abstract: 
    To address the uncertainties students face during the application process, our goal is to develop a reliable model that can help them better gauge their competitiveness and offer guidance for self-improvement. I utilize self-reported data from students applying to psychology programs, which I have gathered from the GradCafe website\footnote{GradCafe: https://www.thegradcafe.com/} and matched misspelled or abbreviated school names data with GhatGPT API. I will employ Fbprophet, Multivariate Regression and other analysis to reveal the following insights: (i)  trends and patterns concerning shifts in application status, (ii) students' academic performance on each program, and (iii) impacts of students' standard test score on their admission outcomes. 

Motivation and Reason:

Historically, students have encountered difficulties due to the uncertainty inherent in the application process. To address this, I aim to provide a dependable resource to support future applicants as they navigate upcoming application cycles. Our tool is not intended to predict acceptance decisions but rather to assist users in understanding their relative standing among their peers, drawing from past experiences and offering advice on how to bolster their qualifications.

For this project, I will employ data science, feature analysis and other machine learning methodologies using self-reported student data gathered from the website known as The GradCafe. As a prominent platform for real-time graduate school admissions updates, The GradCafe enables applicants to submit their application statuses and admission results, fostering an interactive space for students to discuss and share their experiences. To gather the necessary data, students must input information such as the institutions they are applying to, program names, degree types, application cycles, demographic details, notifications (rejection, acceptance, interview), notification dates, GRE scores, GPAs, and any additional comments.

In this project, our final curated dataset includes crucial features such as the institution, major, degree, entry term, application decisions, academic performance, and student comments. Our primary focus is on the following key areas:

(i) Examine historical data to identify trends and patterns concerning shifts in application status (interviews, rejections, acceptances) and project these changes for the years 2021, 2022 and 2023.

(ii) Analyze students' GPA and GRE scores in each program, providing insights into the academic performance and aptitude of students.

(iii) Perform multivariate regression study based on GPA and GRE Scores and analyze the impact of GPA and GRE scores on admissions outcomes in psychology programs, revealing their significance while considering the varying importance across different institutions.


General information about this dataset comprises:

Size: The dataset contains approximately 200,000 data points spanning 21 different majors. Of these, 59088 data points pertain specifically to psychology, which is our main area of interest.

Features included: The dataset consists of key features such as university, program, degree type, entrance semester, decision (acceptance, rejection, or interview), decision date, GPA, GRE Verbal, GRE Quantitative, GRE Writing, GRE Subject, application status, date added, and notes or comments from the applicants.

Biases: Since the data is based on self-reported information from students, it may be subject to potential biases and inaccuracies. Students could unintentionally or intentionally misrepresent certain details, and the dataset might not be completely representative of the entire applicant pool due to self-selection biases.
