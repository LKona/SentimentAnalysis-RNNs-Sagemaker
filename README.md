# SentimentAnalysis-RNNs-Sagemaker
Udacity Deep Learning Nanodegree Project - Deploying a sentiment analysis model using Amazon Sagemaker and PyTorch.

Objective: Construct a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. Create this model using Amazon's SageMaker service. In addition, deploy the model and construct a simple web app which will interact with the deployed model.

What I learnt:

1. Downloading or otherwise retrieving the data.
2. Processing / Preparing the data (Using BeautifulSoup, mapping words that appear in the reviews to integers, pad the data)
3. Uploading the processed data to S3.
4. Building and training own PyTorch model.
5. Testing the trained model (typically using a batch transform job).
6. Deploying the trained model.
7. Using the deployed model and test it. (Then delete the endpoint.)
8. Deploying the model for the web app.
9. Using the model for the web app.
    * Setting up a Lambda function.
    * Setting up the API Gateway.
    * Deploying the app and accessing via index.html.
