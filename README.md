# 🌍 Wanderlust - Explore the World, One Stay at a Time

Wanderlust is a full-stack web application that allows users to discover, list, and review unique stays across the globe. Inspired by modern travel platforms, it offers a complete booking-like experience with dynamic features, secure authentication, and seamless user interaction.

## ✨ About the Project

Wanderlust was built as part of a hands-on web development journey to explore backend architecture, RESTful APIs, and third-party service integrations. It emphasizes clean design, CRUD operations, and user-first functionality.

Whether you're a traveler looking for your next stay or a host wanting to list a property, Wanderlust provides a smooth interface to manage everything.

## ⚙️ Tech Stack

**Backend**  
- Node.js  
- Express.js  
- MongoDB  
- Mongoose

**Authentication & Security**  
- Passport.js  
- Passport Local  
- Passport Local Mongoose  
- Bcrypt  
- Express Session  
- Connect Mongo  
- Cookie Parser  
- Dotenv

**Frontend & Templating**  
- EJS  
- Bootstrap  
- Connect Flash

**File & Image Handling**  
- Multer  
- Cloudinary

**Data Validation**  
- Joi

## 🔑 Key Functionalities

- 🧑‍💼 User Authentication: Register, login, logout, and manage personal profiles securely  
- 🏡 Property Listings: Add, view, update, and delete property details  
- 🖼️ Image Uploads: Upload and manage multiple listing images with Cloudinary  
- ✍️ Review System: Leave and manage reviews on properties  
- ⚠️ Validation & Feedback: Input validation with Joi and flash messaging for user interaction  
- 🔐 Secure Sessions: Session management with Express Session and MongoDB store

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/rohitnitj/Airbnb-Rohit.git
   cd Airbnb-Rohit
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add:
   ```env
   DB_URL=your_mongodb_url
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_KEY=your_cloudinary_key
   CLOUDINARY_SECRET=your_cloudinary_secret
   SECRET=your_session_secret
   ```

4. **Run the Development Server**
   ```bash
   npm start
   ```

## 📸 Screenshots

> *(You can add screenshots here to showcase the interface, listings, reviews, etc.)*

## 🚀 Learnings & Takeaways

- 📌 Built and structured a complete backend using Express.js and MongoDB  
- 🔐 Implemented secure user authentication and session handling  
- 🖼️ Integrated Cloudinary for scalable image storage  
- 🧪 Validated user input using Joi and enhanced UX with real-time feedback  
- 🧰 Improved debugging, routing, and error-handling practices

## 📬 Connect & Explore

- 🌐 **Live App**: [https://airbnb-rohit.onrender.com/login](https://airbnb-rohit.onrender.com/login)  
- 💻 **GitHub Repository**: [https://github.com/rohitnitj/Airbnb-Rohit](https://github.com/rohitnitj/Airbnb-Rohit)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
