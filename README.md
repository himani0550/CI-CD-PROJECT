# GitHub Actions CI/CD Pipeline Flask App
Implement a CI/CD workflow using GitHub Actions for a Python application.
## Requirements :
### SETUP : 
1. Create a public repository on github with the python application.
2. Utilize Github Actions in the provided python application respository, defining steps for dependencies installation, testing, build and deployment.
### Github Actions Workflow :
1. Create a .github/workflows directory in your repository.
2. Inside the directory, create a YAML file to define the workflow.
### Workflow Steps :
1. Install Dependencies: Install all necessary dependencies for the Python application using pip.
2. Run Tests: Execute the test suite using a framework like pytest.
3. Build: If tests pass, prepare the application for deployment.
4. Deploy to Staging: Deploy the application to a staging environment when changes are pushed to the staging branch.
5. Deploy to Production: Deploy the application to production when a release is tagged.
### Environment Secrets :
- Use GitHub Secrets to safeguard sensitive deployment information.
