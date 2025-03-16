# 🃏 Blackjack Game 🏆

A React-based Blackjack game designed as a project to practice DevOps skills. This game follows standard Blackjack rules, allowing players to hit, stand, and compete against a dealer. It integrates CI/CD, testing, and monitoring tools for a complete development workflow.

## ✨ Features
- 🎨 **React-based UI** – Interactive and responsive interface.
- 🎭 **Tailwind CSS** – Modern styling with utility classes.
- 🃏 **Game Mechanics** – Standard Blackjack rules (hit, stand, bust, dealer logic).
- ✅ **Jest Testing** – Comprehensive test suite to ensure game logic works correctly.
- 🐳 **Dockerized Setup** – Containerized application for consistent development and deployment.
- 🚀 **Vercel Deployment** – Hosted with Vercel for fast and easy access.
- 🔍 **Sentry Integration** – Error tracking and monitoring.
- 📊 **Test Coverage & Reporting** – Automated test coverage reports saved as an artifact.
- 🔄 **CI/CD Pipeline** – Automated deployment and testing.

## 🛠 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/daniellem62/devops-project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd devops-project
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## 🧪 Running Tests
Run Jest tests with:
```bash
npm test
```
To generate a test coverage report:
```bash
npm run test:coverage
```

## 🐳 Docker Setup
To build and run the app in a Docker container:
```bash
docker build -t devops-project .
docker run -p 3000:3000 devops-project
```

## 🚀 Deployment
The game is deployed on Vercel. Pushes to the `main` branch trigger an automatic deployment.

## 🔮 Future Enhancements
- 🎮 Multiplayer mode.
- 🏦 Improved dealer AI.
- 🏆 Score tracking with a leaderboard.

## 🤝 Contributing
Feel free to fork the repository and submit pull requests for improvements.

## 📜 License
This project is licensed under the MIT License.

---
Enjoy the game and happy coding! 🃏🎉


