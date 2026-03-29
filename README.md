# Tenzies Game 🎲

A fun and interactive Tenzies dice game built with React and Vite. The goal of the game is to roll all the dice until they show the same number. Click each die to freeze it at its current value between rolls.

## 🚀 Getting Started

Follow these steps to run the application locally on your machine.

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed. Node.js comes bundled with npm (Node Package Manager).

### Installation

1. Navigate to your project directory in your terminal:
   ```bash
   cd Tenzies
   ```

2. Install the necessary dependencies:
   ```bash
   npm install
   ```

### Running the App

Start the local development server by running:
```bash
npm run dev
```

Your terminal will display a local URL (usually `http://localhost:5173/`). Open this link in your web browser to play the game!

## 🚀 Deployment

The easiest way to deploy this project is via [Netlify](https://www.netlify.com/).

### Deploying via GitHub
1. Upload your code to a GitHub repository.
2. Log in to [Netlify](https://app.netlify.com/) and click **Add New Site** > **Import an existing project**.
3. Authorize GitHub and select your repository.
4. Netlify will auto-detect Vite. Ensure the settings are:
   - **Build command**: `npm run build`
   - **Publish directory**: `dist`
5. Click **Deploy Site**. In a few minutes, your site will be live!

## 🛠️ Built With
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [nanoid](https://www.npmjs.com/package/nanoid)
- [react-confetti](https://www.npmjs.com/package/react-confetti)

## 📜 Acknowledgements
This project is based on the [Scrimba Frontend Career Path](https://scrimba.com/fullstack-path-c0fullstack).