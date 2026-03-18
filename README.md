<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/67f8c229-99c0-4835-acda-2b9903418c59" />


🚀 Java DevOps Automation Pipeline
==================================

An end-to-end CI/CD ecosystem for Java applications. This project integrates automated building, testing, and code quality analysis into a containerized deployment workflow.

🏗️ Architecture & Workflow
---------------------------

1.  **Build:** Managed by **Maven** for dependency and lifecycle control.
    
2.  **Quality:** Static code analysis and security gates via **SonarQube**.
    
3.  **Test:** Automated UI and regression testing using **Selenium WebDriver**.
    
4.  **Package:** Application and environment strictly defined in **Docker**.
    
5.  **CI/CD:** Full orchestration provided by **Jenkins**.
    

🛠️ Technology Stack
--------------------

*   **Language:** Java
    
*   **Build Tool:** Maven
    
*   **Analysis:** SonarQube
    
*   **Automation:** Selenium
    
*   **Containers:** Docker
    
*   **Pipeline:** Jenkins
    

🚀 Quick Start
--------------
```
# Clone the repository
git clone https://github.com/HP04Harsh/Selenium-Maven-Docker-Pipeline.git

# Run build and quality scan
mvn clean verify sonar:sonar

# Build the Docker image
docker build -t devops-pipeline-app .
```
**Maintained by:** [HP04Harsh](https://github.com/HP04Harsh)
