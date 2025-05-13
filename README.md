# 👨‍💼 Employee Management Web Application

This is a full-featured **Java EE-based Employee Management Web Application** built using **NetBeans**, **Enterprise JavaBeans (EJB)**, **JPA**, and **MySQL**, and deployed on **GlassFish Server**. The application supports core CRUD operations, advanced employee queries, and role-based views.

---

## 🚀 Technologies Used

- **Java EE** (Servlets, EJB)
- **Java Persistence API (JPA)**
- **MySQL** (Relational Database)
- **HTML & JSP** (Frontend)
- **GlassFish Server** (Application Server)
- **NetBeans IDE**

---

## ✅ Features

### 🧾 Employee CRUD Operations
- Add Employee – `AddEmployeeServlet.java`, `add_employee.html`, `add_employee_success.jsp`
- Edit Employee – `EditEmployeeServlet.java`, `edit_employee.html`, `edit_employee_result.jsp`
- Delete Employee – `DeleteEmployeeServlet.java`, `delete_employee.html`, `delete_result.jsp`

### 🔍 Employee Filtering & Search
- View All Employees – `ViewAllEmployeesServlet.java`, `view_all_employees.html`, `show_employees.jsp`
- View by ID – `ViewByIdServlet.java`, `view_by_id.html`
- View by Department – `ViewByDepartmentServlet.java`, `view_by_department.html`
- View by Gender – `ViewByGenderServlet.java`, `view_by_gender.html`
- View by Salary Threshold – `ViewBySalaryAboveServlet.java`, `view_salary_above.html`
- View Highest Paid – `HighestPaidServlet.java`, `highest_paid.html`, `show_highest_paid.jsp`

### 👤 Role-Based Interfaces
- **Manager Dashboard** – `manager_menu.html`
- **Secretary Dashboard** – `secretary_menu.html`

---

## 📁 Project Structure

WEB-INF/
│
├── HTML Pages
│ ├── add_employee.html
│ ├── edit_employee.html
│ ├── delete_employee.html
│ ├── view_by_id.html
│ ├── view_by_department.html
│ ├── view_by_gender.html
│ ├── view_salary_above.html
│ ├── manager_menu.html
│ ├── secretary_menu.html
│ └── index.html
│
├── JSP Pages
│ ├── add_employee_success.jsp
│ ├── edit_employee_result.jsp
│ ├── delete_result.jsp
│ ├── show_employees.jsp
│ ├── show_highest_paid.jsp
│ └── search_result.jsp
│
└── Java Servlets (in ac.za.servlets)
├── AddEmployeeServlet.java
├── EditEmployeeServlet.java
├── DeleteEmployeeServlet.java
├── ViewAllEmployeesServlet.java
├── ViewByIdServlet.java
├── ViewByDepartmentServlet.java
├── ViewByGenderServlet.java
├── ViewBySalaryAboveServlet.java
└── HighestPaidServlet.java


---

## 💡 How It Works

1. User navigates through role-based dashboards (Manager or Secretary).
2. Forms (HTML) collect employee details or search parameters.
3. Servlets handle the HTTP requests and delegate to EJBs for business logic.
4. JPA interacts with the MySQL database to perform persistence operations.
5. Results are displayed using JSP pages.

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-management.git
