<!--
  AI BlogNest
  GitHub README
-->

<div align="center">

🤖 AI BlogNest

✨ Create. Generate. Summarize. Publish.

An AI-powered full-stack blogging platform built with React, Node.js, Express, MongoDB and Google Gemini.

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=36BCF7&center=true&vCenter=true&width=650&lines=Write+better+with+AI+%E2%9C%A8;Generate+blogs+with+Gemini+%F0%9F%A4%96;Summarize+content+instantly+%F0%9F%A7%A0;Create.+Edit.+Publish.+%F0%9F%9A%80" alt="Typing animation" />

<br/>

<img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React 18" />
<img src="https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js Express" />
<img src="https://img.shields.io/badge/MongoDB-Mongoose-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Gemini" />
<img src="https://img.shields.io/badge/JWT-Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />

<br/><br/>




</div>

🌟 What is AI BlogNest?

AI BlogNest is a full-stack blogging application that combines a modern React interface with a Node.js/Express REST API, MongoDB persistence, JWT authentication, and Google Gemini AI.

The application helps users:

✍️ Create and manage blog posts

🤖 Generate blog drafts with Google Gemini

🧠 Summarize blog content using AI

🔎 Search and filter published stories

🔐 Secure accounts with JWT authentication

👤 Manage personal blog content

📝 Edit AI-generated content before publishing

AI BlogNest is designed around a simple idea: let AI accelerate content creation while keeping the user in control of the final content.

✨ Features

<table>
<tr>
<td width="50%">

🤖 AI Studio

AI blog generation

Google Gemini integration

Topic-based content generation

Automatic category inference

AI-powered summarization

Generated content can be edited before publishing

</td>
<td width="50%">

📝 Blogging

Create posts

Edit posts

Delete posts

Read published stories

Author information

Categories

Timestamps

</td>
</tr>

<tr>
<td width="50%">

🔐 Authentication

User registration

Secure login

JWT authentication

Protected routes

bcrypt password hashing

Author ownership checks

</td>
<td width="50%">

🔎 Discovery

Explore stories

Text search

Category filtering

Individual blog pages

Latest stories

Responsive navigation

</td>
</tr>
</table>

🧠 AI Workflow

                     ┌──────────────────┐
                     │      USER        │
                     │   Enter Topic    │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │    AI STUDIO     │
                     │  React Frontend  │
                     └────────┬─────────┘
                              │
                              │ POST /api/ai/generate-blog
                              ▼
                     ┌──────────────────┐
                     │   EXPRESS API    │
                     │  AI Controller   │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │  GEMINI SERVICE  │
                     │  Prompt + Model  │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │  GOOGLE GEMINI   │
                     │       AI         │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │ GENERATED BLOG   │
                     │  Cleaned Output  │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │     MONGODB      │
                     │   Blog Storage   │
                     └────────┬─────────┘
                              │
                              ▼
                     ┌──────────────────┐
                     │   EDIT & POST    │
                     │  User Control    │
                     └──────────────────┘

🏗️ System Architecture

┌───────────────────────────────────────────────────────────────┐
│                         AI BlogNest                           │
└───────────────────────────────────────────────────────────────┘

             FRONTEND
┌──────────────────────────────┐
│ React 18 + Vite              │
│ React Router                 │
│ Lucide React                 │
│ CSS                          │
└──────────────┬───────────────┘
               │
               │ REST API / JSON
               ▼
             BACKEND
┌──────────────────────────────┐
│ Node.js + Express            │
│                              │
│ ├── Auth Routes              │
│ ├── Blog Routes              │
│ ├── AI Routes                │
│ ├── Controllers              │
│ ├── Middleware               │
│ └── Gemini Service           │
└───────┬───────────────┬──────┘
        │               │
        │               │
        ▼               ▼
┌──────────────┐   ┌────────────────┐
│   MongoDB    │   │ Google Gemini   │
│ + Mongoose   │   │      API        │
└──────────────┘   └────────────────┘

