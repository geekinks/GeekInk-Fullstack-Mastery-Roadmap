# Project: Responsive E-commerce Website (NoSQL - MongoDB) 

Almost everyone enjoys online shopping, and we at Geek Ink understand how crucial it is to have a scalable, responsive, and fast e-commerce platform to serve modern-day consumers. Shopping experiences, much like the fast-paced world of tech, should be seamless, flexible, and accessible to everyone, no matter the device or internet connection.

For this reason, in this roadmap, our main hands-on project will be an e-commerce platform designed for efficiency and scalability. We’ll leverage the power of MongoDB as our NoSQL database, along with modern web technologies to build a user-friendly and robust shopping experience. From managing products and users to handling orders, the platform will allow users to browse, shop, and purchase with ease.

Using open-source tools and cloud services like **DigitalOcean**, we’ll create an application capable of handling thousands of requests and providing real-time updates to the platform. By combining **GitHub Projects Kanban**, **GitHub Actions**, and **Google Meet**, this project will follow agile development practices to ensure smooth collaboration and effective project tracking.

> [!TIP]
>If you are looking for the full roadmap, including details on this project, head back to the repo [home page](../README.md) and start from the beginning!

## Table of Contents
- Project Badge
- Approach
- Goal
- Phase 1: Initial Setup & Planning
  - 1.1 Tools
  - 1.2 Code
  - 1.3 Collaboration
- Phase 2: Frontend Development
  - 2.1 Tools
  - 2.2 Code
  - 2.3 Collaboration
  - 2.4 Testing
- Phase 3: Backend Development & API Integration
  - 3.1 Tools
  - 3.2 Code
  - 3.3 Collaboration
  - 3.4 Continuous Integration
  - 3.5 Testing
- Phase 4: Database & CRUD Operations
  - 4.1 Tools
  - 4.2 Code
  - 4.3 Collaboration
  - 4.4 Continuous Integration
  - 4.5 Continuous Delivery
- Phase 5: Deployment & Scaling
  - 5.1 Tools
  - 5.2 Code
  - 5.3 Collaboration
  - 5.4 Continuous Integration
  - 5.5 Continuous Delivery
- Phase 6: Real-time Features & Optimization

---

---

## Approach

This project follows a dynamic MVP-style approach to gradually implement a **Responsive E-commerce Website** using collaborative tools like GitHub Projects, Google Docs, and Google Meet. Each phase will cover key areas like frontend, backend, testing, and deployment, focusing on industry-standard practices.

Collaborative work will rely on peer-coding with tools like GitHub Kanban boards for project tracking, GitHub Actions for automated tasks, and Google Meet for live sessions. No Docker or other DevOps tools will be involved. Instead, we'll use DigitalOcean for hosting and MongoDB Atlas for the database.

---

## Goal

The goal of this project is to build a **responsive e-commerce website** that features a product catalog, shopping cart, and checkout functionality. We’ll use **MongoDB** (NoSQL) as the database and **React** for the frontend. The website will be highly scalable, leveraging GitHub Actions and cloud platforms like **DigitalOcean** for deployment.

---

## Phase 1: Initial Setup & Planning

### 1.1 Tools
- Git & GitHub
- GitHub Projects (Kanban board for task tracking)
- Google Docs (for documentation)
- Draw.io (for architecture diagrams)

### 1.2 Code
- Set up the initial file structure for both frontend (React) and backend (Node.js).
- Initialize a GitHub repository and create an issue template for tracking tasks.

### 1.3 Collaboration
- Use **GitHub Projects Kanban** to manage tasks and track progress.
- Set up **Google Meet** for team meetings and collaboration.
- Use **Google Docs** for project planning and documentation sharing.

---

## Phase 2: Frontend Development

### 2.1 Tools
- React.js
- Bootstrap (for responsive design)
- SASS

### 2.2 Code
- Develop a responsive homepage with product listings.
- Implement a navigation bar and product card design.

### 2.3 Collaboration
- Track all frontend development tasks in GitHub Projects (Kanban).
- Hold regular team meetings using **Google Meet** for live feedback.

### 2.4 Testing
- Use **Jest** for frontend unit testing.
- Ensure the website is fully responsive on mobile, tablet, and desktop.

---

## Phase 3: Backend Development & API Integration

### 3.1 Tools
- Node.js
- Express.js
- MongoDB Atlas (NoSQL database)
- Mongoose (ODM for MongoDB)

### 3.2 Code
- Build RESTful APIs for handling products, users, and orders.
- Implement user authentication with JWT for secure login and signup.

### 3.3 Collaboration
- Use **GitHub Issues** for tracking backend tasks.
- Share API design documentation via **Google Docs**.
- Use **Draw.io** for backend architecture diagrams.

### 3.4 Continuous Integration
- Set up **GitHub Actions** to automatically run tests and linting on pull requests.

### 3.5 Testing
- Write backend tests using **Jest** or **Mocha**.
- Test all API endpoints for proper functionality and security.

---

## Phase 4: Database & CRUD Operations

### 4.1 Tools
- MongoDB Atlas (cloud NoSQL database)
- Mongoose (for MongoDB schema management)

### 4.2 Code
- Implement CRUD operations for products, users, and orders.
- Ensure the frontend can interact with the backend API.

### 4.3 Collaboration
- Use **GitHub Projects** to manage CRUD tasks.
- Discuss database design and schema changes in **Google Meet**.

### 4.4 Continuous Integration
- Automate testing of CRUD operations with **GitHub Actions**.

### 4.5 Continuous Delivery
- Deploy the application to **DigitalOcean**, using a CI/CD pipeline managed by GitHub Actions.

---

## Phase 5: Deployment & Scaling

### 5.1 Tools
- DigitalOcean (cloud hosting)
- Nginx (for reverse proxy and load balancing)

### 5.2 Code
- Set up deployment configurations for the application on **DigitalOcean**.
- Implement horizontal scaling for the backend API.

### 5.3 Collaboration
- Use **GitHub Projects** to track deployment and scaling tasks.
- Share deployment documentation via **Google Docs**.

### 5.4 Continuous Integration
- Automate deployment to **DigitalOcean** using **GitHub Actions** for CI/CD.

### 5.5 Continuous Delivery
- Set up continuous delivery to automatically push updates to the live environment on successful builds.

---

## Phase 6: Real-time Features & Optimization

### Approach

In this phase, we add real-time features like notifications using **WebSockets** (or **Socket.io**) for events such as new orders or inventory changes. The project will also undergo performance optimization and caching improvements for faster data access.

### Final Goal:

The final goal of this project is to build a fully responsive, scalable e-commerce platform that adheres to industry best practices, with real-time capabilities and optimized performance. By using tools like GitHub Actions for CI/CD, MongoDB for data management, and DigitalOcean for deployment, this project prepares developers for real-world fullstack development challenges.
