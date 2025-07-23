# 🧭 TravaLog – A Smart Travel Logging Platform
👉 [Project-code-and-setups-for-Travalog](https://github.com/foranurag0202/Project-code-and-setups-for-Travalog)

Welcome to the **main repository** for **TravaLog**, a platform designed to help users log, organize, and share their travel experiences in a smart and interactive way.

---

## ⚠️ NOTICE: Project Under Development

This repository will serve as the **home for the final and complete version** of TravaLog. The project is currently in active development.

Until then, you can explore the **pre-release version** of the code and setups in this repository:

👉 [Project-code-and-setups-for-Travalog](https://github.com/foranurag0202/Project-code-and-setups-for-Travalog)

---

## 🎯 Project Vision

TravaLog aims to provide:

- 📍 A location-based travel logbook  
- 📸 Media-rich post sharing (images, notes, maps)  
- 🔒 User authentication & private logs  
- 🌐 Real-time syncing and cross-device access  
- 🗂️ Itinerary planning & recommendation system (coming soon)

---

## 🚧 Current Status

The project is under active development and in its **pre-release phase**.

Check out the working code and local setup instructions in the [pre-release repository](https://github.com/foranurag0202/Project-code-and-setups-for-Travalog).

---

## 📅 Roadmap

- ✅ Setup basic project structure  
- ✅ Connect frontend and backend  
- ✅ Implement MongoDB integration  
- 🛠️ Add user authentication  
- 🛠️ Build logging features (locations, media, notes)  
- 🔜 Build recommendation & search engine  
- 🔜 Deploy on cloud platform (Vercel + MongoDB Atlas)

---

## 📝 License

This project will be released under the **MIT License** upon completion.

---

## 🤝 Contributions

Contributions will be open after the first public version is released. Until then, feel free to watch the project or fork the pre-release version.

---

## 📬 Contact

- GitHub: [@foranurag0202](https://github.com/foranurag0202)  
- LinkedIn: [Anurag Yadav](# 🧭 TravaLog – A Smart Travel Logging Platform

Welcome to the **main repository** for **TravaLog**, a platform designed to help users log, organize, and share their travel experiences in a smart and interactive way.

---

## ⚠️ NOTICE: Project Under Development

This repository will serve as the **home for the final and complete version** of TravaLog. The project is currently in active development.

Until then, you can explore the **pre-release version** of the code and setups in this repository:

👉 [Project-code-and-setups-for-Travalog](https://github.com/foranurag0202/Project-code-and-setups-for-Travalog)

---

## 🎯 Project Vision

TravaLog aims to provide:

- 📍 A location-based travel logbook  
- 📸 Media-rich post sharing (images, notes, maps)  
- 🔒 User authentication & private logs  
- 🌐 Real-time syncing and cross-device access  
- 🗂️ Itinerary planning & recommendation system (coming soon)

---

## 🚧 Current Status

The project is under active development and in its **pre-release phase**.

Check out the working code and local setup instructions in the [pre-release repository](https://github.com/foranurag0202/Project-code-and-setups-for-Travalog).



## 🛠 Local Development Setup for the Project

This project uses **Node.js**, **Express**, **MongoDB (local)**, and **EJS** templating engine.

---

### ✅ 1. Install Required Tools

#### 📦 Node.js & npm

Download and install from:
👉 [https://nodejs.org/](https://nodejs.org/)

#### 🛢 MongoDB Community Edition

Install from:
👉 [https://www.mongodb.com/try/download/community](https://www.mongodb.com/try/download/community)

---

### ✅ 2. Install Project Dependencies

Once MongoDB and Node.js are installed, in your project folder, run:

```bash
npm install
```

If `package.json` doesn't exist yet, create it first:

```bash
npm init -y
```

Then install your required packages:

```bash
npm install express mongoose ejs ejs-mate method-override cors
```

Optional but recommended for development:

```bash
npm install -g nodemon
```

---

### ✅ 3. Start MongoDB Locally

Start your MongoDB server using terminal:

```bash
mongod
```

> This will run your MongoDB server locally at `mongodb://127.0.0.1:27017`

To interact with it:

```bash
mongosh
```

Then switch to the database manually:

```bash
use wanderlust
```

---

### ✅ 4. Start the App

Start the Express server:

```bash
node app.js
```

Or use nodemon for auto-reload:

```bash
nodemon app.js
```

Then visit:

```
http://localhost:8080/listings
```

---

### ✅ 5. Seed Some Data (Optional)

If we want to insert data using `mongosh` directly:

```bash
mongosh
use wanderlust

db.listings.insertOne({
  title: "Test House",
  description: "Lovely mountain view",
  price: 150,
  location: "Shimla",
  country: "India"
})
```

---

### 🧾 Summary of the Express Routes

| Route                | Method | Description                  |
| -------------------- | ------ | ---------------------------- |
| `/listings`          | GET    | Show all listings            |
| `/listings/new`      | GET    | Form to create a new listing |
| `/listings`          | POST   | Submit new listing           |
| `/listings/:id`      | GET    | Show individual listing      |
| `/listings/:id/edit` | GET    | Form to edit a listing       |
| `/listings/:id`      | PUT    | Submit edit                  |
| `/listings/:id`      | DELETE | Delete listing               |

---

### 🧠 Reminder: Folder Structure

```
wanderlust/
├── models/
│   └── listing.js
├── utils/
│   ├── wrapAsync.js
│   └── ExpressError.js
├── views/
│   ├── listings/
│   └── error.ejs
├── public/
├── app.js
└── package.json


## 📅 Roadmap

- ✅ Setup basic project structure  
- ✅ Connect frontend and backend  
- ✅ Implement MongoDB integration  
- 🛠️ Add user authentication  
- 🛠️ Build logging features (locations, media, notes)  
- 🔜 Build recommendation & search engine  
- 🔜 Deploy on cloud platform (Vercel + MongoDB Atlas)

---

## 📝 License

This project will be released under the **MIT License** upon completion.

---

## 🤝 Contributions

Contributions will be open after the first public version is released. Until then, feel free to watch the project or fork the pre-release version.

---

## 📬 Contact

- GitHub: [@foranurag0202](https://github.com/foranurag0202)  
- LinkedIn: [Anurag Kumar](https://www.linkedin.com/in/anurag-kumar-549b77257)
)
