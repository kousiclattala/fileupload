# fileupload
Project for uploading files to local DB and also remote DB

In this project i developed a simple backend server using Nodejs, Expressjs, Mongoose for accepting the files from the user and storing them in the DB via various ways 
like storing locally, uploading to remote DBs like cloudinary, AWS S3 bucket.

For frontend part i use React, in that i just created a simple form with few fields firstname, lastname, file.

## To run this project

- clone it into your machine.
- navigate to `/backend`, `/frontend` folders and run `npm install`. It will install the necessary dependencies for this project.
- Create a account in [Cloudinary](https://cloudinary.com/) and copy the `cloud_name`, `api_key`, `api_secret`. paste these fields in the `cloudinary.config({})` 
  method in `index.js` file.
- Ceate a account in [AWS Console](https://signin.aws.amazon.com/signin) and follow the steps mentioned here [AWS-NodeJS-S3](https://stackabuse.com/uploading-files-to-aws-s3-with-node-js/) 
- Change the fileds in the `accesskeyId`, `secretAccessKey` with your AWS keys.

- after making the required changes, navigate to `/backend` folder and run this command `npm run dev`.
- next navigate to `/frontend` folder and run this command `npm start`.
