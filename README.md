# File uploading to AWS S3 buckets from a [Next.js](https://nextjs.org/) project.

This repo shows file upload, list, display and delete of private files in S3, from Next.js.  


## Setup

You'll need an S3 bucket and AWS credentials to run the
app.

## Set up env
Create a .env.local file in the parent directory.

Replace with your aws region, bucket name and keys
```
S3_BUCKET_REGION=eu-north-1
S3_BUCKET_NAME=my.bucket.name
SECRET_AWS_ACCESS_KEY_ID=AKIAMyAWSAccessId......
SECRET_AWS_SECRET_ACCESS_KEY=XMyAWSSecret.......
```

### Install and run

```bash
yarn
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Add S3 bucket and IAM user

You'll need an S3 bucket and AWS credentials to run the
app.

#### Manually

- Navigate to [AWS console](https://s3.console.aws.amazon.com/) and create a regular S3 bucket.
- Preferably, create a new IAM user and download its keys.

