# Documentation

## Setup
1. Create local and github git repositories
2. Create static website index.html and buildspec.yml locally
3. Push to github repository
4. Create S3 bucket
5. Create CodeBuild project from GitHub repo to build artifacts to the S3 bucket
6. Create CodePipeline to deploy

## Deploy
1. Execute CodePipeline to create website files in the bucket

## Static Website Hosting
1. Enable static website hosting for the bucket
2. Add bucket policy
3. Website is now accessible

### Notes
Github Repo: https://github.com/LxdRyan/accad4-assessment