# AWSTranslation-using-API-Gateway-and-Lambda-Functions

The user sends the text as a payload to the API by making a POST request. Upon this request, the API directs to a lambda function. The lambda function communicates to translate the text using Amazon Translate and sends back the response.

## Amazon Translate

Amazon Translate is a neural machine translation service that offers fast, high-quality, cost-effective, and customizable language translation. Utilizing deep learning models, it provides more accurate and natural translation compared to traditional statistical and rule-based translation algorithms.

Amazon Translate enables you to adapt content like websites and applications for international users and efficiently translate large texts.

## Purpose

The purpose of this effort is to perform text translation using the AWS Lambda service and return the translated text as an API response. This project is specifically designed to operate within a Lambda function and provide text translation service by connecting this function with a suitable trigger (API Gateway).

## Code

The provided code is the Lambda function code required to accomplish all of these. It's designed to work with Python 3.9 and above.
