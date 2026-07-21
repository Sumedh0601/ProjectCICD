End-to-End CI/CD Pipeline Automation Using Jenkins, Docker & AWS EC2
Project Overview

Designed and implemented a complete End-to-End CI/CD pipeline that automates the software delivery lifecycle. The pipeline integrates GitHub, Jenkins, Docker, and AWS EC2 to automatically clone the source code, build a Docker image, push it to Docker Hub, deploy the application, and send email notifications using SMTP.

Technologies Used
Jenkins
Docker
Docker Hub
Git & GitHub
AWS EC2 (Ubuntu)
SMTP Email Notifications
Linux
Shell Scripting
Jenkins Pipeline (Declarative)
Project Workflow
Developer pushes the latest code to GitHub.
Jenkins Pipeline automatically triggers the build.
Jenkins clones the repository from GitHub.
The application is built successfully.
A Docker image is created using the project's Dockerfile.
Jenkins authenticates with Docker Hub.
The Docker image is pushed to Docker Hub.
The application is deployed as a Docker container on the EC2 instance.
Jenkins sends success or failure notifications through SMTP email.
Key Features
Automated source code checkout from GitHub.
Automated Docker image creation.
Secure Docker Hub authentication using Jenkins Credentials.
Automatic image push to Docker Hub.
Containerized application deployment.
SMTP email notifications for build success and failure.
CI/CD pipeline built using Jenkins Declarative Pipeline.
Hosted on AWS EC2 running Ubuntu Linux.
Challenges Solved
Configured Jenkins permissions to access the Docker daemon.
Resolved Docker socket permission issues.
Managed Docker Hub authentication using credentials.
Fixed container port conflicts during deployment.
Automated container deployment within the Jenkins pipeline.
Integrated SMTP for real-time build notifications.
Outcomes
Reduced manual deployment effort through automation.
Improved deployment consistency and reliability.
Achieved faster release cycles with a fully automated CI/CD pipeline.
Implemented secure credential management using Jenkins Credentials.
Enabled continuous integration and continuous deployment with minimal manual intervention.
Resume Version (ATS-Friendly)

End-to-End CI/CD Pipeline Using Jenkins, Docker & AWS EC2

Developed an automated CI/CD pipeline using Jenkins Declarative Pipeline.
Integrated GitHub for automatic source code checkout.
Built Docker images and pushed them securely to Docker Hub.
Deployed containerized applications on AWS EC2 using Docker.
Configured Jenkins Credentials for secure Docker Hub authentication.
Implemented SMTP email notifications for build success and failure alerts.
Automated the complete build, test, image creation, and deployment process.
Troubleshot Docker permission issues, authentication errors, and deployment conflicts.
Technologies: Jenkins, Docker, Docker Hub, GitHub, AWS EC2, Linux, Shell Scripting, SMTP.
