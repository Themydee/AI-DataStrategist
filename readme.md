# 🧠 AI-DataStrategist

**AI-DataStrategist** is a secure full-stack web application for user registration and authentication, built with a modern tech stack. It features form validation, password hashing, and token-based authentication using JSON Web Tokens (JWT).

---

## 📦 Tech Stack

| Layer        | Stack                                                                  |
|--------------|------------------------------------------------------------------------|
| **Frontend** | React, TypeScript, Zod, Axios, Tailwind CSS                           |
| **Form**     | React Hook Form + Zod                                                  |
| **Backend**  | Express.js, Zod, Bcrypt, JWT                                           |
| **Auth**     | JSON Web Token (JWT)                                                   |

---

## 🚀 Features

- 🔐 Secure user registration and authentication  
- 🧠 Schema validation using **Zod** on both frontend and backend  
- 💾 Password hashing using **Bcrypt**  
- 🔑 Token-based authentication with **JWT**  
- ☑️ Client-side form validation with **React Hook Form + Zod**  
- 📬 Simple protected route example  
- 🌐 CORS-enabled API communication  

---

## 🔧 Getting Started

### 📁 Clone the Repository

```bash
git clone https://github.com/edwardogheneochuko/AI-DataStrategist.git

cd AI-DataStrategist

cd client
npm install
npm run dev

cd backend
npm install
node server.js



---

### 🧪 Example Payloads

## `POST /api/user/register`
```json
{
  "username": "Anna",
  "email": "anna@example.com",
  "password": "securePassword"
}

## `Response`
````json
{
    "success": true,
    "message": "User registered successfully",
    "user": {
        "id": "<user_id>",
        "name": "Anna",
        "email": "anna2example.com"
    },
    "token": "<jwt_token>"
}

---


### 📁 Project Structure


```# 🧠 AI-DataStrategist

**AI-DataStrategist** is a secure full-stack web application for user registration and authentication, built with a modern tech stack. It features form validation, password hashing, and token-based authentication using JSON Web Tokens (JWT).

---

## 📦 Tech Stack

| Layer        | Stack                                                                  |
|--------------|------------------------------------------------------------------------|
| **Frontend** | React, TypeScript, Zod, Axios, Tailwind CSS                           |
| **Form**     | React Hook Form + Zod                                                  |
| **Backend**  | Express.js, Zod, Bcrypt, JWT                                           |
| **Auth**     | JSON Web Token (JWT)                                                   |

---

## 🚀 Features

- 🔐 Secure user registration and authentication  
- 🧠 Schema validation using **Zod** on both frontend and backend  
- 💾 Password hashing using **Bcrypt**  
- 🔑 Token-based authentication with **JWT**  
- ☑️ Client-side form validation with **React Hook Form + Zod**  
- 📬 Simple protected route example  
- 🌐 CORS-enabled API communication  

---

## 🔧 Getting Started

### 📁 Clone the Repository

```bash
git clone https://github.com/edwardogheneochuko/AI-DataStrategist.git

cd AI-DataStrategist

cd client
npm install
npm run dev

cd backend
npm install
node server.js


```


---

### 🧪 Example Payloads

#### `POST /api/user/register`
```json
{
  "username": "Anna",
  "email": "anna@example.com",
  "password": "securePassword"
}

````

#### `Response`

````json
{
  "success": true,
  "message": "User registered successfully"
  "user": {
    "id": "<user_id>",
    "name": "Anna",
    "email": "anna2example.com"
  },
  "token": "<jwt_token>"
}

````

---
### 📁 Project Structure

AI-DataStrategist/
│
├── frontend/                 # React frontend
│   └── App.js               # Main registration form
│
├── backend/                  # Express backend
│   ├── server.js            # Main backend entry point
│   ├── routes/              # API routes
│   ├── controllers/         # Controller logic
│   ├── middleware/          # JWT middleware
│
└── README.md                 # Project documentation

---

AI-DataStrategist/
│
├── frontend/                 # React frontend
│   └── App.js               # Main registration form
│
├── backend/                  # Express backend
│   ├── server.js            # Main backend entry point
│   ├── routes/              # API routes
│   ├── controllers/         # Controller logic
│   ├── middleware/          # JWT middleware
│
└── README.md                 # Project documentation

---


---
