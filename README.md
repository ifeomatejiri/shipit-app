# ShipIt App 🚀

A lightweight Python web application containerized with Docker and deployed to **Azure Container Apps** using **GitHub Actions**.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Python
- **Containerization:** Docker
- **Cloud Host:** Azure Container Apps
- **CI/CD Pipeline:** GitHub Actions
- **Resource Group:** `shipit-rg`

---

## 📁 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── deploy.yml   # GitHub Actions workflow for automated deployments
├── app.py               # Python application entry point
├── Dockerfile           # Container build definition
└── README.md            # Project documentation
