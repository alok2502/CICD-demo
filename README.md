### ✅ Key Concepts:
- CI: CodeBuild for building Docker-based Flask app.
- CD: CodeDeploy to deploy the app on EC2.
- Source Code: GitHub (fallback for CodeCommit)

### 🛠️ What Was Done:
- Created a simple "Hello World" Flask app.
- Created a CodeBuild project to install dependencies and build the app.
- Stored DockerHub credentials in AWS Parameter Store.
- Built and pushed the image to DockerHub.
- Deployed app to EC2 using CodeDeploy with appropriate IAM roles and tags.
- Integrated CodePipeline to orchestrate the CI/CD workflow.
- Verified end-to-end deployment by pushing changes to GitHub and observing the pipeline.
