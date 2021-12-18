# Author:
- Nguyen Hoang Hiep
- Gmail: hoanghiepuit97@gmail.com

# Description
This repo is demo project to learn Serverless Framework

# Technology Stacks
- AWS
    - API Gateway
    - Lambda Function or AppSync for backend
    - AWS Neptune
    - AWS Cloudwatch
    - AWS X-Ray
    - More backend integrations Graphcool Prisma, Durid, MongoDB
- GraphQL
- Serverless Application for manage deploy
- Apollo Engine for monitoring and debugging

# Explaination
- handler.js: lambda function handler to route HTTP requests and return the response.
- serverless.yml: creates AWS resources and sets up the GraphQL endpoint.
- schema.js: defines our GraphQL schema we're using to build this mini Twitter app.
- resolver.js: defines query handler functions to fetch data from our other services (RDS, REST, DynamoDB, etc.)

## Step 1: Configure the Serverless template

