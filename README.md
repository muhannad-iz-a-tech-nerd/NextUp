# NextUp

# Project Summary
The **NextUp Learning Platform** provides a comprehensive educational experience across various disciplines, including AI, Digital Art, App Development, and Web Development. Each main course consists of ten detailed sub-courses, enhancing users' skills through structured learning paths. The platform features an intuitive user interface, an AI-powered course recommendation system, and now includes a study chatbot and user profile system to personalize the learning experience.

# Project Module Description
- **Main Navigation**: Allows users to navigate between courses and sub-courses.
- **Course Listings**: Displays main courses with descriptions and icons.
- **Sub-Course View**: Detailed view of individual sub-courses, including lessons and prerequisites.
- **Recommendations Panel**: Suggests courses based on user interactions and preferences.
- **Learning Dashboard**: Tracks user activity and displays statistics.
- **Study Chatbot**: Provides personalized study tips, motivation, and course recommendations based on user context.
- **User Profile System**: Enables users to create profiles to track learning goals, preferences, and progress.

# Directory Tree
```
shadcn-ui/
├── README.md                  # Project documentation
├── components.json            # Component metadata
├── eslint.config.js           # ESLint configuration
├── index.html                 # Main HTML file
├── package.json               # Project dependencies and scripts
├── postcss.config.js          # PostCSS configuration
├── public/
│   ├── favicon.svg            # Favicon for the application
│   └── robots.txt             # Robots.txt for SEO
├── src/
│   ├── App.css                # Global styles
│   ├── App.tsx                # Main application component
│   ├── components/
│   │   ├── chatbot/           # Chatbot components
│   │   ├── courses/           # Course-related components
│   │   ├── dashboard/         # Dashboard components
│   │   ├── navigation/        # Navigation components
│   │   └── profile/           # User profile components
│   ├── data/
│   │   ├── coursesDataStructure.ts # Course data structure
│   │   ├── studyChatbotKnowledge.ts # Chatbot knowledge base
│   │   └── userProfileDataStructure.ts # User profile data models
│   ├── hooks/                 # Custom hooks
│   ├── lib/                   # Utility functions
│   ├── pages/                 # Page components
│   ├── utils/                 # Utility functions for recommendations and profile management
│   └── vite-env.d.ts          # TypeScript environment definitions
├── tailwind.config.ts         # Tailwind CSS configuration
├── template_config.json       # Template configuration
├── tsconfig.app.json          # TypeScript configuration for app
├── tsconfig.json              # Base TypeScript configuration
├── tsconfig.node.json         # TypeScript configuration for Node
└── vite.config.ts             # Vite configuration
```

# File Description Inventory
- **README.md**: Provides project overview and setup instructions.
- **index.html**: Entry point for the web application.
- **App.tsx**: Main application logic and routing.
- **coursesDataStructure.ts**: Defines course and sub-course data structures.
- **studyChatbotKnowledge.ts**: Contains knowledge base for the chatbot.
- **userProfileDataStructure.ts**: Defines user profile data models.
- **userProfileManager.ts**: Manages user profile logic.
- **studyChatbotLogic.ts**: Implements the chatbot conversation logic.
- **MainNavigationHeader.tsx**: Navigation header component.
- **MainCoursesGrid.tsx**: Displays main courses in a grid layout.
- **SubCoursesListView.tsx**: Lists sub-courses for a selected main course.
- **CourseDetailView.tsx**: Detailed view of a selected sub-course.
- **RecommendationsPanel.tsx**: Shows personalized course recommendations.
- **LearningDashboardStats.tsx**: Displays user activity statistics.
- **UserProfileCreationModal.tsx**: Modal for creating user profiles.
- **UserProfileDisplayCard.tsx**: Displays user profile information.
- **StudyChatbotInterface.tsx**: Main interface for the study chatbot.
- **ChatbotFloatingButton.tsx**: Floating button to access the chatbot.

# Technology Stack
- **React**: Frontend library for building user interfaces.
- **TypeScript**: Superset of JavaScript for type safety.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Vite**: Build tool for faster development.
- **LocalStorage**: For storing user interactions and data.

