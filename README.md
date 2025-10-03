# To-do-List
# React To-Do List

[![React](https://img.shields.io/badge/React-18-blue?logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5-brightgreen?logo=vite)](https://vitejs.dev/)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A simple and intuitive To-Do List application built with **React**. Keep track of your tasks, mark them as completed, and stay organized.

## 🚀 Features

- Add, edit, and delete tasks  
- Mark tasks as completed or pending  
- Responsive design for desktop and mobile  
- Persistent tasks using browser local storage  
- Built with modern React (Hooks & functional components)  

## 🛠 Tech Stack

- **Frontend:** React 18, Vite  
- **State Management:** React Hooks (`useState`, `useEffect`)  
- **Styling:** CSS / Tailwind CSS (optional)  
- **Deployment:** GitHub Pages or any static hosting  

## ⚡ Installation

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

## :star: 2.Install dependencies


```bash
npm install
```
## 3:start development

```bash
npm run dev
```

### Deploy to GitHub Pages:
1.Install gh-pages if not installed:
```bash
npm install gh-pages --save-dev
```
2.Add deployment scripts in package.json
```sCRIPTS
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```
3.Run Deployement
```bash
npm run deploy
```
⭐ Make sure the base in vite.config.js matches your repository name:
base: '/<your-repo-name>/'


## Project Structure

```
react-todo/
├── public/
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── vite.config.js
├── package.json
└── README.md
```

🙌 Contributing

1.Fork the repository

2.Create a new branch (git checkout -b feature/YourFeature)

3.Make your changes and commit (git commit -m "Add feature")

4.Push to the branch (git push origin feature/YourFeature)

5.Open a Pull Request

## 📄 License

This project is open-source and available under the **MIT License**.
See the [LICENSE](LICENSE.txt) file for more info.

