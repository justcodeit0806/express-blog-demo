# 🚀 Express Blog


> **Note:** This is a demo repository. The full source code is available for purchase at https://justcodeit.net/courses/expressjs.


![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![EJS](https://img.shields.io/badge/ejs-%23A91E50.svg?style=for-the-badge&logo=ejs&logoColor=white)


A fully functional blog application built with Node.js and Express. Users can register, authenticate, and manage articles through a RESTful interface.

**🌐 Live Demo:** [https://express-blog.justcodeit.net](https://express-blog.justcodeit.net)



## ✨ Features 

- **🔐 Authentication:** Secure sessions-based login and registration system.
- **📝 Article Management:** Full CRUD (Create, Read, Update, Delete) functionality for blog posts.
- **🎨 Templating:** Server-side rendering using EJS for dynamic content.
*   **🛡️ Protected Routes:** Middleware implementation to prevent unauthorized access.


## 🛠️ Technologies Used

- **Frontend:** EJS (Embedded JavaScript Templating), CSS
- **Backend:** Node.js, Express.js
- **Auth:** Express Session, Bcrypt
- **Deployment:** Render


## 🚀 Getting Started



Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14 or higher)
- **npm**

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/justcodeit0806/express-blog.git
    cd express-blog
    ```

2.  **Install dependencies:**
    ```sh
    npm install 
    ```

3.  **Set up Environment Variables:**
    The application requires environment variables for configuration. Create a `.env` file in the root directory and add the following:
    ```sh
    PORT=5001
    SESSION_SECRET="your_secret_key"
    ```
    
    

### Running the Application

1.  **Development Mode:** Runs the server with nodemon for hot-reloading.
    ```sh
    npm run dev
    ```

2.  **Production Mode:** Runs the server using standard node.
    ```sh
    node app.js
    ```

Open http://localhost:5001 to view it in the browser.


## ⚙️ API Endpoints

**Auth**

*   `GET /register` - Render the register page.
*   `GET /login` - Render the login page.
*   `GET /logout` - Destroy session and log out
*   `POST /register` - Register a new user.
*   `POST /login` - Authenticate a user and create a session.


**Articles**
*   `GET /articles/new` - Render the "Create Article" Page.
*   `GET /articles/:articleId/update` - Render the "Update Article" Page.
*   `POST /articles` - Create a new article.
*   `PUT /articles/:articleId` - Update an existing article.
*   `DELETE /articles/:articleId` - Delete an article.

## 🎓 About the Course

This repository represents **Project 1** of the **Master Express.js** curriculum at [https://justcodeit.net/courses/expressjs](https://justcodeit.net/courses/expressjs).

**What we build in the full course:**

*   **Project 1:** A functional SSR blog using Express, EJS, and local auth.
*   **Project 2:** A complete **Full-Stack Application** separated into a Backend API and a modern Frontend.
    *   **Backend:** Advanced REST API with Express, Mongoose, and JWT.
    *   **Frontend:** React.js & Tailwind CSS.
    *   **Cloud:** Learn how to work with **Google Cloud Platform (GCP)**.
    *   **Best Practices:** Error handling, input validation, and security headers.

**Ready to become a Full Stack Engineer?**

[**🚀 Start the Full Master Express.js Course**](https://justcodeit.net/courses/expressjs)

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://justcodeit.net">justcodeIt.net</a></sub>
</div>
