🏡 VibeKey

Find Your Stay. Feel Your Vibe.

VibeKey is a modern accommodation discovery and booking platform that connects travelers with unique stays. Users can explore properties, view detailed listings, check availability, and make bookings through a simple and intuitive interface.

The project is inspired by modern stay-booking marketplaces while focusing on a clean, user-friendly experience and scalable software architecture.

---

✨ Features

👤 User Features

- User registration and authentication
- Browse available properties
- Search and filter stays
- View detailed property information
- Check property availability
- Book accommodations
- View booking details and history
- Manage user profile

🏠 Host Features

- Add and manage property listings
- Upload property images
- Set property details and pricing
- Manage availability
- View and manage bookings

🔎 Discovery

- Location-based property search
- Category-based browsing
- Price filtering
- Property details and amenities
- Responsive listing interface

🔐 Security

- Secure authentication
- Protected user and host operations
- Input validation
- Secure handling of user data

---

🛠️ Tech Stack

Frontend

- HTML5
- CSS3
- JavaScript
- React.js

Backend

- Node.js
- Express.js
- REST APIs

Database

- MongoDB

Tools

- Git
- GitHub
- VS Code
- Postman

---

🏗️ System Architecture

                ┌─────────────────┐
                │      User       │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │   React Client  │
                └────────┬────────┘
                         │
                    REST APIs
                         │
                         ▼
                ┌─────────────────┐
                │ Node + Express  │
                │     Server      │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │    MongoDB      │
                │    Database     │
                └─────────────────┘

---

📂 Project Structure

VibeKey/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── README.md
└── package.json

---

🚀 Getting Started

1. Clone the repository

git clone https://github.com/your-username/vibekey.git
cd vibekey

2. Install dependencies

npm install

If frontend and backend have separate dependencies:

cd client
npm install

cd ../server
npm install

3. Configure environment variables

Create a ".env" file in the server directory:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

4. Run the application

npm run dev

The application will be available locally at the configured frontend URL.

---

🎯 Use Cases

- Travelers looking for short-term accommodation
- Users searching for stays based on location and budget
- Hosts wanting to publish and manage properties
- Users managing their bookings in one place

---

🔮 Future Enhancements

- 💳 Online payment integration
- ⭐ Ratings and reviews
- 💬 Host–guest messaging
- 🗺️ Interactive maps
- 🔔 Booking notifications
- 🤖 AI-powered stay recommendations
- 📱 Progressive Web App support
- ☁️ Cloud deployment and scalable infrastructure

---

📸 Screenshots

Add screenshots of the home page, property listing, property details, booking page, and dashboard here.

---

🌟 Why VibeKey?

VibeKey was built to explore how a real-world two-sided marketplace can connect property hosts and travelers through search, listing management, availability, and booking workflows.

The project demonstrates practical implementation of:

- Full-stack application development
- REST API design
- Authentication and authorization
- Database management
- CRUD operations
- Search and filtering
- Booking workflows
- Responsive UI development

---

👩‍💻 Author

Sneha

B.Tech Computer Science Engineering

"GitHub" (https://github.com/smiling25261)

---

📄 License

This project is developed for educational and portfolio purposes.# VibeKey