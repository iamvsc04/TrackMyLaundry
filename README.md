# Project Laundry - NFC-Enabled Laundry Management System

A modern laundry management system that uses NFC-enabled laundry bags to track garments through various processing stages with real-time updates for users and admins.

## Features

### User Features
- User authentication (JWT)
- NFC-enabled laundry bag tracking
- Real-time laundry status tracking
- Push notifications and SMS updates
- Transaction history
- Digital receipts and coupons

### Admin Features
- Admin dashboard
- NFC tag management
- Inventory tracking
- Process monitoring
- Customer management
- Analytics and reporting

## Tech Stack

- **Frontend**: React.js (Vite) + Tailwind CSS
- **Backend**: Node.js + Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **NFC Integration**: node-nfc
- **Notifications**: Firebase Cloud Messaging, Twilio
- **PDF Generation**: PDFKit
- **Hosting**: Vercel (Frontend), Render (Backend)

## Project Structure

```
project-laundry/
├── client/                 # Frontend React application
├── server/                 # Backend Node.js application
├── docs/                   # Documentation
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- MongoDB
- NFC Reader hardware
- Firebase account
- Twilio account

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/project-laundry.git
cd project-laundry
```

2. Install dependencies
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables
```bash
# In server directory
cp .env.example .env
# Fill in your environment variables
```

4. Start the development servers
```bash
# Start backend server (from server directory)
npm run dev

# Start frontend server (from client directory)
npm run dev
```

## Environment Variables

### Backend (.env)
```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
FIREBASE_CONFIG=your_firebase_config
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
```

### Frontend (.env)
```
VITE_API_URL=http://localhost:5000
VITE_FIREBASE_CONFIG=your_firebase_config
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. #
