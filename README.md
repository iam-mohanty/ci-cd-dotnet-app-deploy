# .NET Application Deployment with Jenkins CI/CD 🚀

## Project Overview 🎉
Deploying a .NET application with a Jenkins CI/CD pipeline.

## Project Description 📋

This project demonstrates how to deploy a .NET application with a Jenkins CI/CD pipeline. This pipeline includes automated testing, Docker image management, and local development.

## Workflow Diagram 📊
![net workflow](https://github.com/mathesh-me/ci-cd-dotnet-app-deployment/assets/144098846/dcd44360-1c50-4542-9ec9-3604fd04c3a3)


## Prerequisites 📋

Ensure you have the following prerequisites before getting started:

- A virtual machine or EC2 instance with the following installed:
  - [Docker](https://docs.docker.com/engine/install/)
  - [Docker Compose](https://docs.docker.com/compose/install/)
  - [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - [Jenkins](https://www.jenkins.io/doc/book/installing/)
  - [Make](https://www.gnu.org/software/make/)
  - [Python](https://www.python.org/downloads/)
  - [Trivy](https://aquasecurity.github.io/trivy/v0.18.3/installation/)
- A code for the .NET application hosted on GitHub.

## Features 

- **Automated Testing:** Utilize Trivy, SonarQube, and OWASP Dependency Check for comprehensive code testing.
- **Docker Image Management:** Build, scan, and push Docker images seamlessly.
- **Jenkins Integration:** Streamline development with an integrated Jenkins CI/CD pipeline.
- **Local Development:** Easily trigger local builds using the Docker image generated by the pipeline.

## CI/CD Pipeline Overview 📋

1. **Checkout Code:**
   - Automatically fetches the latest code from the GitHub repository.

2. **Testing:**
   - Employs Trivy, SonarQube, and OWASP Dependency Check for thorough code testing.

3. **Docker Image Build:**
   - Utilizes a Makefile to build Docker images.

4. **Docker Image Scan:**
   - Trivy scans Docker images for vulnerabilities.

5. **Docker Image Push:**
   - Pushes the Docker image to a designated repository.

6. **Local Build:**
   - Enables developers to trigger local builds using the generated Docker image.

## Getting Started 🚀

### Steps

| Step No | Document Link |
| ------ | ------ |
| 1 | [Launch t2.large EC2 Instance][Step-1] |
| 2 | [Install and Configure Jenkins][Step-2] |
| 3 | [Install tools on Virtual machine][Step-3] |
| 4 | [Install Plugins in Jenkins][Step-4] |
| 5 | [Configure tools in Jenkins][Step-5] |
| 6 | [Store Credentials in Jenkins][Step-6] |
| 7 | [Creating Pipeline Job][Step-7] |
| 8 | [Configuring Webhook][Step-8] |
| 9 | [Deploying Application][Step-9] |

   [Step-1]: <./Steps/step-1.md>
   [Step-2]: <./Steps/step-2.md>   
   [Step-3]: <./Steps/step-3.md>
   [Step-4]: <./Steps/step-4.md>
   [Step-5]: <./Steps/step-5.md>  
   [Step-6]: <./Steps/step-6.md>
   [Step-7]: <./Steps/step-7.md>
   [Step-8]: <./Steps/step-8.md>
   [Step-9]: <./Steps/step-9.md>

## Usage ⚙️

- Clone the repository to your local machine or Jenkins server.

- Create a new pipeline job in Jenkins and configure it to use the `Jenkinsfile` in the repository.

- Run the pipeline job to deploy the .NET application.


## Contributing 🤝

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License 📄

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.

## Aknowledgements 🙏

- [AWS](https://aws.amazon.com/) - For running Jenkins.

- [Jenkins](https://www.jenkins.io/) - For continuous integration and continuous delivery.

- [Docker](https://www.docker.com/) - For containerization.

- [SonarQube](https://www.sonarqube.org/) - For code quality testing.

- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check/) - For dependency testing.

- [Trivy](https://trivy.dev/) - For vulnerability scanning.

- [Make](https://www.gnu.org/software/make/) - For streamlining Docker image builds.


## Author ✍️

- [Mathesh](https://www.linkedin.com/in/mathesh-me/) on LinkedIn.

- You Can also check out my [Medium](https://medium.com/@mathesh-me) for more articles on DevOps Tools and Technologies.



