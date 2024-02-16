# TerraformS3StaticWebHosting
this is terraform project which create the s3 bucket in aws console and and create the static website.

The purpose of the project to create a static website which include a portfoilo website (index.html) and error.html which appear whenever index.html not up and running.

step1) install and setup the vscode.
step2) install and setup the terraform.
step3) configure the terraform with aws-cli.
step4) write a terraform configuration script file to create s3 bucket and make the bucket publicly avaialble and also enable static webhosting
step5) use the command one by one to get desired output terraform init--->terraform plan ---> terraform apply.
stept6) go to s3 console get DNS or just check terraform output to get the s3 bucket url where the website is uploaded in the object. 
step7) and finally paste the url in your favorite browser to see the website.
