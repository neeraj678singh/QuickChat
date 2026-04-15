# QuickChat
My first full-stack MERN project. A real-time chat application with modern UI, built using MERN stack + Socket.io.
</br>
</br>


<h2>Features</h2>
<pre>
💬 Real-time messaging using Socket.io
🟢 Online/Offline user status
📩 Unseen message count
🖼️ Image sharing support
🔐 Authentication (Login/Signup with JWT)
👤 User profile management
📱 Responsive UI
🖼️ Screenshots
</pre>

<h2>Tech Stack</h2>
<pre>
Layer:	Technology
Frontend:	React, Tailwind CSS
Backend:	Node.js, Express
Database:	MongoDB
Realtime:	Socket.io
Auth:	JWT
Storage:	Cloudinary
</pre>

<h2>Installation</h2>
<pre>
1️⃣ Clone the Repository
git clone https://github.com/your-username/quick-chat-app.git
cd quick-chat-app
2️⃣ Backend Setup
cd server
npm install
</pre>
</br>
<pre>
Create .env file:

MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret

</pre>

<h2>Run backend:</h2>
<pre>
npm run dev
3️⃣ Frontend Setup
cd client
npm install
npm run dev
</pre>

<h2>API Endpoints</h2>
<pre>
Auth
POST /api/auth/signup
POST /api/auth/login
GET /api/auth/check
Messages
GET /api/messages/users
GET /api/messages/:id
POST /api/messages/send/:id
PUT /api/messages/mark/:id
</pre>


<h2>Project Structure: </h2>
<pre>
quick-chat-app/
│
├── client/          # React frontend
│   ├── components/
│   ├── pages/
│   └── context/
│
├── server/          # Express backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── lib/
│
└── README.md
</pre>
