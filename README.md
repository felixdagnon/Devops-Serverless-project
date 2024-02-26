# Devops-Serverless-project

Devops Serverless project

# 1-CI/CD flow for lambda using CodeCommit, CodeBuild, Cloud9

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/59fa01b6-afb1-4517-b37e-36faa7fc8029)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/c124840b-b3ef-4d0d-9522-28a2f47b9f88)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/38ce1341-925c-4b41-ab3a-8481927d0b8f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/e5675810-fcb5-4812-afa3-0c73a81ffa34)

## AWS CodeCommit

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/45366fe9-63a3-4d74-91e9-a814e337284e)

Create user groups: 

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/1f46161f-9777-4065-ac24-547aa7f1e89c)

Example Developer Tina: HTTPS Git credentials for AWS CodeCommit. 

Copy and paste credentials in notepad and use it to log in mananagement console

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/68de2408-0091-4a14-9982-74f58b77ed46)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/e6db4e59-fb7c-4747-81f5-5874bbbc8083)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/c2b0683f-1f69-4ec3-8cf4-1e66f43aadba)

Create CodeCommit repository in the console with the credentials

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/c2a75516-ab6d-4878-a09d-1018b77d8b9c)

Example: create text file in the repo and commit change

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/145c08b8-2320-479e-8e3e-c6abffbffea5)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/9786e826-d4dd-4fb9-aef0-2377e0664022)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/1da052b6-925f-4349-9162-42fac68c57f9)

https link: https://git-codecommit.us-east-1.amazonaws.com/v1/repos/HelloWord

## Clone this repo in Cloud9 with command: git clone

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/474ff0ce-7406-462d-a84c-374992e7810f)

## Create HelloWord folder and put in Python file HelloWord.py for example

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/8da5c1af-6c38-4919-899f-5316c83ac353)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/2cff3f64-b580-4e7a-a529-063f6bdbfaa9)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/b8642758-482b-4dfc-9d3f-8e28d7286c62)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/1991fa26-e6c8-476e-a6b6-ac4ef952aebe)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/02f50666-655b-466f-8415-e3c844a74a94)


## Push git code from Cloud9IDE to CodeCommit repo 

Execute those command in bash

$ cd HelloWord

$ git add HelloWord.py

$ git commit -m "Add a customery hello word program"

$ git push -u origin main

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/cd3d925c-fb88-458b-85bf-d8079f72f8dd)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/f50999b3-58e0-4615-8596-3d34d9087ec1)

## Consult CodeCommit console to see the program in the repo

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/c44ae9eb-a33b-4eda-8a59-682f4b65fc7f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/c8c16f7b-6e86-42d7-a585-a1b5c22c5e8a)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/313f6de1-8e4c-4674-af76-82b7d7f40abf)

# 2-AWS CodeCommit Notification and Trigger in the repository

## AWS CodeCommit Notification SNS by email

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/506bc1c9-d60c-4532-bfa0-2ecd11617c57)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/0bfa607d-e479-4733-a978-882d4d0d316f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/0bec096e-8491-439d-9cd1-b92f5a1f2ad6)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/6193983e-efbf-4a64-b01a-3b79e4595a03)

## AWS CodeCommit Notification by Trigger SNS or lambda

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/03f7d89f-e7a2-4912-9a16-940650fac5cd)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/b7e8a194-7b46-48cd-871a-46b9c71a8a62)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/d62e8ac1-7e4e-4e53-b332-46c863ff12ab)

# 2-AWS CodeCommit Branch and pull requests

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/bf941818-f359-42d0-864d-eb4d0edf1a9f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/574534a1-32c7-4ebe-a37d-2327f492edbe)

## Demo

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/623a1716-9c3b-4b4e-8395-6d131f9d7092)

## Code review: create a Branch and Pull Request to request this change to be merge to the Master or Main

$ git commit -a -m "Changed print statement"

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/08e26ee4-e7c1-4bdf-89f5-a26feb13d521)

## Create Branch

