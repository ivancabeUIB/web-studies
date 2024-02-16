# React and Astro Installation Guide for Windows

This guide will walk you through the steps to set up a new project using React and Astro on a Windows machine.

## Prerequisites

Before you begin, ensure that you have the following tools installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

## Create a New Astro Project with React

1. Open your terminal and run the following command to create a new Astro project with the React template:

   ```bash
   npx create-astro my-react-astro-app --template astro-react
1. Navigate to the project directory:

bash
Copy code
cd my-react-astro-app

2. Install project dependencies:

bash
Copy code
npm install

## Start the Development Server
Run the following command to start the development server:

npm run dev

## This will launch your Astro application. You can access it at http://localhost:3000 by default.

Additional Configuration (if needed)
If you encounter any issues or want to customize your setup, you may need to modify the astro.config.mjs file in the project root. Ensure that the jsx property is set to 'react'.

export default {
  // ...other configurations...
  jsx: 'react',
};

