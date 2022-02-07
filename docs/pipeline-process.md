# Pipeline-process of udacity-deploy-fullstack-js-app

## Overview

The pipeline process in CircleCI is:
[alt text](https://github.com/choiyounyeong/udacity-deploy-fullstack-js-app/blob/master/docs/pipeline-process.pdf  "CircleCI pipeline")

## Configuration of environment variables

Environment variables are added in CircleCI so that AWS EB CLI can run the code. Such as:
* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY
* AWS_DEFAULT_REGION
* etc.

[alt text](https://github.com/choiyounyeong/udacity-deploy-fullstack-js-app/blob/master/docs/ciecleCI-env.png "CircleCI environment variables")