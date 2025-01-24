# InvestBuddy: A FinTech Solution for Young Investors 🚀

InvestBuddy is an innovative FinTech platform designed to empower young investors with personalized insights, efficient workflows, and a user-friendly interface. The project leverages modern technologies like Angular, Spring Boot, AWS, and Machine Learning to deliver a robust and scalable solution.

---

## 🛠 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Architecture](#architecture)
- [FullStack Workflow](#fullstack-workflow)
- [Technologies Used](#technologies-used)
- [Team Contributions](#team-contributions)
- [Installation and Setup](#installation-and-setup)
- [Images and Workflow](#images-and-workflow)
- [Acknowledgments](#acknowledgments)

---

## 🌟 Project Overview

InvestBuddy aims to:
- Simplify the investment process for young users.
- Provide personalized investment recommendations using Machine Learning models.
- Ensure a secure and seamless user onboarding experience with advanced **KYC Integration**.

The project is a collaborative effort of a team of software engineering students guided by professors **Pr. Lotfi ELAACHAK**, **Pr. Anouar Abdelhakim Boudhir**, and **Pr. Yasyn EL YUSUFI**.

---

## 🔑 Features

### Core Functionalities:
- **KYC Integration**: Dual-layer verification (Email and Human) using the **Veriff API** for robust user security.
- **Admin Dashboard**: Interactive dashboard with real-time animations, dynamic charts, and intuitive management tools.
- **Investment Recommendations**: AI-driven models delivering personalized insights with an accuracy of 84%.
- **Microservices Architecture**: Scalable backend powered by Spring Boot.
- **Cloud-Ready**: Deployed on AWS with CI/CD pipelines for automated workflows.

---

## 🏗 Architecture

### FullStack Workflow:
- **Frontend**: Angular 19-based components for Login, Registration, KYC Verification, and Investment Dashboard.
- **API Gateway**: Handles all communication between frontend and backend services.
- **Backend Services**: Spring Boot-based microservices for user management, KYC, notifications, and recommendations.
- **Database**: PostgreSQL for structured data storage.
- **Cloud Infrastructure**: AWS for scalability, Keycloak for authentication, and Kafka for asynchronous communication.

![image](https://github.com/user-attachments/assets/ecaf767f-4ed5-4610-891b-bd75bf27b72a)
*Diagram showcasing the end-to-end flow of InvestBuddy.*

---

## 🧰 Technologies Used

| **Category**      | **Tools & Frameworks**                          |
|--------------------|------------------------------------------------|
| Frontend           | Angular 19, Particles.js, Three.js, SweetAlert |
| Backend            | Spring Boot, PostgreSQL, Veriff API           |
| Machine Learning   | Python, TensorFlow, Scikit-Learn              |
| DevOps & Cloud     | AWS, Docker, Jenkins, Keycloak, Kafka         |
| Monitoring         | Eureka, Zipkin                                |

---

## 🤝 Team Contributions

- **Mohamed BARBYCH** - *Frontend Engineer*: Implemented the responsive UI and integrated the KYC verification workflow for efficient onboarding.
  ![image](https://github.com/user-attachments/assets/3af39c12-f968-4493-b1bc-8bd7afcd676c)

- **Boubacar SANGARE** - *Backend Engineer*: Developed the backend architecture and API services for seamless data management.
![image](https://github.com/user-attachments/assets/a399ac3e-8bfe-44ca-95c0-063b14b651a6)

- **Badr BENABDELAH** - *Machine Learning Engineer*: Built the AI models for investment recommendations with 84% accuracy.
  ![image](https://github.com/user-attachments/assets/b8c03b49-2c5f-4cff-8daf-53230d1f7a96)

- **Mouaad ELHANSALI** - *Cloud Engineer*: Designed and managed scalable AWS cloud infrastructure.
  ![image](https://github.com/user-attachments/assets/1fbbb186-c7ca-4b54-b7a2-5578d71b3a79)

- **Abdessamad ABAKHAR** - *DevOps Engineer*: Automated CI/CD pipelines and streamlined deployment processes.
  ![image](https://github.com/user-attachments/assets/b4a32638-7640-43d5-b76b-2be80eedb322)


---

## ⚙️ Installation and Setup

### Prerequisites:
- Node.js and Angular CLI for the frontend.
- JDK and Maven for the backend.
- Docker for containerized deployments.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/investbuddy.git
   cd investbuddy

2. Setup the Frontend:
   ```bash
   cd frontend
   npm install
   npm start

3. Setup the Backend:
   ```bash
   cd backend
   mvn clean install
   java -jar target/investbuddy.jar

4. Deploy on AWS or use Docker for local deployment.
