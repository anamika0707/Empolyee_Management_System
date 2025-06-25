# Employee Management System

A simple Employee Management System built with React and Vite. This project allows an admin to assign tasks to employees and track their progress. Employees can view and update their tasks.

## Features

- Admin and Employee login
- Admin dashboard to create and assign tasks
- Employee dashboard to view and manage tasks
- Task status tracking (new, active, completed, failed)
- Persistent data using localStorage
- Responsive UI styled with Tailwind CSS

## Project Structure

```
Employee-management/
├── public/                # Static assets
├── src/
│   ├── assets/            # Images and icons
│   ├── components/
│   │   ├── Auth/          # Login component
│   │   ├── Dashboard/     # Admin and Employee dashboards
│   │   ├── TaskList/      # Task card components
│   │   └── other/         # Header, CreateTask, AllTask, etc.
│   ├── context/           # AuthProvider for global state
│   ├── utils/             # localStorage helpers
│   ├── App.jsx            # Main app logic
│   ├── main.jsx           # Entry point
│   └── index.css          # Global styles
├── index.html             # HTML template
├── tailwind.config.js     # Tailwind CSS config
├── postcss.config.js      # PostCSS config
├── vite.config.js         # Vite config
├── package.json           # Project metadata and scripts
└── README.md              # Project documentation
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/employee-management.git
   cd Employee-management
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```sh
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

- **Admin Login:**  
  Email: `admin@me.com`  
  Password: `123`

- **Employee Login:**  
  Use one of the emails and password (`123`) from the seeded data in [`src/utils/localStorage.jsx`](src/utils/localStorage.jsx).

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Customization

- Modify employee and admin data in [`src/utils/localStorage.jsx`](src/utils/localStorage.jsx).
- Update styles in [`src/index.css`](src/index.css) or Tailwind config.
