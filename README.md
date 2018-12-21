# Welcome to my sample for hosting static website with AWS DevOps tools 
This sample code helps get you started with a simple static HTML website
deployed by using AWS CodeCommit, AWS CodeBuild, AWS CodePipeline, AWS CloudFormation AWS CodeDeploy to an Amazon EC2 instance.

What's Here
-----------

This sample includes:

* README.md - this file
* buildspec.yml - this file is used by AWS CodeBuild when building the artifact.
* appspec.yml - this file is used by AWS CodeDeploy when deploying the website
  to EC2
* scripts/ - this directory contains scripts used by AWS CodeDeploy when
  installing and deploying your website on the Amazon EC2 instance
* webpage/ - this directory contains static web assets used by your website
  * index.html - this file contains the sample website

