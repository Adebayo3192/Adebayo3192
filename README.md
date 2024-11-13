attendance-tracker-app/
├── client/                    # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       │   ├── AttendanceScanner.js   # QR/Fingerprint scanner UI
│       │   ├── Notification.js        # Notification component for SMS/Email
│       │   ├── Calendar.js            # Academic Calendar UI
│       │   ├── AttendanceChart.js     # Punctuality and attendance chart
│       │   └── StudentProfile.js      # Student profile management
│       ├── App.js                     # Main React app
│       └── index.js
├── server/                    # Express backend
│   ├── controllers/
│   │   ├── authController.js           # Authentication logic
│   │   ├── attendanceController.js     # Attendance management
│   │   ├── notificationController.js   # Notification (SMS/Email)
│   │   └── calendarController.js       # Academic calendar logic
│   ├── models/
│   │   ├── User.js                     # User model (students/teachers)
│   │   ├── Attendance.js               # Attendance record model
│   │   └── Calendar.js                 # Calendar event model
│   ├── routes/
│   │   ├── authRoutes.js               # Routes for authentication
│   │   ├── attendanceRoutes.js         # Routes for attendance
│   │   ├── notificationRoutes.js       # Routes for notifications
│   │   └── calendarRoutes.js           # Routes for calendar
│   ├── config/
│   │   └── db.js                       # Database connection setup
│   ├── utils/
│   │   ├── fingerprint.js              # Fingerprint API integration
│   │   ├── qrScanner.js                # QR code scanner API integration
│   │   └── excelExport.js              # Excel export functionality
│   ├── app.js                          # Main Express app
│   └── server.js                       # Server configuration and startup
├── .env                                # Environment variables
├── package.json                        # Dependencies and scripts
└── README.md                           # Project documentation
