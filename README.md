# 🤖 AI Chatbot

A conversational AI chatbot built with **React** and **Vite** — fast, lightweight, and ready to chat.

---

## ✨ Features

- 💬 Real-time chat interface with a clean, responsive UI
- ⚡ Blazing-fast development with Vite's Hot Module Replacement (HMR)
- 🧠 Powered by an AI backend for intelligent responses
- 📱 Responsive design that works across devices

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend Framework | [React](https://react.dev/) |
| Build Tool | [Vite](https://vitejs.dev/) |
| Language | JavaScript |
| Styling | CSS |
| Linting | ESLint |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Mona-Agrawall/ai-chatbot-.git
cd ai-chatbot-

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env
# Edit .env and add your API key(s)

# 4. Start the development server
npm run dev
```

The app will be running at `http://localhost:5173`.

### Build for Production

```bash
npm run build
npm run preview
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root of the project. Example:

```env
VITE_API_KEY=your_api_key_here
```

> ⚠️ Never commit your `.env` file. It is already included in `.gitignore`.

---

## 📁 Project Structure

```
ai-chatbot-/
├── public/           # Static assets
├── src/
│   ├── components/   # React components
│   ├── App.jsx       # Root component
│   └── main.jsx      # Entry point
├── .env              # Environment variables (not committed)
├── index.html        # HTML entry point
├── vite.config.js    # Vite configuration
└── package.json
```

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📄 License

This project is open source. Feel free to use and modify it for your own purposes.

---

## 👩‍💻 Author

**Mona Agrawal** — [@Mona-Agrawall](https://github.com/Mona-Agrawall)
