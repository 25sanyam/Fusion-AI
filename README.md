# ⚡ Fusion AI  

Fusion AI ⚡ is a powerful AI-SaaS platform that helps users boost productivity by generating articles ✍️, blog titles 📰, AI images 🎨, resume reviews 📄, and background removal 🖼️ — all in one place!

Built with the PERN stack 🖥️ (PostgreSQL, Express, React, Node.js), it provides a seamless experience with Clerk authentication 🔑, subscription billing 💳, and Cloudinary image storage ☁️.

Whether you’re a content creator ✨, developer 👨‍💻, or job seeker 🎯, Fusion AI makes your workflow faster, smarter, and easier. 🚀

## ✨ Features  

- ✍️ **Article Generation** – Create AI-written articles instantly  
- 📰 **Blog Title Suggestions** – Catchy and SEO-friendly titles  
- 🎨 **AI Image Generation** – Generate unique AI images  
- 🖼️ **Background Removal** – Remove image backgrounds effortlessly  
- 📄 **Resume Review** – Get AI-powered suggestions for resumes  
- 🔑 **Authentication & Billing** – Secure login and subscription handling with Clerk  
- 🌍 **Community Gallery** – Explore all publicly available AI-generated images  

## 🛠 Tech Stack  

- **Frontend:** ⚛️ React, 🎨 Tailwind CSS, React Router  
- **Backend:** 🟢 Node.js, 🚀 Express  
- **Database:** 🐘 PostgreSQL  
- **Authentication & Billing:** 🔑 Clerk  
- **File Storage:** ☁️ Cloudinary  
- **Deployment:** ▲ Vercel (Frontend), ▲ Vercel (Backend)  


## 📂 Project Structure  

```bash
Fusion_AI/  
├── 📁 client/                 # 🎨 React frontend  
│   ├── 📁 public/              # Static assets  
│   └── 📁 src/                 # Source code  
│       ├── 🧩 components/      # Reusable UI components  
│       ├── 📄 pages/           # App pages (Home, Dashboard, etc.)  
│       ├── 🌍 context/         # Context API for global state  
│       ├── 🛠 services/        # API & utility functions  
│       └── ⚛️ App.jsx          # Main React app entry  
│
├── 📁 server/                 # 🚀 Node.js backend  
│   ├── 🧑‍💻 controllers/       # Business logic  
│   ├── 🔗 routes/             # API routes  
│   ├── 🗄 models/              # Database models (PostgreSQL)  
│   ├── 🛡 middleware/          # Custom middlewares  
│   └── 📜 server.js            # Entry point  
│
├── 🔐 .env.example            # Sample environment variables  
├── 📦 package.json            # Project dependencies  
└── 📘 README.md               # Project 
```
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file
# ⚙️ Environment Variables  

Create a `.env` file inside the **server** folder and add:  

```env
# Database
DATABASE_URL= "your_postgres_connection_string"

# Clerk
CLERK_PUBLISHABLE_KEY= "your_clerk_publishable_key"
CLERK_SECRET_KEY= your_clerk_secret_key

# Cloudinary
CLOUDINARY_CLOUD_NAME= your_cloud_name
CLOUDINARY_API_KEY= your_cloudinary_api_key
CLOUDINARY_API_SECRET= your_cloudinary_api_secret

# Gemini/ ClipDrop API
GEMINI_API_KEY= "your gemini api key"

CLIPDROP_API_KEY= "your clipdrop api key"

# Other
PORT=5000
 ```
## 💻 Installation  

Follow these steps to run the project locally:  
```bash
git clone https://github.com/25sanyam/Fusion-AI.git
cd Fusion-AI
```

## Install frontend dependencies
cd client
npm install
```

## Install backend dependencies
cd ../server
npm install
```
## Start backend (in server folder)
npm run server
```
## Start frontend (in client folder)
npm run dev
```
🚀 Production Deployment

You can deploy Fusion AI to production using Vercel for both frontend and Backend.
```bash
# 1. Deploy Backend (Server)

Push your code to GitHub.

Create a new project on VErcel

Connect your repo and deploy the server/ folder.

Add your environment variables (from .env) in the vercel dashboard.

After deployment, you’ll get a live API URL (e.g., https://fusion-ai-server.vercel.app/).
```

# 2. Deploy Frontend (Client)
```

Go to Vercel and create a new project.

Import your repo and select the client/ folder.

Set environment variables (like API base URL, Clerk keys, Cloudinary keys).

Deploy! 🎉

Your app will be live at something like https://fusion-ai-client-zeta.vercel.app/
```


## 🎥 Demo  

### 🌐 Live Demo  
👉 [Fusion AI Live](https://fusion-ai-client-zeta.vercel.app/)  



