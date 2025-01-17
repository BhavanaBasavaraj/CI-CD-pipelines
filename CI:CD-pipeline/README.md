# AWS Continuous Integration Demo

This project demonstrates how to set up a basic CI/CD pipeline using AWS services like CodePipeline and CodeBuild. The goal is to automate the process of integrating and deploying changes for a Python application.  

## Steps to Set Up  

### 1. Set Up AWS CodePipeline  
- Open the **AWS Management Console** and go to **CodePipeline**.  
- Click "Create pipeline" and give it a name.  
- Connect your GitHub account and select your repository and branch.  
- Add a **Build Stage** using **AWS CodeBuild**.  

### 2. Configure AWS CodeBuild  
- Create a new build project in CodeBuild.  
- Select your CodePipeline as the source.  
- Set up the environment, runtime, and build commands (e.g., install dependencies, run tests).  
- Save the configuration.  

### 3. Trigger the Pipeline  
- Make changes to your GitHub repository (e.g., update the code or fix bugs).  
- Push the changes to the branch connected to CodePipeline.  
- Check your pipeline in the AWS Console to see it in action.  

---

This project shows a simple CI/CD workflow using GitHub and AWS. It’s a great way to learn about continuous integration and deployment! 😊  
