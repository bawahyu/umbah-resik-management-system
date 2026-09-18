# Umbah Resik: Shoe Care Management & POS System

A localized Point of Sale (POS) and operational management system designed specifically for shoe care and laundry services. 

While the application serves as a functional booking and inventory system for the business, **the primary engineering focus of this repository is the deployment architecture and cloud infrastructure.** The system is built to demonstrate isolated environments, containerization, and network reliability.

##  Engineering & Infrastructure Focus 

Rather than just building a standalone web app, this project is architected with a DevOps mindset to ensure the laundry shop's data is secure and the system is immune to local hardware failures.

* **Containerization:** The entire application (frontend and Node.js backend) is containerized using **Docker** and orchestrated via `docker-compose.yml`. This ensures the environment is identical whether deployed on a local shop computer or a cloud server.
* **Deployment Architecture:** Designed to be easily migrated from local on-premise routing to **AWS EC2** for cloud centralization.
* **Network Security (Planned):** Implementation of reverse proxy and local LAN segmentation to separate public guest Wi-Fi from the cashier's transaction network.

##  Tech Stack

**Infrastructure & Operations:**
* Docker & Docker Compose
* Target Cloud Deployment: AWS (EC2)
* Version Control: Git

**Application Core:**
* Backend: Node.js
* Frontend: HTML / CSS / Vanilla JS (Client-side rendering)

## Quick Start (Deployment)

Because the infrastructure is fully containerized, deploying the system requires minimal manual configuration.

1. Clone the repository:
   ```bash
   git clone [https://github.com/baguswahyu/umbah-resik-management-system.git](https://github.com/baguswahyu/umbah-resik-management-system.git)
   <img width="1918" height="865" alt="BAGUS WAHYU UMBAH RESIK" src="https://github.com/user-attachments/assets/d8567302-d2d6-4b10-bd9d-9c3fdb3693ea" />
<img width="1903" height="757" alt="BAGUS WAHYU UMBAH RESIK 2" src="https://github.com/user-attachments/assets/eb6db25d-ed24-4d10-9445-9cc587925d41" />
<img width="955" height="471" alt="Cuplikan layar 2026-09-19 005329" src="https://github.com/user-attachments/assets/3b82a3a3-d451-403b-a96e-e8d7a51a4b41" />

