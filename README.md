# 📝 Todo-App

A full-stack Todo application built with **HTML**, **CSS**, **JS**, **Node.js**, **Express**, **MongoDB**, and **JWT Authentication**.

## 🚀 Features

- User Signup & Signin (with JWT)
- Secure Passwords (bcrypt)
- Create, Read, Update, Delete Todos
- Rate Limiting for API Security
- Input Validation (zod)
- Static Frontend Serving
- Protected API Routes

## 🛠️ Tech Stack

- **Backend:** Node.js, Express
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, bcrypt
- **Validation:** zod
- **Security:** express-rate-limit
- **Environment:** dotenv

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Praveen1116/Final-Projects.git

# Go to the project folder
cd Final-Projects/finalTodo

# Install dependencies
npm install
```

## ⚙️ Usage

1. **Set up MongoDB:**  
   Make sure MongoDB is running locally or provide a connection string in `.env`.

2. **Configure Environment Variables:**  
   Create a `.env` file in `finalTodo` folder:
   ```
   JWT_SECRET=your_jwt_secret
   MONGODB_URI=your_mongodb_connection_string
   ```

3. **Start the server:**
   ```bash
   node index.js
   ```

4. **Open in browser:**  
   Visit [http://localhost:3000](http://localhost:3000)

## 📚 API Endpoints

| Method | Endpoint           | Description               |
|--------|--------------------|---------------------------|
| POST   | `/api/signup`      | Register a new user       |
| POST   | `/api/signin`      | Login and get JWT token   |
| POST   | `/api/todo`        | Create a new todo         |
| GET    | `/api/todos`       | Get all todos (user)      |
| PUT    | `/api/todo/:id`    | Update a todo             |
| DELETE | `/api/todo/:id`    | Delete a todo             |



## 🧑‍💻 Author

- [Pathi Caleb](https://github.com/Caleb-pathi)
