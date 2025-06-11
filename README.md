# 🗓️ Staff Leave Management System

A web-based application built with **Django** (Python) and **SQLite** for managing staff leave requests and approvals. This system provides separate role-based modules for Admin and Staff users, automating the workflow of applying for and handling leave applications.

---

## 🚀 Technology Stack

- **Backend:** Python (Django Framework)
- **Database:** SQLite (`db.sqlite3`)
- **Frontend:** HTML, CSS (Less/SCSS), JavaScript, jQuery
- **Libraries/Tools:** Django ORM & Templating, SQLiteStudio (optional)

---

## 🔑 Key Features

### 🧑‍💼 Role-Based Access
- **Admin:** Full access to staff management and leave approval.
- **Staff:** Can apply for leave, update profile, and view leave history.

### 🛠️ Admin Module
- Add/update staff records
- Approve or reject leave requests
- Dashboard with statistics (total staff, pending leaves)
- Admin profile and password management

### 👨‍💼 Staff Module
- Secure login using email and password
- Apply for leave and view leave status/history
- Profile editing and password change

### 🔄 Leave Workflow
- Staff submits a leave request
- Admin receives and reviews requests from their dashboard
- Admin can approve or reject each request

### 👤 Profile Management
- Users have profile pages with optional profile pictures
- Password change functionality
- Separate login pages for Staff and Admin

### 🌐 Responsive Web UI
- Clean, form-based navigation
- Dashboard, Leave Management, and Profile sections
- Optimized for desktop use

---
## 🛠️ Setup and Installation

### ✅ Prerequisites

Make sure the following are installed on your system:

- **Python 3.x**  
  - On macOS/Linux, use `python3`  
  - On Windows, use `python`

- **Django**  
  Install using pip if not already installed:

  ```bash
  pip install django
### 🧰 SQLiteStudio (Optional)

A GUI tool to view or manage the SQLite database:  
🔗 [https://sqlitestudio.pl/](https://sqlitestudio.pl/)

---

### 📥 Get the Code

Clone the repository or download it as a ZIP:

  ```bash
  git clone https://github.com/SahilKhan-007/Staff_Leave_Management.git
  ```
## Database Setup

The system uses **SQLite**. Check if a `db.sqlite3` file already exists inside `staffleave/slms/`.

- ✅ **If `db.sqlite3` is provided**:  
  You can open and inspect it using [SQLiteStudio](https://sqlitestudio.pl/).

- ❌ **If not provided**:  
  Create the database tables using Django migrations:

  ```bash
  python manage.py migrate
  ```
## How to Run the Staff Leave Management System (Django + Python)

1. **Download the ZIP file**
2. **Extract the file**, copy the `staffleave` folder and paste it on the **Desktop**.
3. **Open VSCode** and click on the **Terminal**.
4. Navigate to the project directory using the `cd` command:

   ```bash
   cd Staff_Leave_Management/staffleave/slms
   ```

5. Run the Django development server:
 ```bash
python manage.py runserver
 ```
6. After running the above command, you will see output indicating that the server is running.

7. Open your browser and go to: 
  http://127.0.0.1:8000
The project will now be running.
