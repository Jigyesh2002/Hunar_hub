# HunarHub - Skilled Local Artisans & Service Platform

**HunarHub** is a Flask-based web platform designed to connect local skilled artisans, craftsmen, and technicians (carpenters, tailors, electricians, plumbers, etc.) directly with customers looking for reliable and affordable services.

---

## 🚀 How to Run the Project (Step-by-Step Guide)

Follow these steps to set up and run the project locally on your machine.

### Prerequisites
Make sure Python (version 3.10 or higher) is installed on your system.

---

### Step 1: Open Terminal in Project Directory
Open PowerShell or Command Prompt inside the project folder:
```powershell
cd d:\skillconnect
```

---

### Step 2: Create & Activate Virtual Environment

**On Windows (PowerShell):**
```powershell
# Create virtual environment (if not created already)
py -3.12 -m venv venv

# Activate virtual environment
.\venv\Scripts\Activate.ps1
```

**On Command Prompt (cmd):**
```cmd
venv\Scripts\activate.bat
```

---

### Step 3: Install Required Dependencies
Install the required packages from `requirements.txt`:
```powershell
pip install -r requirements.txt
```

---

### Step 4: Seed the Database (Optional but Recommended)
Populate the SQLite database with initial categories, demo admin, customers, workers, and sample bookings:
```powershell
python seed.py
```

---

### Step 5: Start the Flask Development Server
Run the application using:
```powershell
python app.py
```

---

### Step 6: Open in Web Browser
Open your browser and navigate to:
👉 **`http://127.0.0.1:5000`**

---

## 🔐 Demo Login Credentials

You can test the platform using any of these seeded accounts:

| Role | Email | Password |
| :--- | :--- | :--- |
| **Admin** | `admin@hunarhub.com` | `admin123` |
| **Customer** | `rahul@gmail.com` | `password123` |
| **Artisan (Carpenter)** | `ramesh@hunarhub.com` | `password123` |
| **Artisan (Tailor)** | `sunita@hunarhub.com` | `password123` |
| **Artisan (Electrician)** | `amit@hunarhub.com` | `password123` |

---

## 📝 Copyright

**Copyright © 2026 Jigyesh Suthar. All Rights Reserved.**  
Designed & Developed with ❤️ by **Jigyesh Suthar**.
