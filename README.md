# OG Tasker

OG Tasker is a task management web application built with React and modern frontend tools. The project focuses on creating an efficient, responsive, and user-friendly interface for organizing tasks, tracking progress, and visualizing data. It is designed as a foundation for learning and exploring best practices in React development while also serving as a functional productivity tool.

## Features

* React 18 with concurrent rendering
* Vite as the development server and build tool
* Tailwind CSS for utility-first styling
* React Router v6 for routing
* D3.js and Recharts for data visualization
* React Hook Form for form handling
* Framer Motion for animations
* Jest and React Testing Library for testing

## Prerequisites

* Node.js v14+
* npm or yarn

## Installation

```bash
npm install
# or
yarn install
```

Start development:

```bash
npm run dev
# or
yarn dev
```

Build for production:

```bash
npm run build
```

## Project Structure

```
OG-Tasker/
├── public/             
├── src/
│   ├── components/     
│   ├── pages/          
│   ├── styles/         
│   ├── App.jsx         
│   ├── Routes.jsx      
│   └── index.jsx       
├── .env                
├── index.html          
├── package.json        
├── tailwind.config.js  
└── vite.config.js      
```

## Routes

Example in `Routes.jsx`:

```jsx
import { useRoutes } from "react-router-dom";
import HomePage from "pages/HomePage";
import AboutPage from "pages/AboutPage";

const ProjectRoutes = () => {
  return useRoutes([
    { path: "/", element: <HomePage /> },
    { path: "/about", element: <AboutPage /> },
  ]);
};

export default ProjectRoutes;
```

## Styling

Tailwind CSS with plugins for forms, typography, aspect ratio, container queries, fluid typography, and animations.

## Responsive Design

Built with Tailwind CSS breakpoints to ensure compatibility across devices.

## Acknowledgments

* Team OG
