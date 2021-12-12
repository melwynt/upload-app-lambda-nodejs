## NodeJS Lambda function

This current repo is related to this project:
[github.com/melwynt/upload-app](https://github.com/melwynt/upload-app/)

`Upload App` is a React App to let users upload a file in an S3 bucket.

The `index.js` file is to be added in your NodeJS lambda function.
The goal of this file is to return a presigned URL to the React App with a key.

## Node version

Node version: Node.js 14.x

## Instructions

For a full how-to guide, this [video](https://youtu.be/_khupEk42zs) explains all the steps very well.

You will have to:

- create a lambda function
- create the API Gateway trigger
- create an S3 bucket
- make sure that Cross-origin resource sharing (CORS) is configured properly
- create an environment variable in your lambda function
- give the right permissions to your S3 bucket (cf. this [video](https://youtu.be/mw_-0iCVpUc) for more details)
