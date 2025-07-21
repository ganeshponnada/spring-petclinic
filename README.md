# 🐾 Spring PetClinic – DevOps CI/CD Project

This project demonstrates a complete CI/CD pipeline for the [Spring PetClinic](https://github.com/spring-projects/spring-petclinic) Java application using industry-standard DevOps tools and AWS cloud infrastructure. It simulates a real-world deployment workflow from code commit to production deployment.

---

## 🚀 Tech Stack & Tools Used

| Area             | Tools & Services                                          |
|------------------|-----------------------------------------------------------|
| Version Control  | Git, GitHub                                               |
| Build Tool       | Maven                                                     |
| CI/CD Orchestration | Jenkins                                                |
| Code Quality     | SonarQube                                                 |
| Artifact Management | Nexus Repository Manager                              |
| Containerization | Docker (basic)                                            |
| Web Server       | Apache Tomcat (on AWS EC2)                                |
| Cloud Platform   | AWS (EC2, S3, IAM, ECS, ECR, CloudWatch)                  |
| OS & Scripting   | Linux (Amazon Linux), Shell Scripting (Bash)              |

---

## 🔁 CI/CD Pipeline Flow

1. 🧑‍💻 Developer pushes code to **GitHub**
2. 🛠 Jenkins is triggered via webhook
3. ⚙️ Maven builds the application
4. 🔍 SonarQube performs static code analysis
5. 🎯 Build artifacts are stored in **Nexus**
6. 🚀 Artifacts are deployed to **Apache Tomcat** (on AWS EC2)
7. 🐳 Docker image built (basic level) and pushed to **AWS ECR**
8. 📦 Docker container deployed using **AWS ECS Fargate**
9. 📊 Monitoring & logs handled via **AWS CloudWatch**

---

## 📁 Project Structure 

├── Jenkinsfile
├── Dockerfile (basic)
├── deploy/
│ └── deploy.sh
├── scripts/
│ └── startup.sh

yaml
Copy
Edit

---

## 📌 Learning Outcomes

✅ Hands-on with real-time Jenkins pipeline setup  
✅ End-to-end deployment automation using AWS & CI/CD tools  
✅ Practical experience with DevOps in a simulated production environment  

---

## 👤 Author

**Ponnada Ganesh**  
💼 Aspiring DevOps Engineer with 2 years of relevant experience  
📫 Email: ganeshponnada111@gmail.com  
🔗 GitHub: [github.com/ganeshponnada](https://github.com/ganeshponnada)

---

## ✅ Project Status

✔️ Completed & tested end-to-end in a lab-based real-time simulation  
🚀 Ready to deploy and showcase for DevOps interviews

---

## 📄 License

Apache 2.0 – inherited from the original Spring PetClinic repo.
