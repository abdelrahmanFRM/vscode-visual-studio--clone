<<<<<<< HEAD
## ✅ Todor App – Project Summary

**Todor** is a modern, full-featured **Todo Application** built with React and TypeScript. It allows users to manage tasks efficiently through a clean, responsive interface, while using **Strapi CMS** as a powerful backend to store todos and user data (like emails). The app demonstrates best practices in form handling, validation, API integration, and UI accessibility.

---

### 🚀 Tech Stack

* **Frontend**

  * **React** – Building a dynamic user interface
  * **TypeScript** – Type-safe, scalable code
  * **Tailwind CSS** – Utility-first CSS framework for styling
  * **React Router DOM** – SPA navigation
  * **React Hook Form** – Flexible form handling
  * **Yup** – Validation schema for forms
  * **Axios** – HTTP client for API communication
  * **React Query** – Server state management and caching
  * **React Hot Toast** – Toast-based user feedback
  * **@headlessui/react** – Accessible UI components

* **Backend**

  * **Strapi CMS** – Headless CMS to build and manage:

    * Todo items
    * User emails (for personalization or sign-in logic)

---

### ✨ Key Features

* 📝 Create, edit, complete, and delete todo tasks
* 🧠 Real-time API interactions with **React Query + Axios**
* 📬 Email capture and storage via **Strapi CMS**
* 🔐 Form validation using **React Hook Form + Yup**
* 💬 Instant feedback via **React Hot Toast**
* 💅 Mobile-first responsive UI built with **Tailwind CSS**
* 🎨 Accessible UI with components from **Headless UI**
* 🌐 SPA navigation powered by **React Router**

---

### 📁 Project Structure Overview

```
src/
├── components/        # Reusable UI components
├── pages/             # Views for different routes
├── services/          # API logic with Axios and Strapi
├── hooks/             # Custom React hooks
├── validations/       # Yup schemas for validation
├── utils/             # Utility functions/helpers
└── App.tsx            # Main app entry point and routing
```

---

### 🔧 Strapi CMS Integration

* **Content Types**:

  * `Todo`: Stores task title, description, completion status, timestamp
  * `UserEmail`: Stores user email addresses submitted from the app

* **API Integration**:

  * Used **Axios** for requests
  * Managed data with **React Query** for optimal performance and UX
  * Role-based permissions in Strapi used to secure public access

---


Let me know what you’d like next.

=======
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
>>>>>>> 82fa674 (Initial commit:Todo-App)
