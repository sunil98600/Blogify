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
```
### **2. Install Dependencies**
```bash
npm intall
```
### **3. Configure Environment Variables**
Rename the .env.example file to .env and configure the following variables
```bash
PORT=3000
MONGO_URI=<Your MongoDB URI>
JWT_SECRET=<Your JWT Secret>
```
### **4. Start the Application**
```bash
npm start
```
### **5. Access the Application**
```bash
http://localhost:8000
```
## **Usage**
### **Admin Capabilities**
Manage all blogs and user accounts.
Grant or revoke roles.
### **User Capabilities**
Create, edit, and delete their blogs.
View and comment on blogs by other users.

## **Folder Structure**
```bash
BLOGIFY/
├── controllers/       # Handles application logic
├── middlewares/       # Middleware functions
├── models/            # Database models
├── routes/            # API and application routes
├── services/          # Business logic and utilities
├── views/             # EJS templates for dynamic rendering
├── public/            # Static assets (CSS, images, etc.)
├── app.js             # Application entry point
├── package.json       # Project dependencies
├── .env               # Environment variables
```



