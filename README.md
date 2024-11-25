# **Blogify**

**Blogify** is a modern blogging platform designed to offer users a seamless way to create, manage, and share blog content. With robust authentication and role-based access control (RBAC), it ensures secure and structured management of resources.

---

## **Features**

- **Authentication:**  
  - Secure user registration and login using **JWT** (JSON Web Tokens).  
  - Passwords securely stored using hashing.  

- **Role-Based Access Control (RBAC):**  
  - Admin: Full access to manage all resources, including all blogs and user roles.  
  - User: Can create, edit, and delete their blogs.  

- **Blog Management:**  
  - Create, edit, and delete blogs.  
  - View and comment on blogs.  

- **File Uploads:**  
  - Support for image uploads using **Multer**.  

- **Dynamic Views:**  
  - Server-side rendering with **EJS** templates for an interactive user experience.

---

## **Technologies Used**

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JSON Web Tokens (JWT)  
- **Templating Engine:** EJS  
- **File Uploads:** Multer  
- **Environment Variables:** dotenv  

---

## **Setup Instructions**

### **1. Clone the Repository**
```bash
git clone <repository-url>
cd BLOGIFY
