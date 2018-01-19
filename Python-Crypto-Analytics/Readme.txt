-cryptolisttodynamodb.py
In order to use this script you will need an AWS account and an IAM role configured for R/W access to DynamoDB. log into the IAM role through AWSCLI in command prompt and run the script. The script will not run twice if DB already was created. Alternativly it can be run from a properly configured EC2 instance set up with DynamoDB R/W privlages.
