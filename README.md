
# Sentiment Analysis LSTM model with Sagemaker and PyTorch

Repository contains end to end sentiment analysis model creation (using LSTM),
and deployment steps to create a simple functional web app in front of the created model, hosted on SageMaker endpoint.

All the steps are documented in the [notebook](https://github.com/bdnf/sagemaker-deployment/blob/master/SageMaker%20Project.ipynb).

# Deployment Architecture

[!Architecture](/assets/Web%20App%20Diagram.svg)

# Example web interface:

[!Positive](./assets/positive.png)

[!Negative](./assets/negative.png)

---- 
**Technologies used:**
<br> Python 3.6
<br> Libraries:
- PyTorch to Machine Learning
- pandas
- numpy
- nltk
- beautifulsoup4
- html5lib

AWS:
- Sagemaker
- IAM
- Lambda
- API Gateway
