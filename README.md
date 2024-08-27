# takneekmlps
AI PROJECT CYCLE

NOTE TO THE READER: I have tried to explain all the stages of the project in brief and in layman terms. Sometimes however, to explain my reasoning, I have given a bit of background about the subject, so kindly bear with me!

1. Any AI Project goes through the following domains:

a) Problem Scoping: This aspect of the project majorly involves, identifying the problem, noting it down and finding the right motivation and will to solve the problem using AI & other techniques. For the sake of this project, the problem statement was already given and is focused on achieving a goal.

b) Data Acquisition: Once the problem statement is identified, we need to acquire accurate and relevant data from credible sources. This data will then be used as to train and test our AI Model, hence forming the backbone of our project. At this stage, it is necessary to ensure that the data is thoroughly vetted. 
Again, for the purpose of this project, the dataset was already provided in the form of a CSV file.

c) Data Exploration: After we have acquired and rendered our data into our coding environment (this was done using pandas library), it is important to explore that data in order to choose the right model for our problem statement. With reference to this project, data exploration was done using a python library, “matplotlib”. This library helped create scatter plots (these plots can be found in attempt1.ipynb and attempt2.ipynb), which were instrumental in choosing the correct model for the project (as is explained further below).

d) Modelling: After the data has been thoroughly examined and processed, we need to find an appropriate model which will help us achieve our goal. Models can be broadly divided into Rule Based and Learning Based models. Since, in this project we have to use old data to make predictions on fresh data, a rule-based model would be fundamentally flawed. Hence, I opted for a learning-based model. 
Learning-Based models can also be further divided into Machine Learning models and Deep Learning models, but for our task Deep Learning is not relevant because it deals with extremely large amount of data. Hence, a machine-learning based model was chosen. 

Now, learning based models can also be classified into three types:
1. Supervised Learning Models: These models are trained on labelled datasets, ex. With respect to our project, all the data in the CSV file has a “header”, which helps in designating and distinguishing trends w.r.t. the multiple variables. In supervised learning models, we have classification and regression. Classification is used more for discrete data points which can be classified into groups (for ex. Grades obtained by students in a class). As was evident during data exploration, the scatter plots suggested no such distinct classification system and hence regression was the go to model!
2. Unsupervised Models: These are used when the data is not labelled and the model is expected to figure out trends and patterns in the data and identify it.
3. Reinforcement Learning Models.

e) Evaluation: This is one of the most important aspects of the project cycle. We use various evaluation metrics to see how our model is performing using testing data. With respect to this project, I have used a metric known as "R² score". This metric basically measures the variance in the dependent variable that is predictable from the independent variables. (can be found in the attempt2 file with results). 
