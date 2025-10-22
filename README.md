# 🎓 E-Learning Platform

<div align="center">

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

A modern e-learning platform built with FastAPI (Backend) and React (Frontend).

</div>

## 📁 Project Structure

```
├── learning/           # Backend (FastAPI)
│   ├── config/        # Configuration files
│   ├── database/      # Database models and connections
│   ├── middleware/    # Custom middleware
│   ├── models/        # Pydantic models
│   ├── routers/       # API routes
│   ├── services/      # Business logic
│   └── main.py        # Application entry point
│
└── client/            # Frontend (React)
    ├── public/        # Static files
    ├── src/          # Source code
    │   ├── components/  # React components
    │   ├── pages/      # Page components
    │   ├── services/   # API services
    │   └── utils/      # Utility functions
    └── package.json    # Dependencies
```

## 🚀 Backend (FastAPI)

### ✨ Features
- 🔐 RESTful API architecture
- 🔑 JWT Authentication
- 💾 MySQL Database with SQLAlchemy ORM
- ⚡ Async database operations
- ✅ Input validation with Pydantic
- 🔒 Secure password hashing with bcrypt

### 📦 Dependencies
- FastAPI
- Uvicorn
- SQLAlchemy
- Databases (aiomysql)
- Python-jose (JWT)
- Passlib (Password hashing)
- Pydantic
- Cryptography

### ⚙️ Setup
1. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r learning/requirements.txt
   ```

3. Set up environment variables:
   Create a `.env` file in the learning directory with:
   ```
   DATABASE_URL=mysql+aiomysql://user:password@localhost/dbname
   SECRET_KEY=your-secret-key
   ALGORITHM=HS256
   ACCESS_TOKEN_EXPIRE_MINUTES=30
   ```

4. Run the server:
   ```bash
   uvicorn learning.main:app --reload
   ```

## 🎨 Frontend (React)

### ✨ Features
- ⚛️ Modern React with Vite
- 📱 Responsive design
- 🧩 Component-based architecture
- 🔄 API integration
- 📝 Form validation
- 🛡️ Protected routes

### 📦 Dependencies
- React
- React Router
- Axios
- Tailwind CSS
- ESLint

### ⚙️ Setup
1. Install dependencies:
   ```bash
   cd client
   npm install
   ```

2. Run development server:
   ```bash
   npm run dev
   ```

## 💻 Development

### Backend Development
- 📝 Follow PEP 8 style guide
- 🎯 Use type hints
- 📚 Write docstrings for functions and classes
- ⚠️ Implement proper error handling
- 🧪 Write unit tests

### Frontend Development
- 📝 Follow ESLint rules
- ⚛️ Use functional components with hooks
- 🛡️ Implement proper error boundaries
- 🧪 Write component tests
- 📊 Use proper state management

## 🤝 Contributing
1. 🍴 Fork the repository
2. 🌿 Create a feature branch
3. 💾 Commit your changes
4. 📤 Push to the branch
5. 🔄 Create a Pull Request

## 📄 License
This project is licensed under the MIT License.

---

<div align="center">
Made by Aman Bhatnagar
</div>
