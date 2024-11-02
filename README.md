# Udemy-Clone-Fullstack
A full-stack Udemy clone built with both frontend and backend functionality. This project replicates core features of Udemy, including user authentication, course browsing, enrollment, and more.
**Udemy Course Platform Clone**

**Table of Contents**
1.	Project Overview
2.	Features
3.	Technologies Used
4.	Getting Started
•	Prerequisites
•	Installation
5.	Usage
•	User Guide
•	Admin Guide
6.	Folder Structure
7.	Project Structure and Design
8.	Contributing
9.	Future Enhancements
10.	License
    
**Project Overview**
The Udemy Course Platform Clone is a full-featured web application inspired by the functionality of platforms like Udemy. This project simulates an online course platform, allowing users to browse courses, enroll in classes, and interact with course materials. It was created as a training project to strengthen full-stack development skills using Vue.js on the frontend, and Node.js, Express, and MongoDB on the backend.
The application includes a responsive design, dynamic content, user authentication, and an admin dashboard for managing course-related data. The main purpose of this project is to showcase development skills in a real-world project scenario and provide a starting point for others looking to build similar platforms.

**Features**
This platform includes several key features to provide a full course browsing and learning experience:

**User Features**
1.	User Authentication:Users can sign up, log in, and securely access enrolled courses.
2.	Course Browsing: Users can search, filter, and explore courses by category, level, and other criteria.
3.	Enrollment System: Users can enroll in courses and view their learning progress.
4.	Interactive Course Content: Supports lecture viewing, quizzes, and assessments to enhance learning.
  
**Admin Features**
Admin Dashboard: Admins can access a dashboard to manage courses, instructors, students, and track overall platform metrics.
Content Management: Admins can create, edit, and delete course details, including titles, descriptions, pricing, and categories.
User Management: Admins can manage user accounts and control access.

## Installed Packages

The project uses the following packages:

```bash
@babel/core@7.25.7
@babel/eslint-parser@7.25.7
@fortawesome/fontawesome-free@6.6.0
@vue/cli-plugin-babel@5.0.8
@vue/cli-plugin-eslint@5.0.8
@vue/cli-plugin-router@5.0.8
@vue/cli-plugin-vuex@5.0.8
@vue/cli-service@5.0.8
@vueup/vue-quill@1.2.0
assert@2.1.0
axios@1.7.7
bootstrap-icons@1.11.3
bootstrap-vue-3@0.5.1
bootstrap-vue@2.23.1
bootstrap@5.3.3
buffer@6.0.3
core-js@3.38.1
crypto-browserify@3.12.0
eslint-plugin-vue@8.7.1
eslint@7.32.0
icons@1.0.0
katex@0.16.11
os-browserify@0.3.0
otplib@12.0.1
path-browserify@1.0.1
process@0.11.10
qrcode@1.5.4
quill@2.0.2
speakeasy@2.0.0
stream-browserify@3.0.0
url@0.11.4
util@0.12.5
vm-browserify@1.1.2
vue-axios@3.5.2
vue-router@4.4.5
vue@3.5.11
vuex@4.1.0
```

**Technologies Used**
Frontend: HTML, CSS, JavaScript, Vue.js (Vue 3)
State Management: Vuex
Styling Framework: Bootstrap
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT)

**Getting Started**

**Prerequisites**
Before you begin, make sure you have the following installed:
- **Node.js**: (v14+ recommended)
- **NPM**: (comes with Node.js)
- **MongoDB**: You can use a local instance or MongoDB Atlas.


**Installation**
To get a local copy of the project up and running, follow these steps:

1. Clone the Repository
   ```bash
   git clone https://github.com/yourusername/udemy-clone.git
cd udemy-clone

**Install Dependencies**

npm install

**Run the Development Server**
npm run serve

## Environment Variables

To manage environment variables, create a `.env` file in the root of the project and include any necessary configurations, such as API keys or server URLs.

Example `.env` file:

```plaintext
VUE_APP_API_URL=http://localhost:8000/api
```
**Usage**
Once the server is running, you can:
Register a new user or log in with an existing account.
Browse available courses by category.
Enroll in courses and view content.
Access the admin dashboard for course management (if admin access is provided).

**Contributing**
Contributions are welcome, but the main branch is protected to maintain the integrity of the original showcase project. To contribute:
•	Fork the repository.
•	Create a new branch (git checkout -b feature-branch).
•	Make your changes and commit them (git commit -m 'Add new feature').
•	Push to the branch (git push origin feature-branch).
•	Open a Pull Request.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
**Attribution Required:** If you use or modify this code, please credit MUDASER KHALID as the original author. The original code in the main branch is intended as a stable, uneditable showcase.


