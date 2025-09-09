# Deploy Web Application from GitHub to AWS Elastic Beanstalk using CodePipeline

This repository demonstrates how to set up an automated deployment pipeline where a web application is deployed from **GitHub** to **AWS Elastic Beanstalk** using **AWS CodePipeline**.

## 📌 Overview

The deployment flow:
1. **Source**: Code is pushed to GitHub.
2. **Pipeline**: AWS CodePipeline detects changes.
3. **Deploy**: The application is deployed to Elastic Beanstalk automatically.

📖 Description

This project demonstrates how to set up a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a PHP-based web application.
The pipeline integrates GitHub as the source code repository, AWS CodePipeline for automation, and AWS Elastic Beanstalk as the deployment environment.

The setup ensures that whenever new code is pushed to GitHub, it is automatically built (if required) and deployed to Elastic Beanstalk with zero manual intervention.


📌 Architecture Flow :-
==========
1.	Developer pushes code → PHP code is committed and pushed to GitHub.
2.	Source stage (GitHub) → CodePipeline detects the change.
3.	Pipeline automation (CodePipeline) → Fetches the updated code and passes it through optional build/test steps.
4.	Deployment stage (Elastic Beanstalk) → CodePipeline deploys the new version of the application to the Elastic Beanstalk environment.
5.	Application Live → End users access the updated PHP application via the provided EB URL (or custom domain).
	![image_alt](https://github.com/meghapawar177-droid/-Deploy-Web-Application-from-GitHub-to-AWS-Elastic-Beanstalk-using-CodePipeline/blob/1d7524fa78dfe17baba81f842bfc2141a35e899f/new/eb.png)




📊 Benefits
=

✅ Saves time with continuous deployment.

✅ Reduces errors by avoiding manual deployments.

✅ Ensures code changes are live within minutes.

✅ Provides scalability and monitoring out of the box.





