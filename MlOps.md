## MlOps CI/CD
CI

- specify agent
- use python version
- installing requirements (cli package, requirements.txt file)
- data test (unit testing for model code using pytest)
- az cli task for ml extension
- install azure ml cli (to check whether resource exist)
- azure cli task to create ml compute cluster
- azure cli task to upload data to datastore
- bash task for creating folders (mkdir metadata and models)
- azure cli task for training model
- az cli task for register model
- az cli task for download model
- copy files and then publish pipeline artifact

CD part to Deploy to STG first
- Specify agents and then python version
- az cli task for ml extension
- az cli task to deploy to aci (az ml model)
- bash task for installing requirements
- az cli task for stg unit test
- publish results
