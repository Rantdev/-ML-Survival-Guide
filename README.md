agile-project-management/
│
├── server/                         # Backend application
│   ├── config/
│   │   ├── db.js                   # Database connection
│   │   └── env.js                  # Environment validation
│   │
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── projectController.js
│   │   ├── storyController.js
│   │   ├── taskController.js
│   │   ├── teamController.js
│   │   ├── chatController.js
│   │   ├── performanceController.js
│   │   ├── profileController.js
│   │   ├── emailController.js
│   │   └── otpController.js
│   │
│   ├── middleware/
│   │   ├── auth.js
│   │   ├── errorHandler.js
│   │   └── validation.js
│   │
│   ├── models/
│   │   └── initDB.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   ├── projectRoutes.js
│   │   ├── storyRoutes.js
│   │   ├── taskRoutes.js
│   │   ├── teamRoutes.js
│   │   ├── chatRoutes.js
│   │   ├── performanceRoutes.js
│   │   ├── profileRoutes.js
│   │   └── otpRoutes.js
│   │
│   ├── jobs/
│   │   └── reminderJob.js
│   │
│   ├── .env
│   ├── .env.example
│   ├── package.json
│   ├── package-lock.json
│   ├── app.js
│   └── server.js
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
│   └── agile.db
│
├── docs/
│   ├── api-docs.md
│   ├── architecture.md
│   └── schema.md
│
├── .gitignore
├── README.md
├── LICENSE
└── package.json
