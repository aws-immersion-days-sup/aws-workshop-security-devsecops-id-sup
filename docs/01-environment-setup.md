# Module 1: Environment build

If you are doing this workshop at an event, you will be provided with either an AWS account or a hash key for event engine. Please raise your hand and flag down a workshop facilitator for assistance on any issues during the lab.


## Setup the account

Download or Clone: <a href="https://github.com/aws-immersion-days-sup/aws-workshop-security-devsecops-id-sup" target="_blank">https://github.com/aws-immersion-days-sup/aws-workshop-security-devsecops-id-sup</a>

1. Log in with an Adminstrator level account
2. Create an s3 bucket in the eu-west-1 Ireland region.
3. Upload the two zip files to that bucket.
4. Go to Cloudformation and run “pipeline.yml”
5. Change the bucket location to the one you created earlier.  This bucket location is to reference the zip files.
6. Deploy the stack.
7. Continue on to the next build phase.



## Build Phase



1. Browse to the CodePipeline console. You will find a new Pipeline called DevSecOps.
2. Disable the transition between "StaticCodeAnalysis" and "TestDeployment". 
3. Download the code for the workshop here:  https://github.com/aws-immersion-days-sup/aws-workshop-security-devsecops-id-sup/tree/master/code
4. Once in the AWS Console, go to S3 buckets. Look for a bucket: “{CloudformationStackName}-artifactstorebucket-{randomstring}
5. Copy the two zip files into the S3 bucket (remember to copy the zip files, not the unzipped directories)



Your environment is now built with a basic pipeline using s3 as the source repository.

![Pipeline](./images/01-pipeline.png)

After you have successfully setup your environment, you can proceed to the <a href="https://github.com/aws-immersion-days-sup/aws-workshop-security-devsecops-id-sup/blob/master/docs/02-first-pipeline-error.md" target="_blank">next module</a>.
