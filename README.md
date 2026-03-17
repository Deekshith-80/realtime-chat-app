💬 Socket.IO MERN Chat Application

A full-stack real-time chat application built using the MERN stack and Socket.IO. This project enables users to communicate instantly with a smooth and responsive user interface.

🚀 Features

🔐 User Authentication (Login / Signup)

💬 Real-time messaging using Socket.IO

🟢 Online/Offline user status

✍️ Typing indicators

📜 Chat history storage

📱 Responsive UI (works on mobile & desktop)

Real-time chat apps like this use WebSockets to provide instant communication between users without refreshing the page

🛠️ Tech Stack
Frontend

React.js

CSS / Tailwind (if used)

Backend

Node.js

Express.js

Database

MongoDB (Mongoose)

Real-Time Communication

Socket.IO

📂 Project Structure
SocketIO-MERN-chatApp/
│
├── client/        # React frontend
├── server/        # Node.js backend
├── sockets/       # Socket.IO logic
├── models/        # Database schemas
├── routes/        # API routes
└── config/        # Configuration files
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/YOUR_USERNAME/SocketIO-MERN-chatApp.git
2️⃣ Install dependencies
cd client
npm install

cd ../server
npm install
3️⃣ Setup environment variables

Create a .env file in the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
4️⃣ Run the project
# Start backend
npm run server

# Start frontend
npm start
🌐 How it Works

Users sign up / log in

Socket.IO establishes a real-time connection

Messages are sent instantly without reload

Data is stored in MongoDB for persistence

📸 Screenshots (Optional)

Add screenshots here if you want to make it look more professional

🎯 Future Improvements

📎 File/Image sharing

👥 Group chats

🔔 Notifications

🌙 Dark mode

🤝 Contributing

Feel free to fork this repository and contribute!

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Your Name

GitHub: https://github.com/Deekshith-80
