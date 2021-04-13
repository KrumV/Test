# Super awesome quick quiz APP
Create a web application that allows the users to answer random quiz questions with A) B) C) answer options from the provided list of questions (questions_list.json) and the API backend.
Create the following API endpoints to be consumed by the web application.
1.	Endpoint to retrieve a question with the possible answers from the provided questions list of existing questions that has not been answered for the specific session.
2.	Endpoint to store an answer to a question with a specific session.
3.	Endpoint to calculate the number of correct answers for a given session.
Create a test case that could be run automatically to test the score calculation API.
Create a front-end web page which displays a random question with the available answers and allows the user to answer the question storing a session id with the answer and displaying the next available question. 
Display a button that leads to a separate page with the score for the correctly answered questions in the current session. The button should be unavailable until at least three question have been answered.
Returning to the questions page after viewing the score should reset the session and start new question sequence.

Allowed technologies: .NET Core, React