🔐 Authentication Flow

   REGISTER / LOGIN
          │
          ▼
  ┌─────────────────┐
  │ Express Backend │
  └────────┬────────┘
           │
           ▼
   Password Verification
      / bcrypt Hash
           │
           ▼
      Generate JWT
           │
           ▼
   React stores token
           │
           ▼
  Authorization Header
  Bearer <JWT_TOKEN>
           │
           ▼
  Authentication Middleware
           │
           ▼
      Protected API

🛠️ Technology Stack

Frontend

Technology

Purpose

⚛️ React 18

User interface

⚡ Vite

Frontend development and build tooling

🧭 React Router

Client-side routing

🎨 CSS

Application styling

🔷 Lucide React

Interface icons

🌐 Fetch API

Backend communication

Backend

Technology

Purpose

🟢 Node.js

Backend runtime

🚂 Express.js

REST API

🍃 MongoDB

Database

🍃 Mongoose

MongoDB ODM

🔐 JSON Web Token

Authentication

🔒 bcryptjs

Password hashing

✅ express-validator

Request validation

📝 Morgan

HTTP request logging

🤖 Google Generative AI

Gemini integration

📂 Project Structure

Frontend

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

Backend

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

🚀 Getting Started

Prerequisites

Make sure you have installed:

Node.js

npm

MongoDB or MongoDB Atlas

A Google Gemini API key

1️⃣ Backend Installation

cd Code
npm install

2️⃣ Configure Backend Environment

Create a .env file inside the backend directory:

PORT=5000

MONGO_URI=YOUR_MONGODB_CONNECTION_STRING

JWT_SECRET=YOUR_JWT_SECRET

GEMINI_API_KEY=YOUR_GEMINI_API_KEY

GEMINI_MODEL=gemini-2.5-flash

🔒 Never commit .env or API keys to GitHub.

3️⃣ Start Backend

Development

npm run dev

Production-style start

npm start

Backend:

http://localhost:5000

4️⃣ Frontend Installation

Open another terminal:

cd AI-BlogNest-Frontend
npm install

5️⃣ Configure Frontend

Create .env if required:

VITE_API_URL=http://localhost:5000/api

6️⃣ Start Frontend

npm run dev

Vite will display the local development URL in the terminal.

🔌 REST API

🔐 Authentication

Method

Endpoint

Access

Description

POST

/api/auth/register

Public

Register user

POST

/api/auth/login

Public

Login

GET

/api/auth/profile

Protected

Get profile

Register

{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "password123"
}

Login

{
  "email": "john@example.com",
  "password": "password123"
}

📝 Blog Endpoints

Method

Endpoint

Access

Description

POST

/api/blogs

🔒 Protected

Create blog

GET

/api/blogs

🌐 Public

Get blogs

GET

/api/blogs/:id

🌐 Public

Get blog

PUT

/api/blogs/:id

🔒 Protected

Update blog

DELETE

/api/blogs/:id

🔒 Protected

Delete blog

🤖 AI Endpoints

Generate Blog

POST /api/ai/generate-blog
Authorization: Bearer <JWT_TOKEN>

{
  "topic": "The Future of Artificial Intelligence",
  "category": "Technology"
}

Summarize Blog

POST /api/ai/summarize

{
  "content": "Your blog content goes here..."
}

Response:

{
  "summary": "A concise AI-generated summary..."
}

🗄️ Database

AI BlogNest currently uses two primary Mongoose models.

👤 User

User
├── _id
├── name
├── email
├── password
├── createdAt
└── updatedAt

📝 Blog

Blog
├── _id
├── title
├── content
├── category
├── author
├── authorName
├── createdAt
└── updatedAt

Relationship

             USER
              │
              │ 1
              │
              │ *
              ▼
             BLOG

One user can publish multiple blogs.

🖥️ Application Pages

Route

Purpose

Access

/

Home / latest stories

🌐 Public

/blogs

Explore and search

🌐 Public

/blogs/:id

Blog details

🌐 Public

/login

Login

🌐 Public

/register

Registration

🌐 Public

/write

Create blog

🔒 Protected

/write/:id

