# 🔗 Mcmanager-link
This repository exists only to make the MCManager project visible and easily accessible. The actual source code for MCManager is hosted in one of my private repositories. This public repo serves as a placeholder and entry point.  
👉 https://mcmanager-app.onrender.com/login

---

# 🏢 MCManager - Recruiter Guide

**Modern Human Resources Management Application**  
*Developed by Oscar Pirrone*

---

## 🎯 **Application Overview**

**MCManager** is a comprehensive web application for human resources management built with the most modern technologies. The application enables employee management, leave requests, administrative documents handling, and offers a granular permission system based on roles.

### 🌐 **Application Access**
**Demo URL:** [https://mcmanager-app.onrender.com](https://mcmanager-app.onrender.com)

---

## 🔑 **Test Accounts**

### 👨‍💼 **Administrator Account**
- **Email:** `admin@gmail.com`
- **Password:** `admin`
- **Role:** Admin
- **Access:** All functionalities

### 👤 **Employee Account**  
- **Email:** `jean.kevin@gmail.com`
- **Password:** `admin`
- **Role:** Employee
- **Access:** Limited employee functionalities

---

## 🧪 **Testing Guide by Role**

### 🔐 **As Administrator**

**Available Features:**
- ✅ **Dashboard** - HR indicators overview
- ✅ **Staff** - Complete employee management
- ✅ **Leave Requests** - Approve/reject requests
- ✅ **Planning** - Team leave visualization
- ✅ **Documents** - Document management and sharing
- ✅ **Settings** - Application configuration
- ✅ **Notifications** - Real-time alerts

**Recommended Test Scenarios:**
1. **Staff Management**: Create/edit/delete an employee
2. **Leave Validation**: Approve or reject requests
3. **Document Sharing**: Upload and share files
4. **Planning Visualization**: View team schedule
5. **Notifications**: Receive alerts on new requests

### 👥 **As Employee**

**Available Features:**
- ✅ **Dashboard** - Personal view (leave balance, upcoming leaves)
- ✅ **My Account** - Personal profile management
- ✅ **Leave Requests** - Create and track requests
- ✅ **My Planning** - Personal visualization
- ✅ **Documents** - Access shared documents
- ✅ **Settings** - Personal configuration

**Recommended Test Scenarios:**
1. **Leave Request**: Create a new request
2. **Request Tracking**: Check request status
3. **Profile Update**: Modify personal information
4. **Document Access**: Download shared documents
5. **Planning View**: View scheduled leaves

---

## 🛠️ **Technologies Used**

### **Frontend**
- **Vue 3** (Composition API)
- **TypeScript** 
- **Vuetify** (Material Design)
- **Vue Router** (Navigation)
- **Pinia** (State management)
- **Axios** (HTTP client)
- **Vite** (Build tool)

### **Backend**
- **Node.js** + **Express**
- **TypeScript**
- **MongoDB** + **Mongoose**
- **JWT** (Authentication)
- **WebSocket** (Real-time notifications)
- **Multer** (File upload)
- **CASL** (Authorization)

### **Infrastructure**
- **Docker** (Containerization)
- **Nginx** (Reverse proxy)
- **Render** (Hosting)
- **Cloudinary** (File storage)
- **MongoDB Atlas** (Database)

---

## 🏗️ **Technical Architecture**

### **Architectural Patterns**
- **MVC** (Model-View-Controller)
- **Factory Pattern** (Storage services)
- **Repository Pattern** (Data access)
- **Middleware Pattern** (Authentication/Authorization)

### **Security**
- 🔐 **JWT** with RSA keys
- 🛡️ **CASL** for granular permissions
- 🔒 **Authentication middleware**
- 🚫 **Data validation** client and server side

### **Performance**
- ⚡ **WebSocket** for real-time notifications
- 🎯 **Lazy loading** of Vue components
- 💾 **MongoDB query optimization**
- 🗜️ **Asset compression**

---

## 📱 **Main Features**

### 🏠 **Smart Dashboard**
- HR KPI overview
- Interactive charts
- Real-time notifications
- Shortcuts to main actions

### 👥 **Staff Management**
- Complete employee CRUD
- Detailed profiles with photos
- Modification history
- Data export

### 📅 **Advanced Leave System**
- Automatic working days calculation
- Holiday validation
- Approval workflow
- Automatic notifications
- Interactive visual planning

### 📁 **Document Management**
- Secure file upload
- Smart categorization
- Granular user sharing
- Integrated preview

### 🔔 **Real-time Notifications**
- WebSocket for reactivity
- Push notifications
- Alert history
- Read/unread marking

---

## 🚀 **Notable Technical Points**

### **Modularity**
- **Interchangeable services** (Minio ↔ Cloudinary)
- **Centralized configuration** for environments
- **Reusable Vue components**

### **Scalability** 
- **Microservices-ready architecture**
- **Docker containerization**
- **NoSQL database** (MongoDB)

### **User Experience**
- **Material Design interface**
- **Dark/light mode**
- **Responsive design**
- **Loading states** and user feedback

### **Deployment**
- **Automated CI/CD** via GitHub
- **Containerized deployment** on Render
- **Secure environment variables**
- **Automatic SSL**

---

## 🎨 **User Interface**

The application offers a **modern and intuitive interface** with:
- **Material Design** via Vuetify
- **Smooth and responsive** navigation
- **Adaptive dark/light** theme
- **Interactive components** and visual feedback
- **Consistent iconography** Material Design Icons

---

## 📞 **Developer Contact**

**Oscar Pirrone**  
💼 **Full-Stack Developer**  
📧 Email: [oscar.pirrone33@gmail.com] 
🌐 GitHub: [https://github.com/Fragzel](https://github.com/Fragzel)  
🔗 LinkedIn: www.linkedin.com/in/oscar-pirrone-5649621b1

---

## 🎯 **Skills Demonstration**

### **Frontend**
✅ **Vue 3** and **TypeScript** mastery  
✅ **Reusable component** architecture  
✅ State management with **Pinia**  
✅ **Real-time WebSocket** integration  
✅ Modern and responsive **UX/UI**  

### **Backend**
✅ Robust and secure **RESTful API**  
✅ **Modular and scalable** architecture  
✅ Advanced **Authentication/Authorization**  
✅ **File and database** management  
✅ **Real-time WebSocket** implementation  

### **DevOps**
✅ Complete **Docker containerization**  
✅ **Automated CI/CD**  
✅ **Cloud deployment** on Render  
✅ **Multi-environment** configuration  

---

**🚀 Production-ready and enterprise-scalable!** 
