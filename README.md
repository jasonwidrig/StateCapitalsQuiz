# StateCapitalsQuiz

The lambda for this skill uses this Layer: 	arn:aws:lambda:us-west-2:173334852312:layer:ask-sdk-for-nodejs:4

The lambda for this skill uses a custom role which consists of 2 AWS managed policies: AmazonS3FullAccess and AWSLambdaBasicExeuctionRole

The JS files come from the actual lambda

The other project files came from an ask clone of the skill on Sep 8 2020

The CORS config is for the S3 bucket set up for media files. 

Setting the default encryption for S3 to AES-256 seems to work best for the persistence adapter.
