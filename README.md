# 📄 AI Resume Analyzer / RESUMIND

RESUMIND is a web-based application designed to help job seekers optimize their resumes. By leveraging Artificial Intelligence (AI), the app analyzes uploaded resumes and compares them against specific Job Descriptions to provide an ATS Score, detailed feedback, and actionable improvement tips.

<img width="1920" height="1306" alt="screencapture-localhost-5173-2026-03-08-20_19_34" src="https://github.com/user-attachments/assets/9f745f4e-4fa6-481f-97d8-16ab5f004bc4" />


## ✨ Key Features

- **Seamless PDF Upload:** Supports quick and easy resume uploads in PDF format.
- **Client-side PDF-to-Image Conversion:** Renders PDF pages into images directly in the browser using pdfjs-dist, ensuring high performance without over-leveraging the server.
- **Intelligent AI Analysis:** Integrated AI engine that reads resumes and correlates them with the Company Name, Job Title, and Job Description.
- **Instant Cloud Storage:** Powered by Puter.js for seamless file management (fs) and Key-Value database storage (kv).
- **ATS Scoring & Feedback:** Delivers a detailed breakdown of what is working well and what needs adjustment to bypass HRD/ATS screening filters.
- **Modern UI/UX:** A responsive, elegant, and user-friendly interface built with Tailwind CSS.

## 🛠️ Tech Stack

This application is built using a modern web development stack:

- **Framework:** [React](https://react.dev/) / [React Router v7](https://reactrouter.com/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Backend-as-a-Service (BaaS):** [Puter.js](https://docs.puter.com/) (Menangani Auth, File System, Key-Value Store, dan AI)
- **PDF Processing:** `pdfjs-dist` (Mozilla PDF.js)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Language:** TypeScript & JavaScript

## 🚀 Installation & Getting Started
Follow these steps to run the project locally on your machine.

## Prerequisites
Ensure you have the following installed:
- Node.js (v18.x or later)
- Package manager (npm, yarn, pnpm, or bun)

### Steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Rafifdev/ai-resume-analyzer.git](https://github.com/Rafifdev/ai-resume-analyzer.git)
   cd ai-resume-analyzer
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
   
4. **Start the Development Server:**
   ```bash
   npm run dev
   ```
   
6. **Access the App:**
   Open your browser and navigate to http://localhost:5173.

### 🏗️ Deployment (Produksi)

To create an optimized production build:

```bash
npm run build
```

The build output will be located in the build/ folder. This application supports deployment to Node.js platforms, Vercel, Railway, or via Docker.

### Run via Docker:

```bash
docker build -t ai-resume-analyzer .
docker run -p 3000:3000 ai-resume-analyzer
```

## <p align="center"> Made with ❤️ by <a href="https://www.google.com/search?q=https://github.com/Rafifdev">Rafifdev</a> </p>
