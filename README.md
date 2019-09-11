# DSND-Starbucks_Capstone_Project
 
## Contents:

1. [Description](#description)
2. [Packages and Dependency](#Packages) 
3. [Authors](#authors) 
4. [Acknowledgement](#acknowledgements)  
5. [Results](#results) 
6. [Improvement](improvement)


<a name="descripton"></a>
## Description 
This Project is one of Udacity Requirements to complete Data science Nano Degree 

In this project, We will try answering the some quesion regarding customers of starbucks and build model to predicte some information about customers

Installing
Clone this GIT repository:
git clone 
(https://github.com/faizzal/Starbucks_Capstone_notebook.git)

<a name="Packages"></a> 
## Packages and Dependency 
•	Python 3 
•	Machine Learning Libraries: NumPy, Pandas ,sklearn   
 
Additional Material
In the data folder you can find three json files:
1.	data/portfolio.json 
2.	data/profile.json
3. data/transcript.json

And there is PDF file in root folder contain report of the project
<a name="Authors"></a> 
## Authors 
(https://github.com/faizzal)
 
<a name="acknowledgements"></a> 
## Acknowledgements

•	Udacity for help me to pass this project and provide me all material that I need it 
•	Starbuck  providing dataset that helps to work on model and cleaning data

## Results
As we See we apply the the Random Forest and Logistic regression on combining dataset for starbuckes company and it was contain some data about clients and offers our goal was build model to predict if the customer will respond to the offer or not so we start training our data using our models and evaluates the model we find the accuracy of random forest was good and the accuracy and performance are  better compared to logistic regression also in I use classification_report to compare the models and it was model robust enough to be trusted regarding the result of evaluation.

In first section I was wandering and have some questions like what is the most gender of Starbucks clients? And we find the male was more than other gender also whom have heist average of income based on gender? and the answer was Female  and I asked about the event that send it to customers and measure the counts between the events we can see most event are transactions and the complete event is almost 50 % of   received even.

## Improvement
After we training the models I try to make some model is better so I was using my local machine rather than Jupiter notebook workstation included in with project  because some of models was take long time to training them like the random forest model I tray to enhance the model by increase the  max_depth and that make the model is better than first training the f- score was increasing dramatically witch it was give more confidant with results lately. Also, I try to enhance logistic regression by increase some property but I could get better the final result of that.


