Current project automated pipeline for building, testing, and deployment. 

Procedure followed for implementation of this project:

Step1. Develop model local 

Step2. Write unite test: to validate the functionality.

Step3. Dockerize App: docker image for containerized deployment.

Step4. Push to Github: Push the code and Docker configuration to a GitHub repository. 

Step5. Github Actions CI/CD: Trigger the CI/CD workflow with GitHub Actions.

Step6. Build & test docker image: Run tests in the Dockerized environment to ensure compatibility.

Step7. Monitor model performance: Monitor the model's performance post-deployment. 

Step8. Check R2 Score: Evaluate the R² score to detect degradation.

Step9. Trigger Retraining: If performance declines, retraining was initiated. 

Step10. Deploy Updated model: Deploy the updated model automatically if retrained successfully.
