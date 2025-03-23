# Learning Management System (LMS)

A comprehensive Learning Management System built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that facilitates online learning through a robust platform for students and instructors.

## 🌟 Live Demo

[View Live Demo](https://lsm-mern-m1ma.vercel.app/)
https://github.com/sakshamagarwalm2/LSM-MERN/blob/main/Public/Screenshot%202025-03-23%20152422.png

## 🔥 Features

### For Students
- User authentication (Login/Register)
- Browse and enroll in courses
- Watch video lectures
- Track course progress
- Secure payment integration with PayPal
- Interactive learning interface

### For Instructors
- Create and manage courses
- Upload course content and videos
- Track student progress
- Manage enrollments
- Analytics dashboard
- Content management with Cloudinary

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router v6
- Tailwind CSS
- Radix UI Components
- Axios for API calls
- React Player for video playback
- Framer Motion for animations

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cloudinary for media storage
- PayPal integration
- CORS enabled
- Multer for file uploads

## 🚀 Getting Started

### Prerequisites
- Node.js (v16.20.1 or higher)
- MongoDB
- PayPal Developer Account
- Cloudinary Account

### Installation

1. Clone the repository
```bash
git clone https://github.com/sakshamagarwalm2/LSM-MERN.git
cd LSM-MERN
```

2. Install dependencies for both client and server
```bash
# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

3. Set up environment variables

Create `.env` files in both client and server directories:

Client `.env`:
```env
VITE_API_URL=http://localhost:8000
```

Server `.env`:
```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_CLIENT_SECRET=your_paypal_client_secret
```

4. Start the development servers

```bash
# Start client (in client directory)
npm run dev

# Start server (in server directory)
npm run dev
```

## 📁 Project Structure

### Client
```
client/
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── config/
│   ├── context/
│   ├── hooks/
│   ├── lib/
│   ├── pages/
│   └── services/
```

### Server
```
server/
├── controllers/
├── helpers/
├── middleware/
├── models/
└── routes/
```

## 🔒 Authentication Flow

1. User registration with email and password
2. Password encryption using bcryptjs
3. JWT token generation and validation
4. Protected routes using auth middleware
5. Role-based access control (Student/Instructor)

## 🎥 Media Management

- Video content stored and served via Cloudinary
- Secure upload mechanism
- Optimized streaming capabilities
- Support for multiple video formats

## 💳 Payment Integration

- Secure PayPal payment gateway integration
- Transaction tracking
- Payment verification
- Course access management

## 🔐 Security Features

- Password hashing
- JWT authentication
- Protected API endpoints
- Input validation
- CORS configuration
- Secure file uploads

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License.

## 👨‍💻 Author

Saksham Agarwal - [GitHub Profile](https://github.com/sakshamagarwalm2)

## 🙏 Acknowledgments

- React.js Documentation
- MongoDB Documentation
- Express.js Documentation
- Node.js Documentation
- Cloudinary Documentation
- PayPal API Documentation
