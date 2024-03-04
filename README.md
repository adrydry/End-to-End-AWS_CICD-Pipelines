# End-to-End-AWS_CICD-Pipelines

In this Project, our goal is to create an End to End deployment of a student managment system ON AWS with native tools. During this project, we will use many tools like Aws Cloudformation, Code Commit, Code Build, Code Pipeline, Code Deploy, ECR and ECS

## 1- Create our User and Give permission
Before creating our code commit repository, it is important to create our user and give him the right permission to push the code to Code Commit. Let's go to IAM, create the user and on Security Credentials, generate credentials for **https git Credentials for AWS Commit**

![2](https://github.com/adrydry/End-to-End-AWS_CICD-Pipelines/assets/102819001/cca1b465-cb67-4145-9f1d-717301e359f0)

## 2- Create our Code Commit repositoty
![1](https://github.com/adrydry/End-to-End-AWS_CICD-Pipelines/assets/102819001/89f92165-8595-4919-ad6f-452b6db3700e)


## 3- Clone the repository
To be able to store application in this repository, we need to clone this code commit repository on our local system.Copy the code on VSC
![1](https://github.com/adrydry/End-to-End-AWS_CICD-Pipelines/assets/102819001/babbda6f-b9f2-4b32-939f-ea0f7870308b)

 Enter the user credential
 
![Screenshot 2024-03-03 182733](https://github.com/adrydry/End-to-End-AWS_CICD-Pipelines/assets/102819001/23e5aa4d-c966-4545-a3aa-7de3de3d9404)

Our code commit is successfully cloned

![4](https://github.com/adrydry/End-to-End-AWS_CICD-Pipelines/assets/102819001/f2147688-e24b-4312-b31e-b3e1ad015d10)

## 4- Push our application code in the repository

Go to our local repository, copy all the file and paste in the code commit repository cloned before
