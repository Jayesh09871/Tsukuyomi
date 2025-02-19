## 🏡 Tsukuyomi


A modern and fully responsive **Real Estate Platform** built using the **MERN stack (MongoDB, Express, React, Node.js)**. This platform allows users to browse, list, and manage properties effortlessly.

---

## 🚀 Features

✅ **User Authentication** (Sign up, Login, Logout)  
✅ **Property Listings** (Add, Update, Delete)  
✅ **Advanced Property Search & Filters**  
✅ **Google Maps & Location Integration**  
✅ **Image Uploads for Properties**  
✅ **Admin Dashboard for Managing Listings**  
✅ **Favorite & Wishlist for Properties**  
✅ **Messaging System Between Buyers & Sellers**  
✅ **Secure Payments & Subscription Plans**  
✅ **SEO Optimized & Fast Performance**  

---

## 🛠 Tech Stack

| **Technology**  | **Purpose**  |
|---------------|------------------|
| **MongoDB** | Database for storing property listings & user data |
| **Express.js** | Backend framework for handling API requests |
| **React.js** | Frontend library for a dynamic UI |
| **Node.js** | Server-side runtime for handling business logic |
| **Redux Toolkit** | State management for React |
| **Mongoose** | MongoDB ORM for database operations |
| **Cloudinary** | Image upload & storage for property images |
| **Firebase** | User authentication & push notifications |
| **Stripe** | Payment processing for premium listings |
| **React Router** | Navigation between pages |
| **Axios** | HTTP requests from frontend to backend |
| **Tailwind CSS** | UI styling for a modern look |

---

## 📂 Folder Structure

### **Frontend (React) - `/client`**
```
client/
│── public/               # Static assets (favicon, images)
│── src/
│   ├── assets/           # Images & icons
│   ├── components/       # Reusable UI components (Navbar, Footer, etc.)
│   ├── pages/            # Page components (Home, Listings, PropertyDetails)
│   ├── redux/            # Redux Toolkit (slices & store)
│   ├── hooks/            # Custom React hooks
│   ├── utils/            # Helper functions
│   ├── services/         # API calls (Axios)
│   ├── App.js            # Main app component
│   ├── index.js          # Entry point for React
│   └── styles/           # TailwindCSS global styles
│── .env                  # Environment variables
│── package.json          # Dependencies & scripts
└── README.md             # Project documentation
```

### **Backend (Node.js + Express) - `/server`**
```
server/
│── config/               # Configuration files (DB, Auth)
│── controllers/          # Business logic for routes
│── models/               # Mongoose schemas for MongoDB
│── routes/               # Express route handlers
│── middlewares/          # Middleware (Auth, Validation, etc.)
│── utils/                # Helper functions (JWT, email, etc.)
│── uploads/              # Image uploads (if not using Cloudinary)
│── .env                  # Environment variables
│── server.js             # Entry point for Express
│── package.json          # Dependencies & scripts
└── README.md             # API documentation
```

---

## 🛠 How to Run the Project

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/real-estate-platform.git
cd real-estate-platform
```

### **2️⃣ Install Dependencies**
#### Frontend:
```sh
cd client
npm install
```
#### Backend:
```sh
cd server
npm install
```

### **3️⃣ Setup Environment Variables**
Create a `.env` file in the `/server` folder with the following variables:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### **4️⃣ Start the Development Servers**
#### Backend:
```sh
cd server
npm run dev
```
#### Frontend:
```sh
cd client
npm start
```

---

## 📌 API Endpoints (Backend)

| Method | Route                   | Description                     | Auth Required |
|--------|--------------------------|---------------------------------|--------------|
| `POST` | `/api/auth/register`     | Register a new user             | ❌ |
| `POST` | `/api/auth/login`        | User login                      | ❌ |
| `GET`  | `/api/properties`        | Get all properties              | ❌ |
| `POST` | `/api/properties`        | Create a new property listing   | ✅ |
| `PUT`  | `/api/properties/:id`    | Update property details         | ✅ |
| `DELETE` | `/api/properties/:id`  | Delete a property listing       | ✅ |
| `POST` | `/api/payment`           | Process Stripe payment          | ✅ |

---

## 🔥 Key Packages Used

### **Frontend (React)**
- **React Router** → For navigation
- **Redux Toolkit** → State management
- **Axios** → API requests
- **Tailwind CSS** → Styling
- **React Icons** → Icons for UI

### **Backend (Node.js & Express)**
- **Mongoose** → MongoDB ORM
- **JWT (jsonwebtoken)** → Authentication
- **Bcrypt.js** → Password hashing
- **Multer** → File uploads
- **Cloudinary** → Image storage
- **Stripe** → Payment processing
- **Express Validator** → Input validation

---

## 🎨 UI Screenshots

### **🏠 Home Page**
![Home Page](https://via.placeholder.com/800x400?text=Home+Page)

### **🔍 Property Listings**
![Property Listings](https://via.placeholder.com/800x400?text=Property+Listings)

### **📜 Property Details**
![Property Details](https://via.placeholder.com/800x400?text=Property+Details)

### **👤 User Dashboard**
![User Dashboard](https://via.placeholder.com/800x400?text=User+Dashboard)

---

## 📢 Contributing
Want to contribute? Follow these steps:
1. **Fork the repository**  
2. **Create a new branch** (`feature/new-feature`)  
3. **Commit your changes**  
4. **Push to GitHub and submit a PR!**  

---

## 🛡 Security & Best Practices

✔ Use **Helmet.js** for security headers  
✔ Validate user inputs using **Express Validator**  
✔ Secure passwords with **bcrypt.js**  
✔ Use **JWT Authentication** for secure API access  
✔ Implement **CORS** for cross-origin access  

---

## 📄 License
This project is **open-source** and available under the **MIT License**.

---

## 🌟 Show Some Love!  
If you like this project, don’t forget to ⭐️ **star the repo** and **share it**!
