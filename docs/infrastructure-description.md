# Infrastructure description of udacity-deploy-fullstack-js-app

## The app uses..

The app uses 3 differents of AWS Services:
  * Amazon Relational Database Services(RDS) for a Postgres database.
  * Elastic Beanstalk(EB) to host the backend API.
  * S3 for static hosting of the frontend files.

## Amazon Relational Database Services(RDS)

The app uses a Postgres database in RDS called `database-udacity-deployment` and its endpoint is database-udacity-deployment.cilyyixqzcsb.us-east-1.rds.amazonaws.com. It is built in us-east-1 region and use 5432 port. Master username for the database is `master` and it is set a password.

Please refer to the picture for RDS:
![alt text](https://github.com/choiyounyeong/udacity-deploy-fullstack-js-app/blob/master/screenshots/RDS.png "RDS")

## Elastic Beanstalk(EB)

The node.js server on EB runs on port 8080. http://udagram-env.eba-vbpvia5q.us-east-1.elasticbeanstalk.com/.

Please refer below for EB:
![alt text](https://github.com/choiyounyeong/udacity-deploy-fullstack-js-app/blob/master/screenshots/EB-env.png "EB")

## S3 for static hosting

The bucket name is `udacity-deployment` and the bucket website endpoint is http://udacity-deployment.s3-website-us-east-1.amazonaws.com/.

Please refer below for S3:
![alt text](https://github.com/choiyounyeong/udacity-deploy-fullstack-js-app/blob/master/screenshots/s3.png "S3")