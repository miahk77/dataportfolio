# dataportfolio

# Build settings
theme: minima
This repository contains data analysis and web dev projects stored as notebooks created with Jupyter Notebook.

# [Project 1 : Study App ](https://github.com/miahk77/dataportfolio/blob/main/study_app.ipynb)
- Created a study app using functions and user input.
- The app allows the user to choose between 3 options : add a question, initiate a study session and quit. The first two options are run using a function.
- Add question option : The app prompts the user to manually enter questions, responses, the correct answer, and a list of topic tags. 
- Study session option : The app randomly selects a question from the list of questions, allows the user to input a response and view all possible responses, and then informs the user on whether their answer is correct. 

# [Project 2 : Analysing SAT and ACT Scores - Data Analytics using Pandas](https://github.com/miahk77/dataportfolio/blob/main/Assignment%202%20-%20College%20Board.ipynb)

## Deliverables:
- Cleaned the data with rationale-backed handling of null or missing values.
- Joined the data sets together into a single DataFrame (this was named combinedactsat for reference).
- Correlated participation rates in SAT tests with ACT rates. Trends do not correlate - led to observation that states generally choose to adopt only one standardised test.

![](/images/actparticipation.png)
![](/images/satparticipation.png)

- Explored and compared chosen state's situation with others. Data provided included percentage of students who score equal or higher than 21 in California (PctGE21). Here we can see that ACT participation is low in California in comparison to other states, and the percentage of students who score equal or higher than 21 is 40%, which is quite high. According to the Princeton Review, a score of 23 in the ACT is above the national average. Based on this observation and the performance of students who do take this test in California, we can reccomend that more counties in the state push for the ACT test.

![](/images/california.png)

