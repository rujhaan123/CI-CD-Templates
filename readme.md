Application Build/CI Components for dotnet app

- git clone
- restore dependencies
- build app
- run unit tests
- upload package
- scan code
- build DB
- build UI/integration tests
- upload artifacts

Application Release/CD Components for dotnet app

- download artifacts
- create infra  
   scan infra, deploy infra (arm,terraform), scan cloud resources
- deploy apps
   web app, db
- run tests (integration/UI (Selenium)
- deploy to dev/int/prod

