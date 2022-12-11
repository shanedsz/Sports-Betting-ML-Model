# Sports-Betting-ML-Model
We will be creating a sports betting model/bot to help people with there bets and increase there win rate.

# Aim 
The goal of this project is to help people who are placing bets on NBA and EPL games to have a
higher probability of winning their bet. We will use machine learning algorithms
(RandomForest, LogisticRegression, and Sequential), to make predictions, as well as compare
the accuracy of these models. The end product will be a chatbox utilizing AWS Lex which a user
will be able to ask for the predicted winner of a game they choose.

# Objectives
1. Find reliable and accurate data to using Kaggle. The data we are looking for will be for
more than 10 seasons and will include over 10 columns of statistics, for every game
played in every season
2. Perform data cleaning on the data and prepare it for machine learning algorithms (dropna,
OneHotEncoder, etc.)
3. Create three different .py files with a function that runs each of the algorithms mentioned
(RandomForest, LogisticRegression, and Sequential)
4. Run the data through the functions and test their accuracy for comparison
5. Create a Amazon Web Services Bot which informs client on the pick according to the algorithm 

# Machine Learning

We used a variety of machine learning models to fit the training data and then evaluated by using the testing data, and calculations. Predictions were made by using sample of new data, with the future intention that predictions would be then compared. A new machine learning library and machine learning model was used which can be seen by the code in the machine learning and the code for the bot.


# Why use the AWS Bot?

This bot is also connected to a number which you can call and get the pick you request according to the game you bet on
AWS Chatbot is an interactive agent that makes it easier to monitor and interact with your AWS resources in your Slack channels and chat channels. 
By using AWS Chatbot, you can receive alerts and run commands to return diagnostic information, invoke AWS Lambda functions, and create AWS Support cases so that your team can collaborate and respond to events faster.

We used the bot so we could quickly discover and act on cost anomalies, gain near real-time visibility into anomalous spend with AWS Cost Anomaly Detection alert notifications in Slack by using AWS Chatbot. This also allowed us to learn more about cost anomaly detection.
We ran AWS Command Line Interface commands from Slack channels to remediate your security findings.

# What will we do next ?

We will use pyspark to improve the accuracy of the bot and enhance the aws code using the machine learning code. PySpark is a Python API for Apache Spark. Apache Spark is an analytical processing engine for large scale powerful distributed data processing and machine learning applications.PySpark is a general-purpose, in-memory, distributed processing engine that allows you to process data efficiently in a distributed fashion. Applications running on PySpark are 100x faster than traditional systems.You will get great benefits using PySpark for data ingestion pipelines. Using PySpark we can process data from Hadoop HDFS, AWS S3, and many file systems.PySpark also is used to process real-time data using Streaming and Kafka. Using PySpark streaming you can also stream files from the file system and also stream from the socket.PySpark natively has machine learning and graph libraries

In the future this bot will allow us to respond better to security issues and improve incident management response times. We could then collaborate and resolve IT incidents faster from chat channels with AWS Systems Manager Incident Manager.

# Conclusion

We were able to do what we set out to do based on the time given. We realized this could be the start of a business where users will use our site to make more accurate bets. When enough users use it, we will have enough web traffic to generate advertising revenue. The combination of AWS and ML models are extremely useful tools for everything we have done. We realized that the players on teams are known to keep changing so we should rather get the variables of the individual rather than just the team. We also realized using historical data may be difficult because players change and we are finding ways to overcome that obstacle. Furthermore we are finding ways to use current roster instead of all the way back to 2014 which could be seen as too long. 

