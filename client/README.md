
# 🍽️ QuickDine

QuickDine is a **full-stack food ordering application** with a React frontend and Node.js/Express backend. 🚀

## 🚀 Getting Started

### 📋 Prerequisites

Make sure you have the following installed:

* 🟢 **Node.js** v18 or higher
* 📦 **npm**

### ⚙️ Installation

1. 📥 Clone the repository:

```bash
git clone https://github.com/MahalaxmiGouda-13/QuickDine.git
cd QuickDine
```

2. 💻 Install frontend dependencies:

```bash
cd client
npm install
```

3. 🖥️ Install backend dependencies:

Open another terminal and run:

```bash
cd server
npm install
```

### 🔐 Environment Variables

Create a `.env` file inside the `client` folder:

```env
VITE_API_URL=http://localhost:5000/api
```

Create the required `.env` file inside the `server` folder with your backend configuration.

> ⚠️ **Important:** Never commit `.env` files containing passwords, API keys, database credentials, or other secrets.

## 🛠️ Development Server

### 💻 Frontend

From the `client` folder:

```bash
npm run dev
```

Open your browser at:

🌐 `http://localhost:5173`

### 🖥️ Backend

From the `server` folder:

```bash
npm run dev
```

The backend will run on the port configured in your server environment variables.

## 📦 Building for Production

From the `client` folder:

```bash
npm run build
```

### 👀 Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```text
QuickDine/
├── 📂 client/       # React frontend
├── 📂 server/       # Node.js/Express backend
├── 📄 .gitignore
└── 📄 README.md
```

## ✨ Features

* 🍔 Browse restaurants and food items
* 🔍 Search and explore restaurants
* 🛒 Manage food orders
* 👤 User authentication
* 📋 Restaurant management
* 📊 Admin dashboard
* 📱 Responsive design

## 🧑‍💻 Technologies Used

* ⚛️ React
* 🟦 TypeScript
* 🟢 Node.js
* 🚂 Express.js
* 🍃 MongoDB
* 🎨 Tailwind CSS
* 🔗 REST API

## 📌 Notes

Make sure both the **frontend and backend servers are running** during local development.

Happy coding! 🚀💻


