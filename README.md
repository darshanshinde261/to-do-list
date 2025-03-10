### Features

- Task Management - Add, view, prioritize, and delete tasks.
-  Task Scheduling - Assign tasks to specific days.
-   Persistent Storage - Uses local storage for data retention.
-  User Authentication - Mock authentication using Redux.
-  Dark Mode Support - Toggle between light and dark themes.
-   Graphical Representation - View completed vs. pending tasks using Recharts.

### Setup Instructions
- lone the Repository
```
  git clone YOUR_REPOSITORY_URL
  cd YOUR_PROJECT_FOLDER
```

- Install Dependencies
```
  npm install
```
- Install Additional Packages
```
  npm install redux react-redux @reduxjs/toolkit tailwindcss recharts
```

- Configure Tailwind CSS
  Run the Tailwind setup command:
  ```
    npx tailwindcss init -p
  ```

- Then update tailwind.config.js:
```
  /** @type {import('tailwindcss').Config} */
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

- Update src/index.css:
```
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```
- Start the Development Server
```
npm run dev
```

- Build & Deploy : For production build
```
  For production build
```
- For deployment (Netlify/Vercel), push your code to GitHub and follow the deployment steps on the respective platforms
