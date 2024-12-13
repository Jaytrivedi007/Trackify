# 🏋️‍♂️ Trackify - Fitness Tracking Application

<div align="center">
  <h1>Trackify</h1>
  <p><em>Your Personal Fitness Journey Companion</em></p>
</div>

## 📝 Overview

Trackify is a comprehensive fitness tracking application that helps users monitor their workout progress, track calories burned, and visualize their fitness journey through intuitive charts and statistics.

## ✨ Features

### 🔐 Authentication
- Secure user registration and login
- JWT-based authentication
- Protected routes for authenticated users

### 📊 Dashboard
- Real-time fitness metrics
- Weekly progress visualization
- Workout category distribution charts
- Daily workout statistics

### 💪 Workout Tracking
- Add detailed workout information
  - Sets and reps tracking
  - Weight monitoring
  - Duration logging
- Automatic calorie calculation
- Categorized workout organization

### 📈 Analytics
- Weekly calories burned charts
- Workout category distribution
- Performance metrics
- Progress tracking

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux (State Management)
- Redux Persist
- Styled Components
- Material UI Charts
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Bcrypt

## 🚀 Getting Started

### Prerequisites
- Node.js
- MongoDB
- npm/yarn

### Installation

1. Clone the repository
 ```bash
 git clone https://github.com/your-repo/trackify.git
 ```

2. Install dependencies
 ```bash
 cd trackify
 npm install
 ```

3. Install dependencies for frontend
 ```bash
 cd client
 npm install
 ```

4. Create a `.env` file in the server directory with the following variables
```bash
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=your_port
```

5. Start the backend server
```bash
cd server
npm start
```

6. Start the frontend server
```bash
cd client
npm start
```


7. Start the frontend application
```bash
cd client
npm start
```
<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/Jaytrivedi007">Jay Trivedi</a></p>
