# Simple Inventory Web

A containerized full-stack inventory management web application built with **Python**, **HTML templates**, and **Docker**. Designed to provide straightforward CRUD (Create, Read, Update, Delete) operations, persistent database storage, and an organized web interface for managing inventory records.

---

## Tech Stack

- **Backend:** Python (REST/Web Routing & ORM Models)
- **Frontend:** HTML Templates, CSS / Node-managed frontend dependencies (`package.json`)
- **Database:** Relational Database configured via `database.py` & `models.py` (with local persistence in `/data`)
- **Containerization:** Docker & Docker Compose

---

## Project Structure

```text
Simple-Inventory-web/
├── data/                   # Persistent database/storage directory
├── templates/              # HTML views rendered by the web application
├── database.py             # Database connection and session configuration
├── models.py               # Database schema and inventory data models
├── main.py                 # Application entry point, routes, and CRUD logic
├── Dockerfile              # Container image build instructions
├── docker-compose.yaml     # Multi-container orchestration and volume mapping
├── requirements.txt        # Python dependencies
├── package.json            # Frontend/Node tooling and dependencies
└── README.md               # Project documentation
