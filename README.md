## Deploying Movie Review Sentiment App on SageMaker

### Overview

The goal of the project is to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.

General Process

1. Download or otherwise retrieve the data.
2. Process / Prepare the data.
3. Upload the processed data to S3.
4. Train a chosen model.
5. Test the trained model (typically using a batch transform job).
6. Deploy the trained model.
7. Use the deployed model.

### Web App Deployment

![](media/web_app.svg)

### Interface

![](app/app.png)