$ git checkout -b Changedprint

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/91532a42-b194-424b-8238-c4f8a5174112)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/4dccd286-35cc-44ee-8488-68ed6f951cef)

## Pull request in Bob repository

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/5ec6dc23-3fbd-4d4a-acaa-fc60af970d28)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/adb9e197-e6a0-4b61-b01c-c123b2c63480)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/58f9c727-c6df-424f-a716-5ff9f4f4ab41)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/e375ea34-bcd8-43d7-9488-9f5f880f4809)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/42a1f495-5f28-402b-9872-e5f09b08ee45)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/a5bda4c8-3ff5-4db1-bea5-b4170f377876)

## Tina reviews and merge to the Master(main)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/70fb7541-6d87-4ee3-a48e-88ee4bafb257)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/78e5b150-d933-4eb2-a0bc-38fe980f71e7)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/5c9e23d4-6dc1-4a2b-aa0c-a4b488c84b2e)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/5a6d296c-a5c4-4acd-97eb-20d67b6ff3e3)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/5ac222e6-1d1c-488c-a672-e94919371b41)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/bb819a89-a032-4a8a-9ae8-d4f952a8bb22)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/897e1812-f11a-4064-9e42-01aee91d974b)

## Check change merge in the Master (Main)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/dca4ce21-61ee-4cdf-8087-c7c6d229e0d4)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/d919c9d7-363a-4310-bb85-325e6d138ade)

# CodeBuild 

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/e64a96be-49c7-4f5d-a144-ad5d1b793712)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/527cac8f-092a-4a7a-aae5-9577c1e77aa9)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/03d49cf7-8c15-4475-8d3c-8fd3eb38eba8)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/ae833518-3440-4cb8-83e6-bdb1efe49312)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/2e4ef050-f391-4b7d-88a8-517dba50930c)

### For use case, we can use lambda (or jenkins or CodeDeploy) to deploy CI/CD flow for lambda application 

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/6ef5bea4-f17e-4cd4-8009-d8eaeace8c8b)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/06b69dc4-705d-4f7a-9d1b-74eebfecb72e)

### AWS CodeBuild BuildSpec file

In this step, you create a build specification (build spec) file. A buildspec is a collection of build commands and related settings,
in YAML format, that CodeBuild uses to run a build. Without a build spec, CodeBuild cannot successfully convert your build input 
into build output or locate the build output artifact in the build environment to upload to your output bucket.

Create this file, name it buildspec.yml, and then save it in the root (top level) directory.

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/1787bf22-7e88-4e20-8faa-780665659a53)


### Artifacts

artifacts represents the set of build output artifacts that CodeBuild uploads to the output bucket. files represents
the files to include in the build output. CodeBuild uploads the single messageUtil-1.0.jar file found in the target 
relative directory in the build environment. The file name messageUtil-1.0.jar and the directory name target are based
on the way Apache Maven creates and stores build output artifacts for this example only. In your own builds, these file 
names and directories are different.

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/62299da3-467d-48eb-93ed-816177e473f3)


## Use case: AWs CodeBuild for CI/CD flow lambda application deploy with lambda

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/66e66ff8-26f0-49d2-8cb8-b2417a4a9c2b)


### Create github repository and clone it in Cloud9

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/b9a221b7-57e3-452e-900f-437a7a6b7cd4)

###  Execute those command in cloud9

To clone Git Repo: 

$ git clone https://github.com/felixdagnon/codebuild-demo.git

Create files buildspec.yml and lambda_function.py in codebuild-demo repository :

$ cd codebuild-demo
$ touch buildspec.yml
$ touch lambda_function.py

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/cd0c5ab7-db51-47c4-8452-c9b8e18fb0f1)

### Copy and paste code in the files

