# MM REST API Micro-Like-Service

### Configuration
Available in the [mm-controller/src/main/resources](mm-controller/src/main/resources) folder 

### Test
`mvn install`

### Build
`mvn package -DskipTests` (and all other usage docs in this `README` apply).

### Run
- Change directory to the [mm-controller](mm-controller) folder
`mvn spring-boot:run`



## How to update?
```
### Work with the AWNICS DEVELOP 

## Clone repo after forking it
git clone https://github.com/rawnics/mm-api

## Pull the upstream repository
git remote add upstream-awn https://github.com/AWNICS/mm-api.git
git pull upstream-awn master

## Start working with the develop branch with a pull-merge
git checkout -b develop
git pull upstream-awn develop

## Commit and push branches to your origin
git add .
git commit -m "Updated the code" --author="Rahul Vishwakarma <rahul@awnics.com>"
git push origin develop
git push origin master

## Create a pull request for AWNICS repo from your forked branch

```
