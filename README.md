## **E-Commerce MVC Project**

### **Overview**
This project is a fully functional e-commerce web application built using **ASP.NET MVC** and follows the **N-Tier Architecture** design pattern. It is designed to demonstrate professional development techniques such as the **Repository Pattern**, **Unit of Work**, and integration with popular libraries like **Entity Framework**, **jQuery**, and **Stripe** for payment processing.

---

### **Features**
- **Multi-Layered Architecture (N-Tier):**
  The project is structured into multiple layers for separation of concerns:
  - **Presentation Layer**: Handles user interactions and UI rendering.
  - **Business Logic Layer (BLL)**: Processes business logic and manages data flow between layers.
  - **Data Access Layer (DAL)**: Directly interacts with the database using **Entity Framework**.

- **Repository Pattern & Unit of Work:**
  Ensures clean and maintainable code by encapsulating data access logic.

- **Entity Framework:**
  Handles all database interactions through code-first migrations.

- **Theme Integration:**
  Custom themes and templates are integrated to provide a professional look and feel.

- **User Management:**
  - Registration and login system using **Microsoft ASP Identity**.
  - Role-based access control for managing user permissions.

- **Dashboard:**
  - Administrative dashboard for managing products, categories, orders, and user roles.
  - Integrated with **jQuery DataTables** for efficient data display and filtering.

- **Pagination:**
  - Displays products across multiple pages for better usability.

- **Sessions Management:**
  - Stores user-specific data during their session.

- **Online Payment:**
  - Integrated with **Stripe** to handle secure online payments.

- **Publishing:**
  - Deployed on **Microsoft Azure Cloud** for scalability and performance.

---

### **Technologies Used**
- **Frontend:**
  - HTML5, CSS3, Bootstrap
  - jQuery (DataTables, Toaster.js)
- **Backend:**
  - ASP.NET MVC
  - Entity Framework
  - Microsoft ASP Identity
- **Database:**
  - SQL Server
- **Payment Gateway:**
  - Stripe API
- **Deployment:**
  - Microsoft Azure Cloud

---

### **Project Structure**
The project is organized into the following layers:
- **Presentation Layer**: Handles UI and routes.
- **Business Logic Layer (BLL)**: Contains service logic.
- **Data Access Layer (DAL)**: Includes repository and database context.
- **Shared Models**: Defines entities and DTOs used across layers.


![Project Structre photo](https://ibb.co/8KHYnFQ)



---

### **Setup Instructions**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YourUsername/E-Commerce-MVC-Project.git
   cd E-Commerce-MVC-Project
   ```

2. **Database Setup:**
   - Update the connection string in `appsettings.json` to point to your SQL Server instance.
   - Apply migrations to set up the database:
     ```bash
     dotnet ef database update
     ```

3. **Configure Stripe API Keys:**
   - Add your Stripe keys to the `appsettings.json` file:
     ```json
     "Stripe": {
       "PublishableKey": "your-publishable-key",
       "SecretKey": "your-secret-key"
     }
     ```

### **Screenshots**
1. **Website UI:**
   _**(Insert images of the website’s homepage, product pages, etc.)**_

2. **Admin Dashboard:**
   _**(Insert images of the admin panel and data management features.)**_

3. **Project Structure:**
   _**(Insert an image of the folder structure of the project.)**_

