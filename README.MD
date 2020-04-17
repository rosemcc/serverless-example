# Serverless framework and AWS Lambda

Sample lambda hello function using Serverless Framework

[Serverless Docs](https://serverless.com/framework/docs/providers/aws)

## Setup

Install serverless framework
```
npm install -g serverless
```

Config AWS credentials:
```
serverless config credentials --provider aws --key <your_key> --secret <your_secret>
```

## Usage

Deployment instructions are defined in serverless.yml

[Serverless yaml reference](https://serverless.com/framework/docs/providers/aws/guide/serverless.yml/)

Lambda function is defined in handler.py

Deploy to AWS:
```
serverless deploy
```

Debug locally:
```
serverless invoke local --function hello
```