# Rest API CI And CD Pipeline Using Postman And Github

## Technology and Tool Used
- Postman
- Visual Studio Code
- CI AND CD
- Github
- Terminal

## Prerequisites

- You must have installed Postman to your system
- Install Postman CLI

## Scenario of this project

- The user can create a user
- The user can create a user by id,name
- The user can get all users
- The user can get individual user by user id
- The user can update a user by user id
- The user can delete a user by user id

## API Documents

 https://documenter.getpostman.com/view/16548351/2sA3BoaXSA 

## How to set up Postman CLI Configuration with GitHub

### Step-1:

- Open the Postman
- Create a workspace
- Create a collection

### Step-2:
- Click the collection
  
  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/5ae3cde3-e3f8-492b-8ad8-58fb800a7fd9)

- then click the collection run button

  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/6ee1dab5-47e6-4fb8-87f5-d314543fa1fc)
- then click the automate run via cli

  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/2197efd6-e3ad-4022-ab71-02a7bb470b7c)
### Step-3

- then install postman cli from here

               https://learning.postman.com/docs/postman-cli/postman-cli-installation/#windows-installation
- open the terminal
- hit the commmand
- after postman cli install then generate a api key
- then login with this command in cmd

              postman login --with-api-key {{xyz}}
  
- after login successfully then hit this command in cmd

             postman collection run {{collection_key}}
  ![image](https://github.com/Mamun104/restapi_automation_run_on_postman_cli/assets/78067017/b05fae3a-3b00-48bb-b75c-4c59ed3de8b1)

### Step-4

- Click the run on ci and cd

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/25582ac2-10a9-485b-a420-d158096a388f)

- then Generate Postman CLI Configuration

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/ee098a91-d6cc-4d72-ba65-bc3c50a64682)

- after that copy postman cli command

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/f9191c0b-3f68-4fb5-8dd4-3ff308744f99)

### Step-5

- create a new repository via github
- then click the github action

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/eb449f88-7fab-47b7-80ce-27e0526ef8da)

- then select the simple workflow

![image](https://github.com/Mamun104/restapi_ci_and_cd_pipeline_using_postman_and_github/assets/78067017/51da6529-8e50-4b1f-ae37-c21fc2fb7846)

- then copy and paste the postman cli command
- after that can commit this file
- then click the github action and run this file

## newman-reporter-html

![image](https://github.com/Mamun104/api-cicd-pipeline-using-postman-and-github/assets/78067017/ddec0095-81c0-4573-96d3-9f4be0fa4c3e)

## newman-allure-reporter

![image](https://github.com/Mamun104/api-cicd-pipeline-using-postman-and-github/assets/78067017/8c6b0dc8-b4d5-4738-a302-0afc116ff888)
![image](https://github.com/Mamun104/api-cicd-pipeline-using-postman-and-github/assets/78067017/f6ef0a8d-ff7a-4dde-a5d3-e2d7a80eca3d)


