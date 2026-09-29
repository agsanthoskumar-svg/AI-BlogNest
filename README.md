# 🤖 AI-BlogNest

AI-BlogNest is a full-stack blogging platform designed to help users create, manage, and publish blog content with AI-powered features.

## ✨ Features

* 📝 Create, edit, and manage blog posts
* 🤖 AI-powered content assistance
* 👤 User authentication and authorization
* 🔐 Role-based access control
* 💬 Comment management
* 🏷️ Categories and tags
* 🖼️ Media management
* 👨‍💼 Admin management
* ✅ Request validation and error handling
* 📋 Application logging

## 🛠️ Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB
* REST API
* JWT Authentication

### AI

* AI-powered content generation and assistance
* AI API integration

### Development

* JavaScript
* npm
* Git & GitHub

## 📁 Project Structure

```text
AI-BlogNest/
│
├── Server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/agsanthoskumar-svg/AI-BlogNest.git
```

### 2. Navigate to the project

```bash
cd AI-BlogNest
```

### 3. Install dependencies

```bash
npm install
```

If the backend has its own `package.json`, install its dependencies as well:

```bash
cd Server
npm install
```

### 4. Configure environment variables

Create a `.env` file with the environment variables required by the application.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
AI_API_KEY=your_ai_api_key
```

> Never commit your `.env` file or API keys to GitHub.

### 5. Start the server

From the appropriate project directory, run:

```bash
npm start
```

For development, if the project uses a development script:

```bash
npm run dev
```

## 🔐 Security

AI-BlogNest uses authentication, authorization, validation middleware, and protected environment variables to help secure the application.

Do not expose:

* API keys
* Database credentials
* JWT secrets
* Passwords
* Private tokens

## 📌 API Modules

The backend currently includes modules for:

* Authentication & users
* Posts
* Categories
* Tags
* Comments
* Media
* Admin operations
* AI features

## 🧑‍💻 Development

To contribute:

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git add .
git commit -m "Add your feature"
```

5. Push your branch.

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

## 📄 License

This project is available under the MIT License.

## 👤 Author

**Agsanthoskumar**

GitHub:
https://github.com/agsanthoskumar-svg

---

⭐ If you find AI-BlogNest useful, consider giving the repository a star!

