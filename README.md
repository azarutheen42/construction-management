# Construction Management System (CMS)

A full-stack construction project management web application built using **Django**. This platform streamlines project tracking, resource allocation, blueprint management, and communication between contractors and project managers.

## 🚀 Key Features

* **Project & Site Tracking:** Monitor multiple active construction sites, daily progress logs, and phase milestones.
* **Vendor & Sub-contractor Management:** Directory of active sub-contractors linked directly to assignments.
* **Blueprint & Document Repository:** Version-controlled storage for site blueprints, permits, and inspection reports.
* **Inventory & Resource Allocation:** Track raw material deliveries (cement, steel, etc.) and heavy machinery usage.
* **Role-Based Access Control (RBAC):** Distinct permissions for Project Managers, Site Supervisors, and Clients.

---

## 🛠️ Tech Stack

* **Backend Framework:** Django 5.x (Python)
* **Frontend:** Django Templates, Bootstrap 5, JavaScript (HTMX for dynamic forms optional)
* **Database:** SQLite (Development) / PostgreSQL (Production ready)

---

## ⚙️ Installation & Setup

Follow these steps to get the development environment running locally.

### Prerequisites
* Python 3.10 or higher installed
* Git

### Step-by-Step Guide

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd construction-management-project
   ```

2. **Create and activate a virtual environment**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser account (Admin Dashboard)**
   ```bash
   python manage.py createsuperuser
   ```
   *Follow the terminal prompts to set up your admin username, email, and password.*

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```
   Open your browser and navigate to `http://127.0.0:8000`. Access the admin interface at `http://127.0.0/admin/`.

---


