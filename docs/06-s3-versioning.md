<!--
Testing the lambda function created in the previous module.
--> 
# Module 6:  Configuring S3 Security

Many organizations utilize s3 extensively.  It is important that the s3 buckets are configured to the organization's requirements to ensure data stored safely.


1.	Now that you have added a lambda function to enforce enablement of S3 Versioning Configuration.  Release the change to start the pipeline.


2.	Add the appropriate configuration.
    1.	Edit resource.json and add the appropriate lines.
    2.	Rezip the “codepipe-AWS-devsecops.zip” (the exact name is important)
    3.	Upload the zip to s3.
3.	Come back to the DevSecOps pipeline and watch it through the stages again.


!!! info Hint: <a href="https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-s3-bucket.html" target="_blank">https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-s3-bucket.html</a>

## Finished!

Congratulations on completing this workshop! This is the workshop's permanent home, so feel free to revisit as often as you'd like.



##  Continuing On

The workshop is intended to give you an idea of how to start your own Security

