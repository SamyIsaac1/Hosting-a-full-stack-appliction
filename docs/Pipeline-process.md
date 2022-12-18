# Pipeline Process

`Continuous integration(CI)` is a group of many steps in our pipeline. The goal of continuous integration is to verify if code is ready to be merged when a pull request is submitted or to see if code is ready and safe to be deployed. By installing dependencies and testing the code, we are building confidence that our application is ready to be deployed.

`Continuous delivery or continuous deployment` are both steps that we refer to when talking about the D of CI/CD. Both have as a goal to get the application from the build stage and move it to its destination.

- `Continuous Delivery` aims at getting your application delivered to its final step before it is deployed. In this approach, code is manually approved for deployment.

- `Continuous Deployment` is similar to continuous delivery but goes one step further and makes the complete process automatic without human approval.

  ![Pipeline Process](/docs/Digrams/Pipeline.png)

## Pipeline Process

what we have done here is CI/CD Continuous integration/Continuous delivery becuase the code is manually approved for deployment.
All developers push to a repo at each push they trigger Circleci to install,build and deploy the new version of the application.
