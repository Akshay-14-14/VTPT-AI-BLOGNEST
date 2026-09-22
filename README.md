<div align="center">

# 🤖 AI BlogNest

### **Where Ideas Become Stories.**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=36BCF7&center=true&vCenter=true&width=750&lines=AI-Powered+Blogging+Platform+%E2%9C%A8;Create.+Generate.+Summarize.+Publish.+%F0%9F%9A%80;Powered+by+Google+Gemini+%F0%9F%A4%96;Built+with+React+%2B+Node.js+%2B+MongoDB+%F0%9F%92%9A" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-Frontend-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express.js-REST_API-000000?style=for-the-badge&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/Google_Gemini-AI-4285F4?style=for-the-badge&logo=google&logoColor=white" />

<br/><br/>

<img src="https://img.shields.io/badge/JWT-Authentication-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
<img src="https://img.shields.io/badge/Mongoose-ODM-880000?style=flat-square&logo=mongoose&logoColor=white" />
<img src="https://img.shields.io/badge/bcrypt-Password_Security-338033?style=flat-square" />
<img src="https://img.shields.io/badge/AI_Content-Generation-8A2BE2?style=flat-square" />

<br/><br/>

[![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPOSITORY?style=social)](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)
[![Forks](https://img.shields.io/github/forks/YOUR_USERNAME/YOUR_REPOSITORY?style=social)](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)
[![Issues](https://img.shields.io/github/issues/YOUR_USERNAME/YOUR_REPOSITORY?style=flat-square)](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY)

</div>

---

## 🌟 About The Project

**AI BlogNest** is a full-stack, AI-powered blogging platform designed to make content creation faster, smarter, and more accessible.

The platform combines a modern **React frontend**, a scalable **Node.js + Express backend**, **MongoDB** persistence, secure **JWT authentication**, and **Google Gemini AI** to assist users with blog generation and summarization.

Instead of replacing the writer, AI BlogNest uses AI as a creative assistant — helping users move from an idea to a structured article while keeping the final editing and publishing decision in the user's hands.

### 💡 Core Philosophy

```text
        💭 IDEA
          │
          ▼
     🤖 AI ASSIST
          │
          ▼
      ✍️ EDIT
          │
          ▼
      👀 REVIEW
          │
          ▼
     🚀 PUBLISH
```

---

# ✨ Key Features

<table>
<tr>

<td width="50%" valign="top">

## 🤖 AI Studio

* AI-powered blog generation
* Google Gemini integration
* Topic-based content generation
* AI-assisted writing
* Automatic content structuring
* AI-powered summarization
* Generated content remains editable

</td>

<td width="50%" valign="top">

## ✍️ Blog Management

* Create blog posts
* Edit existing posts
* Delete posts
* View individual articles
* Author information
* Categories
* Publication timestamps

</td>

</tr>

<tr>

<td width="50%" valign="top">

## 🔐 Secure Authentication

* User registration
* User login
* JWT authentication
* Protected routes
* Password hashing with bcrypt
* Author ownership validation

</td>

<td width="50%" valign="top">

## 🔎 Content Discovery

* Browse published blogs
* Search articles
* Category filtering
* Individual blog pages
* Latest content
* Responsive interface

</td>

</tr>
</table>

---

# 🎬 AI Generation Experience

<div align="center">

### From an idea to a publishable article.

```text
┌──────────────┐
│  💭 TOPIC    │
│              │
│ "Future of   │
│  AI"         │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ 🤖 GEMINI AI │
│              │
│ Prompt +     │
│ Generation   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ 📝 DRAFT     │
│              │
│ AI Generated │
│ Blog Content │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ ✍️ EDIT      │
│              │
│ User Review  │
│ & Changes    │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ 🚀 PUBLISH   │
│              │
│ MongoDB      │
└──────────────┘
```

</div>

---

# 🏗️ System Architecture

```text
                         AI BLOGNEST
                              │
          ┌───────────────────┴───────────────────┐
          │                                       │
          ▼                                       ▼
   ┌───────────────┐                       ┌───────────────┐
   │    FRONTEND   │                       │    BACKEND    │
   │               │                       │               │
   │ React 18      │◄──── REST API ──────►│ Express.js    │
   │ Vite          │       JSON            │ Node.js       │
   │ React Router  │                       │ MVC Structure │
   └───────────────┘                       └───────┬───────┘
                                                   │
                              ┌────────────────────┼────────────────────┐
                              │                    │                    │
                              ▼                    ▼                    ▼
                       ┌────────────┐      ┌──────────────┐      ┌─────────────┐
                       │  MongoDB   │      │ JWT / bcrypt │      │   Gemini    │
                       │            │      │              │      │     AI      │
                       │ Users      │      │ Auth         │      │             │
                       │ Blogs      │      │ Security     │      │ Generation  │
                       └────────────┘      └──────────────┘      │ Summarize   │
                                                                └─────────────┘
```

---

# 🧩 MVC Backend Architecture

AI BlogNest follows an MVC-style backend organization.

```text
                    ┌─────────────────────┐
                    │       CLIENT        │
                    │     React App       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │       ROUTES        │
                    │                     │
                    │ Auth Routes         │
                    │ Blog Routes         │
                    │ AI Routes           │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    CONTROLLERS      │
                    │                     │
                    │ authController     │
                    │ blogController     │
                    │ aiController       │
                    └──────┬────────┬─────┘
                           │        │
                 ┌─────────┘        └──────────┐
                 ▼                             ▼
        ┌─────────────────┐           ┌─────────────────┐
        │     MODELS      │           │    SERVICES     │
        │                 │           │                 │
        │ User            │           │ Gemini Service  │
        │ Blog            │           │ AI Processing   │
        └────────┬────────┘           └────────┬────────┘
                 │                             │
                 ▼                             ▼
             MongoDB                    Google Gemini
```

---

# 🔐 Authentication Architecture

```text
┌───────────────┐
│ User Register │
└───────┬───────┘
        ▼
┌──────────────────┐
│ Validate Request │
└───────┬──────────┘
        ▼
┌──────────────────┐
│ bcrypt Password  │
│     Hashing      │
└───────┬──────────┘
        ▼
┌──────────────────┐
│ Store User in DB │
└──────────────────┘


┌───────────────┐
│ User Login    │
└───────┬───────┘
        ▼
┌──────────────────┐
│ Verify Password  │
└───────┬──────────┘
        ▼
┌──────────────────┐
│ Generate JWT     │
└───────┬──────────┘
        ▼
┌──────────────────┐
│ Protected API    │
│ Authorization    │
└──────────────────┘
```

---

# 🛠️ Technology Stack

## 🎨 Frontend

| Technology      | Role                          |
| --------------- | ----------------------------- |
| ⚛️ React 18     | UI development                |
| ⚡ Vite          | Development/build tooling     |
| 🧭 React Router | Client-side routing           |
| 🎨 CSS          | Styling and responsive layout |
| 🔷 Lucide React | UI icons                      |
| 🌐 Fetch API    | REST API communication        |

## ⚙️ Backend

| Technology              | Role               |
| ----------------------- | ------------------ |
| 🟢 Node.js              | Runtime            |
| 🚂 Express.js           | REST API framework |
| 🍃 Mongoose             | MongoDB ODM        |
| 🍃 MongoDB              | Data persistence   |
| 🔐 JWT                  | Authentication     |
| 🔒 bcryptjs             | Password hashing   |
| ✅ express-validator     | Request validation |
| 📝 Morgan               | HTTP logging       |
| 🤖 Google Generative AI | Gemini integration |

---

# 📂 Project Structure

### Frontend

```text
AI-BlogNest-Frontend/
│
├── public/
│
├── src/
│   ├── App.jsx
│   ├── api.js
│   ├── main.jsx
│   └── styles.css
│
├── index.html
├── package.json
├── vite.config.js
└── .env.example
```

### Backend

```text
Code/
│
├── src/
│   ├── config/
│   │   └── db.js
│   │
│   ├── controllers/
│   │   ├── aiController.js
│   │   ├── authController.js
│   │   └── blogController.js
│   │
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   └── errorMiddleware.js
│   │
│   ├── models/
│   │   ├── Blog.js
│   │   └── User.js
│   │
│   ├── routes/
│   │   ├── aiRoutes.js
│   │   ├── authRoutes.js
│   │   └── blogRoutes.js
│   │
│   ├── services/
│   │   └── geminiService.js
│   │
│   ├── app.js
│   └── server.js
│
├── .env
└── package.json
```

---

# 🚀 Getting Started

## 📋 Prerequisites

Before running AI BlogNest, make sure you have:

* Node.js installed
* npm installed
* MongoDB / MongoDB Atlas
* Google Gemini API key

---

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

cd YOUR_REPOSITORY
```

---

## 2. Install Backend Dependencies

```bash
cd Code
npm install
```

---

## 3. Configure Environment Variables

Create a `.env` file inside the backend:

```env
PORT=5000

MONGO_URI=YOUR_MONGODB_CONNECTION_STRING

JWT_SECRET=YOUR_JWT_SECRET

GEMINI_API_KEY=YOUR_GEMINI_API_KEY

GEMINI_MODEL=gemini-2.5-flash
```

> ⚠️ **Never commit your `.env` file or API keys to GitHub.**

---

## 4. Start the Backend

```bash
npm run dev
```

or:

```bash
npm start
```

The backend runs on:

```text
http://localhost:5000
```

---

## 5. Install Frontend Dependencies

Open another terminal:

```bash
cd AI-BlogNest-Frontend
npm install
```

---

## 6. Configure Frontend

Create `.env` if required:

```env
VITE_API_URL=http://localhost:5000/api
```

---

## 7. Start Frontend

```bash
npm run dev
```

Open the URL shown by Vite in your browser.

---

# 🔌 REST API

## 🔐 Authentication

| Method | Endpoint             |    Access    | Description       |
| :----: | -------------------- | :----------: | ----------------- |
| `POST` | `/api/auth/register` |   🌐 Public  | Register a user   |
| `POST` | `/api/auth/login`    |   🌐 Public  | Authenticate user |
|  `GET` | `/api/auth/profile`  | 🔒 Protected | Get user profile  |

### Register

```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "password123"
}
```

### Login

```json
{
  "email": "john@example.com",
  "password": "password123"
}
```

---

# 📝 Blog API

|  Method  | Endpoint         | Access | Description       |
| :------: | ---------------- | :----: | ----------------- |
|  `POST`  | `/api/blogs`     |   🔒   | Create blog       |
|   `GET`  | `/api/blogs`     |   🌐   | Get blogs         |
|   `GET`  | `/api/blogs/:id` |   🌐   | Get specific blog |
|   `PUT`  | `/api/blogs/:id` |   🔒   | Update blog       |
| `DELETE` | `/api/blogs/:id` |   🔒   | Delete blog       |

---

# 🤖 AI API

## Generate Blog

```http
POST /api/ai/generate-blog
Authorization: Bearer <JWT_TOKEN>
```

Example request:

```json
{
  "topic": "The Future of Artificial Intelligence",
  "category": "Technology"
}
```

---

## Summarize Content

```http
POST /api/ai/summarize
```

Example:

```json
{
  "content": "Your blog content goes here..."
}
```

Example response:

```json
{
  "summary": "A concise AI-generated summary..."
}
```

---

# 🗄️ Database Design

AI BlogNest currently uses two primary MongoDB/Mongoose models.

## 👤 User Collection

```text
User
│
├── _id
├── name
├── email
├── password
├── createdAt
└── updatedAt
```

## 📝 Blog Collection

```text
Blog
│
├── _id
├── title
├── content
├── category
├── author
├── authorName
├── createdAt
└── updatedAt
```

### Relationship

```text
                 USER
                  │
                  │  1
                  │
                  │  *
                  ▼
                 BLOG
```

One user can create multiple blog posts.

---

# 🖥️ Application Routes

| Route        | Purpose        | Authentication |
| ------------ | -------------- | :------------: |
| `/`          | Home           |       🌐       |
| `/blogs`     | Explore blogs  |       🌐       |
| `/blogs/:id` | Blog details   |       🌐       |
| `/login`     | Login          |       🌐       |
| `/register`  | Registration   |       🌐       |
| `/write`     | Create blog    |       🔒       |
| `/write/:id` | Edit blog      |       🔒       |
| `/ai`        | AI Studio      |       🔒       |
| `/dashboard` | User dashboard |       🔒       |

---

# 🧪 API Testing Workflow

```text
       REGISTER
           │
           ▼
         LOGIN
           │
           ▼
       RECEIVE JWT
           │
           ▼
      GET PROFILE
           │
           ▼
      CREATE BLOG
           │
           ▼
       GET BLOGS
           │
           ▼
     GET BLOG :ID
           │
           ▼
      UPDATE BLOG
           │
           ▼
   GENERATE AI BLOG
           │
           ▼
   SUMMARIZE CONTENT
           │
           ▼
      DELETE BLOG
```

---

# 🔒 Security

AI BlogNest implements several security practices:

* 🔐 JWT-based authentication
* 🔒 bcrypt password hashing
* 🛡️ Protected routes
* 👤 Blog ownership validation
* ✅ Input validation
* 🔑 Environment-based secrets
* 🚫 Gemini API key remains server-side

### Sensitive values

Never expose:

```text
MONGO_URI
JWT_SECRET
GEMINI_API_KEY
```

---

# 📸 Screenshots

Add your actual screenshots to a `screenshots/` directory:

```text
screenshots/
│
├── home.png
├── explore.png
├── login.png
├── register.png
├── dashboard.png
├── ai-studio.png
├── write-blog.png
└── blog-details.png
```

Then showcase them:

## 🏠 Home

![AI BlogNest Home](screenshots/home.png)

## 🤖 AI Studio

![AI BlogNest AI Studio](screenshots/ai-studio.png)

## ✍️ Write Blog

![AI BlogNest Write Blog](screenshots/write-blog.png)

## 📊 Dashboard

![AI BlogNest Dashboard](screenshots/dashboard.png)

---

# 📊 Current Feature Status

| Feature                 | Status |
| ----------------------- | :----: |
| React Frontend          |    ✅   |
| Vite                    |    ✅   |
| Express REST API        |    ✅   |
| MongoDB                 |    ✅   |
| Mongoose                |    ✅   |
| JWT Authentication      |    ✅   |
| bcrypt Password Hashing |    ✅   |
| Blog CRUD               |    ✅   |
| Search                  |    ✅   |
| Category Filtering      |    ✅   |
| Gemini Integration      |    ✅   |
| AI Blog Generation      |    ✅   |
| AI Summarization        |    ✅   |
| MVC-style Architecture  |    ✅   |
| Semantic Search         |   🚧   |
| MongoDB Atlas Search    |   🚧   |
| MongoDB Vector Search   |   🚧   |
| Embeddings              |   🚧   |
| RAG                     |   🚧   |
| Document Analysis       |   🚧   |
| Document Q&A            |   🚧   |
| Recommendations         |   🚧   |
| RBAC                    |   🚧   |
| Activity Logging        |   🚧   |

> **Note:** 🚧 features are potential future enhancements and are not represented as currently implemented functionality.

---

# 🔮 Roadmap

```text
                         AI BLOGNEST ROADMAP

                             CURRENT
                                │
                    ┌───────────┴───────────┐
                    │                       │
                AI Writing             Blog Platform
                    │                       │
                    └───────────┬───────────┘
                                │
                                ▼
                         🔎 Semantic Search
                                │
                                ▼
                         🧠 Embeddings
                                │
                                ▼
                    ⚡ Vector Search
                                │
                                ▼
                         📚 RAG Pipeline
                                │
                                ▼
                       📄 Document AI
                                │
                                ▼
                     💬 Document Q&A
                                │
                                ▼
                    🎯 Recommendations
                                │
                                ▼
                         👑 RBAC/Admin
                                │
                                ▼
                       📊 AI Analytics
```

### Planned Enhancements

* 🔎 Semantic search
* 🧠 Embedding generation
* ⚡ MongoDB Atlas Vector Search
* 📚 Retrieval-Augmented Generation
* 📄 Document upload and analysis
* 💬 Document question answering
* 🎯 Personalized recommendations
* 👑 Admin dashboard
* 🔐 Role-based access control
* 📊 Activity analytics
* 🧪 Automated testing
* ☁️ Cloud deployment

---

# 🎯 Why AI BlogNest?

AI BlogNest brings several modern development concepts together in one application:

```text
       FRONTEND
          +
       REST API
          +
    AUTHENTICATION
          +
       DATABASE
          +
       AI APIs
          +
        MVC
          +
      VALIDATION
          │
          ▼
   ┌──────────────────┐
   │   AI BLOGNEST    │
   │                  │
   │ Full-Stack AI    │
   │ Web Application  │
   └──────────────────┘
```

It demonstrates how traditional web application architecture can be combined with generative AI to create a practical content platform.

---

# 🧠 AI Integration

The AI layer is separated from the main application logic through a dedicated Gemini service.

```text
React
  │
  ▼
AI Route
  │
  ▼
AI Controller
  │
  ▼
Gemini Service
  │
  ├── Prompt Construction
  │
  ├── Gemini Request
  │
  ├── Response Processing
  │
  └── Generated Content
```

This separation keeps AI-specific logic away from the core blog and authentication functionality.

---

# 🧱 Development Principles

The project follows several practical software engineering principles:

### Separation of Concerns

Frontend, routes, controllers, models, middleware, and AI services have separate responsibilities.

### Reusable API Layer

Frontend communication is handled through API functions rather than mixing backend calls throughout UI logic.

### Protected Resources

Authentication middleware controls access to protected endpoints.

### Secure Credentials

Sensitive credentials are loaded through environment variables.

### User-Controlled AI

AI-generated content can be reviewed and edited before publishing.

---

# 🤝 Contributing

Contributions are welcome.

### 1. Fork

```bash
git fork https://github.com/YOUR_USERNAME/YOUR_REPOSITORY
```

### 2. Create a feature branch

```bash
git checkout -b feature/amazing-feature
```

### 3. Make your changes

```bash
git add .
```

### 4. Commit

```bash
git commit -m "Add amazing feature"
```

### 5. Push

```bash
git push origin feature/amazing-feature
```

Then create a Pull Request.

---

# ⭐ Show Your Support

If you like **AI BlogNest**, consider:

⭐ Starring the repository
🍴 Forking the project
🐛 Reporting issues
💡 Suggesting improvements
🤝 Contributing code

---

<div align="center">

## 🚀 AI BlogNest

### **Create. Generate. Summarize. Publish.**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=900&color=8B5CF6&center=true&vCenter=true&width=600&lines=Ideas+%E2%86%92+AI+%E2%86%92+Stories;Powered+by+Google+Gemini+%F0%9F%A4%96;Built+with+React+%E2%9A%9B%EF%B8%8F+Node.js+%F0%9F%9F%A2+MongoDB+%F0%9F%8D%83;Where+ideas+become+stories+%E2%9C%A8" alt="Animated footer" />

<br/>

**Built with ❤️ using React • Node.js • Express • MongoDB • Google Gemini**

<br/>

`AI-Powered Content Creation`

</div>
