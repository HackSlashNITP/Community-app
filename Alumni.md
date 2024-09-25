# Alumni Association Platform Folder Structure

```bash
alumni_association_platform/
│
├── android/                  # Android platform specific files
├── ios/                      # iOS platform specific files
├── lib/                      # Main Flutter codebase
│   ├── components/           # UI components (widgets, buttons, etc.)
│   │   ├── alerts/           # Notification and Alert related components
│   │   ├── donations/        # Donation Portal components
│   │   ├── events/           # Event and Feedback components
│   │   ├── job_portal/       # Networking & Job Portal components
│   │   ├── messaging/        # Direct Messaging components
│   │   ├── profiles/         # Registration & Directory components
│   │   ├── sharing/          # Blogs, Articles components for Content Sharing
│   │   ├── social_media/     # Social Media Integration components (LinkedIn, Google Sign-in)
│   │   ├── surveys/          # Polls and Survey components
│   │   ├── common_widgets.dart  # Reusable widgets across the app
│   │
│   ├── screens/              # Main screens for each feature
│   │   ├── home_screen.dart  # Main Home Screen
│   │   ├── login_screen.dart # Login and Authentication screen
│   │   ├── profile_screen.dart # User Profile and Peer Search screen
│   │   ├── job_portal_screen.dart # Job Search and Posting screen
│   │   ├── events_screen.dart # Event Management and Feedback screen
│   │   ├── donation_screen.dart # Secure Donations screen
│   │   ├── surveys_screen.dart  # Surveys and Polls screen
│   │   ├── messages_screen.dart # Direct Messaging screen
│   │
│   ├── services/             # Business logic, API calls, services
│   │   ├── auth_service.dart  # Firebase Authentication (firebase_auth)
│   │   ├── firestore_service.dart # Firebase Firestore logic (cloud_firestore)
│   │   ├── notification_service.dart # Push notifications (firebase_messaging)
│   │   ├── social_media_service.dart # LinkedIn and Google Sign-in (linkedin_login, google_sign_in)
│   │   ├── donation_service.dart # Secure donations logic (if using payment gateway)
│   │   ├── event_service.dart # Event management logic
│   │   ├── survey_service.dart # Google Forms API integration
│   │
│   ├── models/               # Data models for the app
│   │   ├── user_model.dart    # User profile model
│   │   ├── event_model.dart   # Event model
│   │   ├── job_model.dart     # Job posting model
│   │   ├── message_model.dart # Messaging model
│   │   ├── donation_model.dart # Donation model
│   │   ├── survey_model.dart   # Survey/Poll model
│   │
│   ├── utils/                # Utility functions, constants, theme
│   │   ├── theme.dart        # App theme and colors
│   │   ├── constants.dart    # Constant values
│   │   ├── validators.dart   # Input validation
│   │
│   ├── main.dart             # Main app entry point
│
├── assets/                   # Static assets (images, icons, etc.)
│   ├── images/
│   ├── icons/
│
├── pubspec.yaml              # Flutter dependencies (Firebase, LinkedIn, Google Sign-In, etc.)
└── README.md                 # Project documentation
