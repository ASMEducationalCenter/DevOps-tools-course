# DevOps-tools-course
Intro to DevOps on AWS with various tools and services


## Devops tools we will cover
- Infrastructure as code:Cloudformation ( Day 1) 
- Infrastructure as code: Terraform ( Day 1) 
- SCM: Git and Github
- API Automation: AWS Command Line Interface, boto3 AWS SDK ( Day 1) 
- Configuration Management: Ansible ( Day 2) 
- Continuous Integration: Jenkins ( Day 2) 
- ChatOps: Slack ( Day 3) 
- Alerting :  SNS (Day 2 and 3) 
- Monitoring and Logging: Cloudwatch Metrics + Logs ( Day 3) 
- Serverless Automation: AWS Lambda ( Day 3) 
- Containers: Docker ( Day 3) 




# Day 1 
- Intro to DevOps 
  - #### Waterfall, Agile, DevOps
     - https://www.guru99.com/waterfall-vs-agile.html
     - https://www.guru99.com/agile-vs-devops.html
    
  - ### What is DevOps
    https://aws.amazon.com/devops/what-is-devops/

  - ### DevOps Culture
    https://www.ca.com/en/blog-automation/what-is-devops-culture.html
    https://martinfowler.com/bliki/DevOpsCulture.html
- Intro to DevOps ToolChain
  - https://dzone.com/articles/the-ultimate-devops-tools-ecosystem-tutorial-part-2

- AWS Refrehsher 
  
- Setup Slack
- Intro to Git 
  - https://git-scm.com/book/en/v1/Getting-Started-Git-Basics
  - http://rogerdudler.github.io/git-guide/
  - https://www.atlassian.com/git/tutorials
  

 


# Day 2 Tentative


- Cloudformation
  - Create a simple stack with cloudformation ( with AWS Management console)
  - Create a simple stack with the AWS CLI 
  - [Lab](https://github.com/ravsau/cloudformation-course/tree/master/lesson2-create-an-ec2)
  
- Terraform 
  - create a simple EC2 windows and linux instance with terraform 
  - create a VPC with terraform 
  - [Lab](https://github.com/ravsau/aws-labs/blob/master/terraform-aws/lesson1-ec2-with-terraform.MD)
  
- AWS CLI 
  - S3 
  - copy to s3 
  - cloudformation
  - EC2 describe 
  
- Intro to Ansible 
  - https://www.ansible.com/
  - https://www.amazon.com/gp/product/098639341X/ref=dbs_a_def_rwt_bibl_vppi_i0

  - https://github.com/geerlingguy/ansible-for-devops
  
  - Setup Ansible 
    -  https://github.com/ravsau/ansible-practice
  

     


# Day 3 Tentative



-  CI/CD with Jenkins 
  - Install jenkins
  - Retrieve password and do initial Jenkins setup
  - Install Jenkins plugin
    - http://localhost:8080/pluginManager/available
    
  
  - create a simple project 
     - poll from SCM ( github)
     - Build 
     - Copy Artifact to S3
     - Deploy artifact with Ansible 
- Immutable infrastructure with Golden Image / AMI 
- Review Autoscaling and Load Balancing 
   - HTTP Flood to autoscale
- ( Lecture + Demo) Logging , Monitoring , Alerting 



- Containerization with Docker Demo 
  - create Docker Image
  - Deploy containers
  - Pull from Dockerhub
  - Push to Dockerhub
  
 - Refresh all the concepts covered

     
## Links
 ### AWS Meetup
   - https://www.meetup.com/Bethesda-Cloud-Computing-Meetup/

## References




