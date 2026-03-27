

---

# 📚 Book Seller App – Full Stack Web Application

> Built using React (Vite), Tailwind CSS, Node.js, Express.js, MongoDB, JWT Authentication, and Stripe, deployed on Netlify and Render.

---

## 📌 Project Description

The Book Seller App is a full-stack web application designed to manage book listings, user authentication, cart operations, and order processing with payment integration.

The application consists of a user-facing frontend and a dedicated admin panel built using React (Vite), providing a fast and responsive user experience. The admin panel allows administrators to manage books with full CRUD functionality, including image uploads.

The backend is developed using Node.js and Express.js, exposing RESTful APIs for user authentication, book management, cart handling, and order processing. MongoDB is used as the database, with Mongoose for efficient data modeling.

The application implements secure authentication using JWT, password hashing with bcrypt, file upload handling with Multer, and payment integration using Stripe. It also includes a hybrid cart system that supports both guest users (localStorage) and authenticated users (server-side cart).

---

## 🚀 Live Demo

* 🌐 **User Frontend:**
  [https://book-seller-app-frontend-panel.netlify.app/](https://book-seller-app-frontend-panel.netlify.app/)

* 🛠️ **Admin Panel:**
  [https://book-seller-app-admin-panel.netlify.app/](https://book-seller-app-admin-panel.netlify.app/)

* ⚙️ **Backend API:**
  [https://book-seller-app-5u6t.onrender.com](https://book-seller-app-5u6t.onrender.com)

* 📂 **GitHub Repository:**
  [https://github.com/pundalikkore/book-seller-app](https://github.com/pundalikkore/book-seller-app)

---

## 🛠️ Tech Stack

### 🎨 Frontend (User + Admin):

* React.js (Vite)
* Tailwind CSS
* JavaScript (ES6+)
* Axios
* React Router
* React Toastify

### 🎨 UI & Enhancements:

* Lucide React & React Icons
* Swiper / React Slick (carousels)

### ⚙️ Backend:

* Node.js
* Express.js
* RESTful APIs
* Mongoose (ODM)

### 🗄️ Database:

* MongoDB (Atlas)

### 🔐 Authentication & Security:

* JWT (jsonwebtoken)
* bcrypt (password hashing)

### 💳 Payments:

* Stripe API integration

### 📦 Other Tools:

* Multer (image upload)
* Validator
* UUID

### ☁️ Deployment:

* Netlify (Frontend & Admin)
* Render (Backend)
* GitHub (Version Control)

---

## ✨ Features

### 👤 User Features:

* User authentication (JWT-based login)
* Browse and explore books
* View detailed book information
* Add to cart and manage items
* Place orders
* Secure payment integration using Stripe

### 🛒 Cart & Orders:

* Hybrid cart system (localStorage + backend sync)
* Add, update, and remove items from cart
* Persistent cart for guest users
* Order creation and management

### 👨‍💼 Admin Features:

* Add books with image upload
* View and manage all books
* Delete books along with images
* Manage inventory

### 🔐 Authentication:

* Secure login with JWT tokens
* Token-based API access
* Logout functionality

### ⚙️ Backend Features:

* RESTful API architecture
* Modular route structure (`user`, `book`, `cart`, `order`)
* Password encryption using bcrypt
* File upload and static file serving
* Payment integration using Stripe
* CORS configuration for production

### 🎨 UI/UX Features:

* Responsive and modern UI
* Toast notifications
* Password visibility toggle
* Carousel/slider for book display

---

## 📂 Project Structure

```
book-seller-app/
│
├── frontend/        # User Interface (React + Vite)
├── admin/           # Admin Panel (React + Vite)
├── backend/         # Node.js + Express API
└── uploads/         # Uploaded images
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/pundalikkore/book-seller-app.git
cd book-seller-app
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create `.env` file:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_key
```

Run backend:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

### 4️⃣ Admin Panel Setup

```bash
cd admin
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in the backend folder:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_key
PORT=4000
```

⚠️ Do not expose your credentials publicly.

---

## 📸 Screenshots

### 🏠 Home Page
![Home](https://github.com/user-attachments/assets/ac60d25d-c7d2-4df6-9201-70f16690584d)

### ℹ️ About Page
![About](https://github.com/user-attachments/assets/7b194899-f1e7-4de1-a65b-0f70e93e61ad)

### 📚 Books Page
![Books](https://github.com/user-attachments/assets/70455139-12f5-4f03-86fe-2761c270634b)

### 🛒 Cart Page
![Cart](https://github.com/user-attachments/assets/c818bc8d-7f65-4454-a33f-3d22189964ef)

### 💳 Checkout Page
![Checkout](https://github.com/user-attachments/assets/099ab0ee-ec47-4898-b910-35299ed1183e)

### 📦 Orders Page
![Orders](https://github.com/user-attachments/assets/12139e98-19ff-4780-af5f-172fd5a77341)

### 🔐 Login Page
![Login](https://github.com/user-attachments/assets/24ac76a5-ca12-457a-aeeb-739336a60741)

### 🛠️ Admin Dashboard
![Admin](https://github.com/user-attachments/assets/93e07a88-9069-4f58-85b0-b2c8dadc7670)

* Home Page
* Login Page
* Admin Dashboard
* Cart Page

---

## 🧹 Code Quality

* ESLint configured for clean code
* React Hooks linting rules applied
* Modern ES module structure

---

## 🔥 Future Enhancements

* Role-based access (Admin/User)
* Order tracking system
* Advanced search & filters
* Email notifications

---

## 👨‍💻 Author

**Pundalik Kore**
📍 Bengaluru, India
📧 [pundalikkore@gmail.com](mailto:pundalikkore@gmail.com)
🔗 GitHub: [https://github.com/pundalikkore](https://github.com/pundalikkore)

---

## ⭐ Support

If you like this project, please ⭐ the repository!

---




