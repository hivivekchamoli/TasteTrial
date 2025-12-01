# 🍽️ TasteTrial – Food Recipe Sharing App

TasteTrial is a MERN-stack based recipe sharing platform where users can add, edit, save, and explore food recipes shared by other users. It includes features like favorites, user authentication, and recipe detail pages.

---

## 🚀 Features

✔️ Browse all recipes  
✔️ Add your own recipes  
✔️ Edit or update your submitted recipes  
✔️ Save recipes to Favorites  
✔️ View detailed cooking steps & ingredients  
✔️ User-based filtering — My Recipes section  
✔️ Email shown for recipe creator  
✔️ Fully responsive UI  
✔️ React Router v6 with loaders  
✔️ Secure backend API with MongoDB

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- CSS3

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- CORS Middleware

---

## 📦 Folder Structure

TasteTrial/
│
├── backend/
│ ├── models/
│ ├── routes/
│ ├── server.js
│ └── controllers/
│
└── frontend/
├── src/
│ ├── pages/
│ ├── components/
│ ├── App.jsx
│ ├── main.jsx
│ └── App.css
└── package.json

yaml
Copy code

---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository
```bash
git clone https://github.com/<your-username>/TasteTrial.git
cd TasteTrial
2️⃣ Setup Backend
bash
Copy code
cd backend
npm install
Create .env file:

ini
Copy code
MONGO_URI=your_mongo_connection_string
PORT=5000
Run backend:

powershell
Copy code
npm start
Backend will run at:

http://localhost:5000

3️⃣ Setup Frontend
bash
Copy code
cd ../frontend
npm install
npm run dev
Frontend will run at:

http://localhost:5173

🔗 API Endpoints
Method	Endpoint	Description
GET	/recipe	Get all recipes
GET	/recipe/:id	Get recipe with author email
POST	/recipe	Add new recipe
PUT	/recipe/:id	Update a recipe
DELETE	/recipe/:id	Delete a recipe
GET	/user/:id	Get recipe creator email

🖥️ Environment Requirements
Node.js ≥ 18

MongoDB Database

Browser with LocalStorage support

🎯 Future Improvements
JWT Authentication (Login / Signup)

Image Upload Support (Cloudinary)

Search & Filter Recipes

Categories & Tags

🤝 Contributing
Contributions & suggestions are always welcome!

📄 License
This project is open-source and free to use.
