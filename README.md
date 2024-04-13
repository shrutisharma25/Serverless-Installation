# Setting Up Serverless Framework with AWS

## Install Node
## Install Serverless:
   - Serverless Docs: https://www.serverless.com/framework/docs/getting-started
   - Command: npm install -g serverless
   - Configure AWS credentials:
     ```bash
     serverless config credentials --provider aws --key YOUR_AWS_ACCESS_KEY --secret YOUR_AWS_SECRET_KEY --profile AccountName
     ```

## Install AWS CLI:
   - Create Access key and Secret key
   - Check if AWS CLI is installed:
     ```bash
     aws --version
     ```

## AWS configure
   - AWS configure
   - AWS Access Key ID [None]: ACCESS_KEY
   - AWS Secret Access Key [None]: SECRET_ACCESS_KEY
   - Default region name [None]: REGION
   - Default output format [None]: json

## Start with Hello World:
   - Command: serverless/sls create --template hello-world
   - Two files will be generated: handler.js and serverless.yml

## Running lambda function locally
  1. Run inbuilt command provided by serverless --> serverless invoke local
      - sls invoke local --function functionName --data {"key":"value"}
  2. Use serverless offline plugin
      - 
