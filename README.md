# 🧳 Wanderlust

**Wanderlust** is a full-stack travel listing platform where users can browse, create, and manage travel destinations. It supports image uploads, user authentication, and interactive maps to enhance user engagement. Built with the MERN stack and tools like Cloudinary and Mapbox.

---

## 🚀 Features

- 📝 Create, edit, and delete travel listings  
- 📸 Upload listing images using Cloudinary  
- 🔐 User authentication and session management with Passport.js  
- 💬 Add and delete reviews  
- 🗺️ Interactive maps using Mapbox  
- 💾 MongoDB session storage  
- 📢 Flash messages for notifications  
- 📱 Responsive UI using EJS + Bootstrap or Tailwind CSS

---

## 🛠️ Tech Stack

- **Frontend:** EJS, HTML, CSS, Bootstrap/Tailwind  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **Authentication:** Passport.js, express-session  
- **Image Uploads:** Multer, Cloudinary  
- **Mapping:** Mapbox  
- **Deployment:** Render  

---

## 📁 Project Structure

```
wonderlust/
├── models/             # Mongoose models (Listing, User, Review)
├── routes/             # All Express route files
├── views/              # EJS templates for UI
├── public/             # Static files (CSS, JS, Images)
├── utils/              # Custom error handler and helpers
├── cloudConfig.js      # Cloudinary configuration
├── app.js              # Entry point of the server
├── package.json        # NPM configuration
└── .env                # Environment variables (excluded from repo)
```

---

## 💻 Getting Started

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/ShehbaazAalam/Wonderlust-.git

# Navigate into the project directory
cd wonderlust

# Install dependencies
npm install

# Start the server (make sure MongoDB URI & env variables are set)
nodemon app.js
```

---

## 👤 Author

**Shehbaaz Aalam**  
GitHub: (https://github.com/ShehbaazAalam/Wonderlust-)
Email: shehbaazaalam00786@gmail.com

---
