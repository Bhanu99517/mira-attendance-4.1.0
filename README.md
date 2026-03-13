# 🎓 Mira Attendance

> **v4.1.0** — AI-powered attendance management web app built with React, TypeScript, and Vite.

[![TypeScript](https://img.shields.io/badge/TypeScript-98%25-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Built%20with-Vite-646CFF?logo=vite)](https://vitejs.dev/)
[![Gemini AI](https://img.shields.io/badge/AI-Gemini-4285F4?logo=google)](https://ai.google.dev/)

---

## ✨ Features

- **AI-Powered Insights** — Integrates Google Gemini API for intelligent attendance analysis and summaries
- **Attendance Tracking** — Mark, view, and manage attendance records for students or team members
- **Responsive UI** — Clean, mobile-friendly interface built with React and TypeScript
- **Fast Build** — Powered by Vite for a snappy development and production experience
- **Type-Safe Codebase** — Fully typed with TypeScript across components, services, and data models

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React + TypeScript | Frontend UI |
| Vite | Build tool & dev server |
| Google Gemini API | AI-powered features |

---

## 📦 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- A [Google Gemini API key](https://ai.google.dev/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Bhanu99517/mira-attendance-4.1.0.git
   cd mira-attendance-4.1.0
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file in the root of the project:
   ```env
   VITE_GEMINI_API_KEY=your_gemini_api_key_here
   ```

   > ⚠️ **Never commit your API key to version control.** The `.env.local` file is already listed in `.gitignore`.

4. **Start the development server**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:5173`

---

## 🏗️ Project Structure

```
mira-attendance-4.1.0/
├── components/          # Reusable UI components
├── App.tsx              # Root application component
├── components.tsx       # Additional component definitions
├── constants.tsx        # App-wide constants
├── geminiClient.ts      # Google Gemini API client setup
├── services.ts          # Business logic & API service layer
├── types.ts             # TypeScript type definitions
├── index.html           # HTML entry point
├── vite.config.ts       # Vite configuration
├── tsconfig.json        # TypeScript configuration
└── package.json         # Project dependencies & scripts
```

---

## ☁️ Deploying to Vercel

1. Push your code to GitHub
2. Import the repository at [vercel.com](https://vercel.com)
3. Add the environment variable in Vercel's project settings:
   - **Key:** `VITE_GEMINI_API_KEY`
   - **Value:** your Gemini API key
4. Click **Deploy**

> ⚠️ The `VITE_GEMINI_API_KEY` **must** be configured in Vercel's Environment Variables dashboard — not just in your local `.env.local` — for AI features to work in production.

---

## 🔑 Environment Variables

| Variable | Required | Description |
|---|---|---|
| `VITE_GEMINI_API_KEY` | ✅ Yes | Your Google Gemini API key for AI features |

---

## 📜 Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start local development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build locally |

---

## 🔄 Version History

| Version | Notes |
|---|---|
| **4.1.3** | Added PWA support, `src/` restructure, migration scripts |
| **4.1.0** | Stable Gemini AI integration, full TypeScript rewrite |

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 👤 Author

**Bhanu** — [@Bhanu99517](https://github.com/Bhanu99517)

---

*Built with ❤️ using React, TypeScript, and Vite*
