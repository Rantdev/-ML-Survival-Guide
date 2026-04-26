## 📂 Project Structure

```bash
agile-project-management/
│
├── server/                         # Backend application
│   ├── config/
│   │   ├── db.js                   # Database connection
│   │   └── env.js                  # Environment validation
│   │
│   ├── controllers/
│   │   ├── authController.js       # Authentication logic
│   │   ├── projectController.js    # Project CRUD operations
│   │   ├── storyController.js      # Story management
│   │   ├── taskController.js       # Task management
│   │   ├── teamController.js       # Team member management
│   │   ├── chatController.js       # Real-time chat
│   │   ├── performanceController.js# Analytics & reports
│   │   ├── profileController.js    # User profile management
│   │   ├── emailController.js      # Email notifications
│   │   └── otpController.js        # OTP verification
│   │
│   ├── middleware/
│   │   ├── auth.js                 # JWT verification
│   │   ├── errorHandler.js         # Global error handling
│   │   └── validation.js           # Input validation
│   │
│   ├── models/
│   │   └── initDB.js               # Database schema initialization
│   │
│   ├── routes/
│   │   ├── authRoutes.js           # Authentication endpoints
│   │   ├── projectRoutes.js        # Project endpoints
│   │   ├── storyRoutes.js          # Story endpoints
│   │   ├── taskRoutes.js           # Task endpoints
│   │   ├── teamRoutes.js           # Team endpoints
│   │   ├── chatRoutes.js           # Chat endpoints
│   │   ├── performanceRoutes.js    # Analytics endpoints
│   │   ├── profileRoutes.js        # Profile endpoints
│   │   └── otpRoutes.js            # OTP endpoints
│   │
│   ├── jobs/
│   │   └── reminderJob.js          # Daily overdue task reminder
│   │
│   ├── .env                        # Environment variables
│   ├── .env.example                # Example environment variables
│   ├── package.json                # Dependencies
│   ├── package-lock.json           # Lock file
│   ├── app.js                      # Express app configuration
│   └── server.js                   # Server entry point
│
├── client/                         # Frontend application
│   ├── public/
│   │   └── vite.svg
│   │
│   ├── src/
│   │   ├── assets/
│   │   │   └── logo.svg
│   │   │
│   │   ├── components/
│   │   │   ├── Layout/
│   │   │   │   ├── Sidebar.jsx
│   │   │   │   ├── Navbar.jsx
│   │   │   │   └── ProtectedRoute.jsx
│   │   │   │
│   │   │   ├── Projects/
│   │   │   │   ├── ProjectCard.jsx
│   │   │   │   └── ProjectModal.jsx
│   │   │   │
│   │   │   ├── Stories/
│   │   │   │   ├── StoryCard.jsx
│   │   │   │   └── StoryModal.jsx
│   │   │   │
│   │   │   ├── Tasks/
│   │   │   │   ├── TaskCard.jsx
│   │   │   │   ├── TaskBoard.jsx
│   │   │   │   └── TaskModal.jsx
│   │   │   │
│   │   │   ├── Chat/
│   │   │   │   ├── ChatBox.jsx
│   │   │   │   └── ChatMessage.jsx
│   │   │   │
│   │   │   ├── Performance/
│   │   │   │   ├── StatsCard.jsx
│   │   │   │   ├── TaskChart.jsx
│   │   │   │   └── Leaderboard.jsx
│   │   │   │
│   │   │   └── Common/
│   │   │       ├── LoadingSpinner.jsx
│   │   │       ├── ConfirmDialog.jsx
│   │   │       └── Toast.jsx
│   │   │
│   │   ├── pages/
│   │   │   ├── Login.jsx
│   │   │   ├── Register.jsx
│   │   │   ├── OTPVerification.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   ├── Projects.jsx
│   │   │   ├── ProjectDetails.jsx
│   │   │   ├── StoryTasks.jsx
│   │   │   ├── MyTasks.jsx
│   │   │   ├── Team.jsx
│   │   │   ├── Performance.jsx
│   │   │   ├── Profile.jsx
│   │   │   └── RoleSetup.jsx
│   │   │
│   │   ├── context/
│   │   │   └── AuthContext.jsx
│   │   │
│   │   ├── hooks/
│   │   │   ├── useAuth.js
│   │   │   ├── useToast.js
│   │   │   └── useLocalStorage.js
│   │   │
│   │   ├── services/
│   │   │   └── api.js
│   │   │
│   │   ├── utils/
│   │   │   ├── constants.js
│   │   │   ├── helpers.js
│   │   │   └── validators.js
│   │   │
│   │   ├── styles/
│   │   │   └── global.css
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── .env
│   ├── .env.example
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── tailwind.config.js
│   ├── postcss.config.js
│   └── vite.config.js
│
├── database/
│   └── agile.db                   # SQLite database
│
├── docs/
│   ├── api-docs.md                # API documentation
│   ├── architecture.md            # Architecture docs
│   └── schema.md                  # Database schema
│
├── .gitignore
├── README.md
├── LICENSE
└── package.json
```
