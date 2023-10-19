# Employee Management System

## Description

The Employee Management System is a web application built using Django. It provides a platform for managing employee data, including personal information, work details, and more. The system allows administrators to have full control over employee records, while employees can log in to view and edit their own profiles.

## Features

1. **Authentication and Authorization:**
   - Secure authentication system for employees and administrators.
   - Employees can log in to view and edit their own profiles.
   - Administrators have full control over employee data.

2. **Employee Profile Management:**
   - Create, retrieve, update, and delete employee profiles.
   - Each profile includes fields such as name, email, contact information, department, and position.

3. **Admin Panel:**
   - User-friendly admin panel for easy management of employee data.
   - Add, edit, and delete employee records.

4. **Search and Filter Functionality:**
   - Search employees by name, department, or position.
   - Filter employees based on specific criteria.

5. **User-Friendly Interface:**
   - Intuitive and easy-to-use interface for seamless navigation.
   - Clear layout for accessing different sections of the application.

6. **Security Measures:**
   - Implemented security measures to ensure only authorized users have access to sensitive employee data.
   - Passwords are securely hashed for added security.

## Getting Started

### Prerequisites

- Python (3.6 or higher)
- Django (3.0 or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shrey1010/employee-management-system.git
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   ```

3. Activate the virtual environment:

   - Windows: `venv\Scripts\activate`
   - macOS and Linux: `source venv/bin/activate`

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Run the Django development server:

   ```bash
   python manage.py runserver
   ```

2. Open your web browser and go to [http://localhost:8000](http://localhost:8000) to access the application.

3. Use the following credentials to log in:

   - Administrator:
     - Username: admin
     - Password: admin

   - Employee:
     - Username: employee
     - Password: employeepassword

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes and commit them (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Create a pull request


## Acknowledgments

- Mention any resources or tutorials you used during the development of this project.

---