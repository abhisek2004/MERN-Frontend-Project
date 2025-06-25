# 🌐 Environment Details

## Software

- Node.js v18+
- npm v9+
- React 18
- Bootstrap 5

## Tools

- VS Code
- Git
- React Developer Tools

## Project Structure

```
MERN-Frontend-Project/
│
├── public/                # Static files (index.html, favicon, etc.)
│
├── src/                   # Source code
│   ├── assets/            # Images, fonts, and other static assets
│   ├── components/        # Reusable React components
│   ├── pages/             # Page-level React components (routes/views)
│   ├── hooks/             # Custom React hooks
│   ├── utils/             # Utility functions and helpers
│   ├── services/          # API calls and external services
│   ├── context/           # React context providers
│   ├── App.js             # Main app component
│   ├── index.js           # Entry point for React
│   └── ...                # Other feature folders or files
│
├── .env                   # Environment variables
├── .gitignore             # Git ignore rules
├── package.json           # Project metadata and dependencies
├── README.md              # Project overview and instructions
├── CONTRIBUTING.md        # Contribution guidelines
└── ENVIRONMENT.md         # Environment and setup details
```

**Notes:**

- All React code lives in the `src/` directory.
- Place images and static assets in `src/assets/`.
- Organize components by feature or type in `src/components/`.
- Use `src/pages/` for route-level components (e.g., Home, About, Dashboard).
- API logic should go in `src/services/`.
- Store custom hooks in `src/hooks/`.
- Use `src/context/` for global state management with React Context.
- Environment variables (like API URLs) go in the `.env`
