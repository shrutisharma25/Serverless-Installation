1. Install Node
2. Install Serverless:
   - Serverless Docs: https://www.serverless.com/framework/docs/getting-started
   - Command: npm install -g serverless
   - Configure AWS credentials:
     ```bash
     serverless config credentials --provider aws --key YOUR_AWS_ACCESS_KEY --secret YOUR_AWS_SECRET_KEY --profile AccountName
     ```

3. Install AWS CLI:
   - Create Access key and Secret key
   - Check if AWS CLI is installed:
     ```bash
     aws --version
     ```

4. AWS configure

5. Start with Hello World:
   - Command: serverless/sls create --template hello-world
   - Two files will be generated: handler.js and serverless.yml

