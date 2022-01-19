# Neural_Network_Charity_Analysis
Module 19

Using machine learning and neural networks, the team will use the features in the provided attached dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

What is being created:
Deliverable 1: Preprocessing Data for a Neural Network Model
Deliverable 2: Compile, Train, and Evaluate the Model
Deliverable 3: Optimize the Model
Deliverable 4: A Written Report on the Neural Network Model (README.md)

<img width="963" alt="2022-01-18 (1)" src="https://user-images.githubusercontent.com/86638388/150060884-df7f316a-e2ce-43ff-a2b7-061ae69971ad.png">

<img width="602" alt="2022-01-18 (2)" src="https://user-images.githubusercontent.com/86638388/150061177-6c90ea32-581d-4e37-b4a5-771c7ae307c5.png">

The initial model only achieved a accuracy of 72.8% so additional optimization was necessary

Model #1 (adding an additional layer)

<img width="488" alt="2022-01-18 (3)" src="https://user-images.githubusercontent.com/86638388/150061677-17af0d4c-6abf-491e-bd52-646a33580ef7.png">

accuracy only rose to 73.6% so another optimization model was run.

Model #2 (additional neurons to the hidden layer)

<img width="539" alt="2022-01-18 (4)" src="https://user-images.githubusercontent.com/86638388/150061960-0b54996e-671d-4d69-b95e-d485d587f60b.png">

accuracy fell to 73.7%.

So another model was run.

Model #3 (Changing the activation functions)

<img width="486" alt="2022-01-18 (5)" src="https://user-images.githubusercontent.com/86638388/150062136-cbe3daca-61db-444d-92a4-7f70d98bac1e.png">

accuracy fell again.  This time to 73.6%

In summary:
Despite all these models, accuracy never grew much beyond 73%.  This is below the target predictive accuracy of 75%.  Of cource, more modeling could be done to see if it can exceed the 75%.  Perhaps exploring more hidden levels or neurons.




