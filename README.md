# Calorie Tracker

Calorie Tracker is a web application developed with React, TypeScript, and TailwindCSS. The application allows users to log their activities and meals, calculate consumed and burned calories, and visualize the total calorie balance. It uses useReducer for state management and stores data in LocalStorage for persistence.

## Features

- **Project Initialization**
  - Set up the project structure and initialized the project.
  - Installed and configured TailwindCSS.

- **User Interface**
  - Created the main containers and input form for data entry.
  - Implemented form validation and state management for activities.

- **State Management**
  - Developed useReducer functions for handling actions such as adding, updating, and deleting activities.
  - Utilized TypeScript for defining event types and activity types.

- **Activity Management**
  - Added functionalities to list activities and meals.
  - Included editing and deletion of activities.
  - Implemented unique ID generation for activities.

- **Data Persistence**
  - Stored activities in LocalStorage.
  - Created actions to reset the app and clear stored data.

- **Calorie Calculation**
  - Calculated and displayed total calories consumed and burned.
  - Showed the differential of calories.

## Getting Started

To get started with the project, clone the repository and follow the installation steps below.

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repo:
   ```sh
   git clone https://github.com/yourusername/calorie-tracker.git

2.Install NPM packages:
npm install

# Usage
To run the project locally:
npm run dev

# Contributing
Contributions are what make the open-source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

# Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
License
Distributed under the MIT License. See LICENSE for more information.

# Contact
Your Name - @your_twitter - your_email@example.com

Project Link: https://github.com/yourusername/calorie-tracker

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list