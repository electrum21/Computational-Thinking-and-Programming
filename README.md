# Computational-Thinking-and-Programming

This project was completed in a team of 5, as part of Nanyang Technological University (NTU) SC1003 Computational Thinking and Programming Module in Year 1.

### Project Background
The "Introduction to Data Science" is a Year 1 course offered at NTU. This course attracts a diverse group of students from various disciplines due to its widespread applicability and popularity.
Recently, the course has experienced a significant increase in enrollment, with 6,000 students registered. These students are organized into 120 tutorial groups, each consisting of 50 students. The course coordinator is facing challenges in efficiently forming teams for a mini-project component of the course.

### Project Objective
To address this issue, our application helps to organize students into teams of five for the data science mini-project, using the provided csv file (records.csv) consisting of 6,000 student records with their Tutorial Group, Student ID, Name, School, Gender, and CGPA. Our application ensures that teams comprise only members of the same tutorial group, and also ensures fairness and diversity when forming teams by considering the following factors:
**1. School Affiliation:** To ensure a mix of knowledge and skills, no team should have a majority of students from the same school.
**2. Gender:** To promote gender diversity, no team should have a majority of students of the same gender.
**3. Current CGPA:** To balance academic performance, teams should not consist predominantly of students with very high or very low CGPAs.

### Project Outcome
Our program strives for balanced and diverse team compositions, taking into account the above criteria.
We managed to achieve a fairly even team distribution across tutorial groups, with the detailed results being available in the Jupyter Notebook file.
Through this project, we have learnt and practised the computational thinking principles of Decomposition, Pattern Recognition, Abstraction and Algorithm Design.

### Project Contributions
For the report, I crafted the report structure and documented the details of our thinking processes, and provided some insights into areas for future improvement.
For the program, I developed the CSV reading function, the helper functions, and the first algorithm which involves distributing teams based on sorting of students by their CGPA.
