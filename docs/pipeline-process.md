# Pipeline-process of udacity-deploy-fullstack-js-app

## Overview

The pipeline process in CircleCI is:
![CircleCI pipeline](https://raw.githubusercontent.com/choiyounyeong/udacity-deploy-fullstack-js-app/master/docs/pipeline-process.png)

## Configuration of environment variables

Environment variables are added in CircleCI so that AWS EB CLI can run the code. Such as:
* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY
* AWS_DEFAULT_REGION
* etc.

![CircleCI environment variables](https://raw.githubusercontent.com/choiyounyeong/udacity-deploy-fullstack-js-app/master/docs/ciecleCI-env.png)