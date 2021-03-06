## Udagram Infrastructure

![Architecture](architecture.png)

### AWS
#### RDS Postgres
The application server uses AWS RDS Postgres as database for storing and retrieving information.

Database URI: `postgresql://postgres:postgres@database-1.cedkmwy81sxr.us-east-1.rds.amazonaws.com:5432/postgres`

#### Elastic Beanstalk
The application server is deployed on AWS Elastic Beanstalk service. The application is build, archived and uploaded
to and S3 bucket "udagram-api-server" from where Elastic Beanstalk extracts and runs the application on an endpoint.

EB URL: `http://udagram-api-dev.eba-tqnyzmne.us-east-1.elasticbeanstalk.com/`

#### S3 Bucket
The frontend application is deployed using AWS S3 Bucket "udagram-api". The bundled assets are uploaded to an S3 bucket and that
bucket is made publicly readable.

Bucket URL: `http://udagram-api.s3-website-us-east-1.amazonaws.com/home`

End users can access the application from the Bucket URL.
