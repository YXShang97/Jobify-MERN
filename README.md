# **Jobify - MERN Application**

Jobify is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to manage job applications efficiently. This README provides instructions on how to set up, run, and deploy the application.

## **Getting Started**

### **Prerequisites**

Before running this app, ensure you have the following installed on your machine:

- **Node.js** (v14.x or higher)
- **npm** (v6.x or higher)
- **MongoDB** (running locally or via a cloud service like MongoDB Atlas)

### **Project Setup**

To set up the project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone <your-repo-url>
   cd jobify
   ```

2. **Install Dependencies**
   Run the following script to install all required dependencies for both the server and client:
   ```bash
   npm run setup-project
   ```

### **Running the Application**

You can run the application in development mode or start the client and server individually.

#### **1. Run the Server Only**

```bash
npm run server
```

This command will start the backend server using `nodemon` for hot reloading.

#### **2. Run the Client Only**

```bash
npm run client
```

This command will start the frontend React application.

#### **3. Run Both Client and Server Concurrently**

```bash
npm run dev
```

This command will start both the client and server simultaneously. The app will be available at:

```
http://localhost:5173/
```

### **Setting Up for Production**

To prepare the application for production, use the following script:

```bash
npm run setup-production-app
```

This will install all necessary dependencies, build the React app, and prepare the application for deployment.
