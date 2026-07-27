# 🎯 AI-Powered Habit Tracker App

A full-stack habit tracking application with AI-powered insights, GitHub-style streak visualization, and personalized recommendations. Built with the MERN stack and enhanced with Google Gemini AI for intelligent habit analysis and streak recovery planning.

## ✨ Features

- **JWT Authentication**: Secure user authentication and authorization
- **GitHub-Style Streak Heatmaps**: Visual representation of habit streaks and consistency patterns
- **Google Gemini AI Integration**: 
  - Personalized weekly reports on habit progress
  - Smart habit suggestions based on user patterns
  - Automated streak-recovery plans for missed habits
- **Habit Management**: Create, track, update, and manage multiple habits
- **Visual Analytics**: Track progress with beautiful charts and heatmaps
- **Responsive Design**: Mobile-friendly interface with Tailwind CSS

## 🛠️ Tech Stack

### Frontend
- **React.js** - UI framework
- **Tailwind CSS** - Utility-first styling
- **HTML5** - Markup

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database

### Authentication & AI
- **JWT** - Secure token-based authentication
- **Google Gemini AI** - AI-powered insights and recommendations

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or cloud instance)
- Google Gemini API key

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/RupeshPradhan33/ai-powered-habit-tracker-app.git
   cd ai-powered-habit-tracker-app
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Setup**

   Create a `.env` file in the `backend` directory:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   GOOGLE_GEMINI_API_KEY=your_gemini_api_key
   NODE_ENV=development
   ```

   Create a `.env` file in the `frontend` directory:
   ```
   REACT_APP_API_URL=http://localhost:5000
   ```

## 💻 Running the Application

### Development Mode

**Terminal 1 - Start Backend Server:**
```bash
cd backend
npm start
```
The backend server will run on `http://localhost:5000`

**Terminal 2 - Start Frontend Development Server:**
```bash
cd frontend
npm start
```
The frontend will run on `http://localhost:3000`

### Production Mode

```bash
cd backend
npm run build
npm run start:prod
```

```bash
cd frontend
npm run build
```

## 📁 Project Structure

```
ai-powered-habit-tracker-app/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── utils/
│   │   └── App.js
│   └── public/
└── README.md
```

## 🔑 Key Features Explained

### JWT Authentication
- Secure login and registration system
- Token-based authentication for API requests
- Refresh token mechanism for extended sessions

### Habit Tracking
- Create and manage multiple habits
- Log daily habit completion
- View historical data and patterns

### GitHub-Style Heatmaps
- Visual representation of habit streaks
- Color-coded intensity based on consistency
- Motivational streak counter

### AI-Powered Insights
- **Weekly Reports**: Comprehensive analysis of your habit progress
- **Smart Suggestions**: AI-generated habit recommendations based on your patterns
- **Streak Recovery Plans**: Personalized strategies to recover from missed habits

## 📊 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/refresh` - Refresh JWT token

### Habits
- `GET /api/habits` - Get all user habits
- `POST /api/habits` - Create new habit
- `PUT /api/habits/:id` - Update habit
- `DELETE /api/habits/:id` - Delete habit

### Tracking
- `POST /api/habits/:id/log` - Log habit completion
- `GET /api/habits/:id/history` - Get habit history

### AI Insights
- `GET /api/ai/weekly-report` - Get AI-generated weekly report
- `GET /api/ai/suggestions` - Get habit suggestions
- `POST /api/ai/recovery-plan` - Generate streak recovery plan

## 🔐 Security Features

- **Password Hashing**: Bcrypt for secure password storage
- **JWT Tokens**: Secure stateless authentication
- **Input Validation**: Server-side validation for all inputs
- **CORS Protection**: Configured CORS headers
- **Environment Variables**: Sensitive data stored securely

## 🎨 UI/UX Highlights

- Clean, intuitive interface
- Dark mode support
- Responsive design for all devices
- Smooth animations and transitions
- Real-time updates

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🐛 Bug Reports & Suggestions

Found a bug or have a suggestion? Please open an issue on GitHub with a clear description and any relevant details.

## 📞 Support

For support, please reach out via:
- GitHub Issues: [Create an Issue](https://github.com/RupeshPradhan33/ai-powered-habit-tracker-app/issues)
- Email: codingninjarupesh@gmail.com

## 🙏 Acknowledgments

- Google Gemini AI for powerful AI insights
- MongoDB for robust database solutions
- React and Express communities for excellent frameworks
- Tailwind CSS for beautiful styling utilities

---

**Made with ❤️ by [Rupesh Pradhan](https://github.com/RupeshPradhan33)**
