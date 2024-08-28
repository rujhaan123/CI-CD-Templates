## Dot Net CI/CD
CI
- git clone
- restore dependencies
- build app
- run unit tests
- upload package
- scan code
- build DB
- build UI/integration tests
- upload artifacts
  
CD
- download artifacts
- create infra  
   scan infra, deploy infra (arm,terraform), scan cloud resources
- deploy apps  
   web app, db
- run tests (integration/UI (Selenium)
- deploy to dev/int/prod

## Container CI/CD
CI
- docker build
- docker tag
- docker login ACR
- docker push
- scan image
- scan Dockerfile, manifests, helm
- run unit tests

Release

- az login (SPN)
- az aks get credential
- kubectl apply -f yaml/ heml apply
- scan cluster config
- -secrets in keyvault
- run integration tests

## MlOps CI/CD
CI
- specify agent
- use python version
- installing requirements (cli package, requirements.txt file)
- data test (unit testing for model code using pytest)
- install azure ml cli (to check whether resource exist)
- azure cli task to create ml compute cluster
- azure cli task to upload data to datastore
  

