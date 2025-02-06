# Azure-Based Web Infrastructure Enhancement

## Overview
This project focuses on developing and securing a cloud-based web application designed to host a cybersecurity blog. Built on Microsoft Azure, the platform prioritizes high availability, scalability, and robust security, serving as a resilient environment for sharing cybersecurity insights and updates.

## Key Components

### Cloud Infrastructure
- **Azure App Service:** Deployed for web hosting to ensure seamless scalability and reliability.
- **Azure SQL Database:** Utilized for secure and scalable data storage.

### Backend & Frontend
- **Backend:** Developed with Flask to handle application logic.
- **Frontend:** Crafted using Bootstrap for a responsive and user-friendly design.

### Authentication & Authorization
- **Azure Active Directory (AAD):** Integrated to enhance access control and secure the application against unauthorized access.

### Traffic & Security Measures
- **Azure Front Door:** Configured to enforce HTTPS traffic, ensuring secure communications and optimized content delivery.
- **Web Application Firewall (WAF):** Custom rules applied to mitigate threats, including SQL injection, PHP injection, and cross-site scripting (XSS) attacks.
- **Role-Based Access Control (RBAC):** Implemented to manage user permissions and restrict access to sensitive resources.
- **Security Best Practices:** Regular audits, updates, and SSL/TLS certificate management are in place to maintain data integrity and confidentiality.

## Vulnerability Mitigation
- **WAF Custom Rules:** Block traffic from specific regions and filter out malicious patterns in requests.
- **Input Validation & Sanitization:** Applied to prevent injection attacks and bolster backend security.

## Detailed Presentation
For a comprehensive walkthrough of the infrastructure enhancement and security measures, please view the detailed presentation:
- **[View the Presentation](./CHET%20FLOWERS_Azure-Based%20Web%20Infrastructure%20Enhancement.pdf)**  
  *(Make sure the PDF is included in the repository.)*

## Summary
This project successfully establishes a secure, scalable platform for disseminating cybersecurity knowledge through a cloud-based web application. By leveraging Azure’s robust cloud services and adhering to industry best practices, the application ensures high performance while remaining resilient to potential threats. This case study provides actionable insights into enhancing web security, making it a valuable resource for organizations looking to fortify their digital infrastructure.

## Conclusion
Through comprehensive security measures—from traffic management with Azure Front Door to robust authentication via Azure AD—this project presents a holistic approach to cloud security. It offers a blueprint for developing secure web applications in Azure, emphasizing the need for continuous security assessments and proactive vulnerability mitigation.