Edit blog

🔒 Protected

/ai

AI Studio

🔒 Protected

/dashboard

Personal dashboard

🔒 Protected

🧪 API Testing

A Thunder Client / Postman collection is included with the supplied project.

Recommended testing flow:

Register
   ↓
Login
   ↓
Receive JWT
   ↓
Get Profile
   ↓
Create Blog
   ↓
Get Blogs
   ↓
Get Blog by ID
   ↓
Update Blog
   ↓
Generate AI Blog
   ↓
Summarize Content
   ↓
Delete Blog

🔒 Security

AI BlogNest uses:

🔐 JWT authentication

🔒 bcrypt password hashing

🛡️ Protected API routes

👤 Blog ownership validation

✅ Input validation

🔑 Environment variables for secrets

🚫 Gemini API key kept on the backend

Never expose these values

MONGO_URI
JWT_SECRET
GEMINI_API_KEY

📸 Screenshots

Add screenshots from your running application here:

screenshots/
├── home.png
├── explore.png
├── login.png
├── dashboard.png
├── ai-studio.png
├── write-blog.png
└── blog-details.png

Example Markdown:

## 🏠 Home

![Home](screenshots/home.png)

## 🤖 AI Studio

![AI Studio](screenshots/ai-studio.png)

## 📊 Dashboard

![Dashboard](screenshots/dashboard.png)

📈 Feature Status

Feature

Status

React Frontend

✅

Vite

✅

Express REST API

✅

MongoDB

✅

Mongoose

✅

JWT Authentication

✅

Password Hashing

✅

Blog CRUD

✅

Search

✅

Category Filtering

✅

Gemini Integration

✅

AI Blog Generation

✅

AI Summarization

✅

MVC-style Backend

✅

Semantic Search

🚧

MongoDB Atlas Search

🚧

Vector Search

🚧

RAG

🚧

Document Analysis

🚧

Recommendations

🚧

Role-Based Access Control

🚧

Activity Logging

🚧

🚧 = Not implemented in the supplied project; potential future enhancement.

🔮 Future Enhancements

The project can be extended with:

🔎 Semantic Search
       ↓
🧠 Embeddings
       ↓
⚡ MongoDB Atlas Vector Search
       ↓
📚 RAG Pipeline
       ↓
📄 Document Analysis
       ↓
💬 Document Q&A
       ↓
🎯 Personalized Recommendations
       ↓
👑 Admin Dashboard + RBAC
       ↓
📊 AI Usage Analytics

Additional possibilities:

💬 AI chat assistant

📄 Document upload

🧠 Context-aware Q&A

🎯 Personalized content recommendations

👑 Admin management

📊 Activity analytics

🧪 Automated testing

☁️ Cloud deployment

🧩 MVC Architecture

                  EXPRESS APPLICATION
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
       ROUTES       CONTROLLERS       MODELS
          │              │              │
          │              │              │
     authRoutes      authController    User
     blogRoutes      blogController    Blog
     aiRoutes        aiController
                         │
                         ▼
                  Gemini Service
                         │
                         ▼
                    Google Gemini

🤝 Contributing

Contributions are welcome!

Fork the project

git fork <repository-url>

Create a branch

git checkout -b feature/amazing-feature

Commit changes

git commit -m "Add amazing feature"

Push

git push origin feature/amazing-feature

Then open a Pull Request.

⭐ Support

If you find AI BlogNest useful:

⭐ Star the repository
🍴 Fork the project
🐛 Report issues
💡 Suggest improvements
🤝 Contribute

<div align="center">

🚀 AI BlogNest

Where ideas become stories.

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3200&pause=1000&color=8B5CF6&center=true&vCenter=true&width=550&lines=Write+%E2%9C%A8;Generate+%F0%9F%A4%96;Summarize+%F0%9F%A7%A0;Edit+%E2%9C%8D%EF%B8%8F;Publish+%F0%9F%9A%80" alt="Animated footer" />

<br/><br/>

Built with ❤️ using React • Node.js • MongoDB • Gemini AI

</div>
