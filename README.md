# 🛠️ Dockerized Node.js Backend API

This is a **Node.js + Express + TypeScript** backend boilerplate using **MongoDB**, **JWT Auth**, and **Cloudinary**, fully containerized with **Docker** for smooth local dev and deployment 🚀.

---

## 🧪 Tech Stack

- **Node.js + Express**
- **TypeScript**
- **MongoDB** (Dockerized or Atlas)
- **JWT** (Auth system)
- **Cloudinary** (Image upload)
- **Docker + Docker Compose**

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory and paste the following:

```env
NODE_ENV=development
PORT=5000

# MongoDB URI (Docker or Cloud-hosted)
# DATABASE_URL=mongodb+srv://userName:password@cluster0.fudiykq.mongodb.net/docker-check?retryWrites=true&w=majority&appName=Cluster0
DATABASE_URL=mongodb://ts-docker:ts-docker@mongodb:27017/db-docker?authSource=admin

# JWT Settings
JWT_ACCESS_SECRET=your-access-token-secret
JWT_ACCESS_EXPIRES_IN=1h
JWT_REFRESH_SECRET=your-refresh-token-secret
JWT_REFRESH_EXPIRES_IN=7d

# Password hashing
BCRYPT_SALT_ROUND=10

# Cloudinary
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