- lambda_function.py

    ```py
   import json
   import boto3
   import requests
   def lambda_handler(event, context):

    # TODO implement
    
    # api-endpoint
    print(event)
    URL = "http://maps.googleapis.com/maps/api/geocode/json"
    location = event['landmark']
    
    # defining a params dict for the parameters to be sent to the API
    PARAMS = {'address':location}
 
    # sending get request and saving the response as response object
    r = requests.get(url = URL, params = PARAMS)
 
    # extracting data in json format
    data = r.json()
 
 
    # extracting latitude, longitude and formatted address 
    # of the first matching location
    latitude = data['results'][0]['geometry']['location']['lat']
    longitude = data['results'][0]['geometry']['location']['lng']
    formatted_address = data['results'][0]['formatted_address']
 
    # printing the output
    print("Latitude:%s\nLongitude:%s\nFormatted Address:%s"
      %(latitude, longitude,formatted_address))
    output={"address":formatted_address} 
    return output
    #return('Hello from %s'%formatted_address)
    ```

    ![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/3a58f143-9143-4e86-baf5-d6bef8a07dd0)



-  buildspec.yml

  ```yml
 version: 0.2
phases:
  install:
    runtime-versions:
      python: 3.7
  build:
    commands:
      - echo Build started on `date`
      - echo Compiling the Python code...
      - pip install requests -t .
  post_build:
    commands:
      - echo Build completed on `date`
      - pwd
      - ls -al
artifacts:
  files:
    - '**/*'
```

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/ab1b7dd5-0925-4934-a100-9e49a80a0475)

## Create the project in aws CodeBuild

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/e0cb4e9a-e9a9-4c38-9a00-d2d867826a81)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/7d198180-9015-4ecd-8046-70ed6a1a6e5e)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/a55aa0d8-4fe4-405f-bda8-15185b2c4064)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/fe4529c2-d122-4e0f-aa23-1e8e0948a24b)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/3d70f4b5-f44b-4fdb-acf4-9e6c8be5240f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/5f5f88c1-d99d-4f92-b85a-0a868216c877)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/aca4a2ee-1eb4-454a-996d-5f0d0a9592fd)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/0140e483-d045-40f1-b8ce-469121f5f1ab)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/3c1b333d-885c-4468-8460-f01cb7e0d51a)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/c030af96-eae1-40b7-ad24-43d2d9c4f013)


## Push code lambda_function.py and Buildspec.yml from Cloud9 main repo to Girhub repository

$ git add .

$ git commit -m "added code and buildspec"

$ git push origin main

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/d6b48dc6-0c54-4399-b247-5801e888985c)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/883fd201-cc43-4117-843a-c169c5461116)

## Check AWS Codebuild console: code is running

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/f8ef7c26-b9c7-41c6-bd17-c833ea6c60bf)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/41f13f59-edad-4c2c-b101-3cad489fca55)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/4c0a12bd-202a-4958-8c80-4a3fd4d96482)


## Check bucket for the zip file deloyed in s3 bucket

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/1782a5f9-a7a8-4893-bf48-9f2202a6a63e)

## Change python version to take the version from AWS codebuild environnement if issue

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/115f5225-4884-462e-ac14-fbe598b30a01)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/3510e571-539d-46b1-94a9-6fed8cf47db2)




# Code deploy for lambda



![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/a61a9c98-d629-4346-b627-3a410658f85a)


![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/ab7998b1-4474-4925-b6d9-38542e289756)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/1fc79811-35dc-413c-9e14-e52b9c77bdd1)

### Create DeployementGroup: how to route trafic to a new version of lambda and also rollback

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/2459f83a-5008-4d0d-b9fe-b4a63397ae8f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/9364f57f-f7d2-41b4-bbb7-fa71fba1fb66)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/4fcc8a57-e549-43ca-b2f9-9f603cb1c5fc)

### Create a deployement group with AppSpec editor

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/cb14a855-d3cd-46ed-b305-83b27a7aca3d)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/ae4cbb1f-7237-4c32-9ef6-074fdb922c89)


### Deployement OK

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/10d9f023-4070-486b-988d-54718da1ce8d)

### Alias ponting to version 5

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/6d778a76-1ae1-47cc-bf9b-d511d328a68f)

![image](https://github.com/felixdagnon/Devops-Serverless-project/assets/91665833/16b84203-d678-4ef9-a675-ecb886a22884)




































































































































