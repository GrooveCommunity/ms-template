
![badgen](https://badgen.net/badge/built%20with/love/red)
![Node](https://img.shields.io/badge/-Node.js-5B9856?style=flat&logoColor=fff&logo=node.js)
![badgen](https://badgen.net/badge/built%20with/typescript/blue)
[![serverless](https://camo.githubusercontent.com/547c6da94c16fedb1aa60c9efda858282e22834f/687474703a2f2f7075626c69632e7365727665726c6573732e636f6d2f6261646765732f76332e737667)](http://www.serverless.com)
[![Code Style](https://badgen.net/badge/code%20style/airbnb/ff5a5f?icon=airbnb)](https://github.com/airbnb/javascript)

# Serverless MicroService template

This project contains a minimal infrastructure to initialize a serverless application to make a great and simple Backend.

The template uses the [serverless framework](http://www.serverless.com) to make all the api gateway, cloudformation, lambda provisioning and etc.

| Dependencies                                 | Description               |  
| -------------------------------------------- | ------------------------- |  
| [node-version >= 14](https://nodejs.org/en/) | Javascript Runtime        | 
| [Serverless Framework](http://www.serverless.com) | You should install globally| 
| [AWS Credentials](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html) | AWS Credential installed| 


## <a name="project-setup"></a> 🔨 Project setup

1. To **clone repository** you need to have [git](https://git-scm.com/downloads) installed:

```bash
git clone git@github.com:GrooveCommunity/ms-template.git
```

2. Enter repository ms-template

```bash
cd ms-template
```

3. To **install dependencies** you need to have [NodeJS](https://nodejs.org/en/) and yarn installed:

```bash
yarn 
```

## <a name="deploying-locally"></a> ⬆️ Deploying to AWS

This step will deploy your local code to AWS.

> :warning: Attention: To run the deploy you need to have performed the above steps.

1. You just need to (it depends on of which environment you want to deploy )

```bash
yarn deploy:dev 
```
or
```bash
yarn deploy:prod 
```

## <a name="running-locally"></a> ▶️ Running locally

To run this microservice and dependencies locally you need to have installed all the dependencies.

1. To run locally, you basically need to run:

```bash
yarn start:local
```

To learn more 💪 [Serverless Framework](https://serverless.com/framework/docs).


### To-dos

- [x] General folder structure
- [x] Test on AWS  
- [x] Linters
- [ ] Get Envs from Secrets Manager
- [ ] Conventional commits
- [ ] Commitizen
- [ ] JWT checker (auth service)  
- [ ] Generic test structure
- [ ] Build pipeline (CI)
    - [ ] Pipeline executor
    - [ ] Linters
    - [ ] Dependabot / Renovate / or at least `yarn audit`
    - [ ] Tests
    - [ ] Husky / Commitizen
    - [ ] Conventional CHANGELOG generator
        - [ ] Conventional commits required
- [x] HTTP handler
    - [x] CORS
    - [?] Logger / or at least build in `winston`
- [ ] Deployment pipeline (CD)
    - [ ] GH pages for test coverage




 
