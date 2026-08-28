<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00e5ff&height=200&section=header&text=PlantDoc%20AI&fontSize=60&fontColor=ffffff&animation=fadeIn" />
  
  <p><strong>An Intelligent Botanical Assistant Powered by Google Gemini AI</strong></p>
  
  <p>
    <a href="https://ais-pre-55wgtp7huqoju3mm547tss-90758329965.asia-southeast1.run.app" target="_blank">
      <img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-Test%20App-success?style=for-the-badge&logo=vercel">
    </a>
  </p>
</div>

---

## 📖 Overview

**PlantDoc AI** is a production-ready, full-stack progressive web application (PWA) designed to bridge the gap between advanced artificial intelligence and practical botany. By leveraging the power of **Google Gemini API**, it provides users with real-time plant diagnostics, context-aware chatting, and personalized garden management.

This project was built with a focus on modern UI/UX principles, strict type safety, and scalable cloud architecture.

### ✨ Key Features

- 🧠 **Zero-Shot AI Context Transitions:** Powered by Google Gemini, the app seamlessly transitions between analyzing uploaded plant images to providing continuous conversational support without losing context.
- 🔐 **Role-Based Access Control (RBAC):** Secure authentication managed by Firebase Auth, featuring an exclusive, hidden **Admin Panel** accessible only to authorized developer credentials.
- 💳 **Monetization & Gamification Ready:** Built-in logic for a tiered "Free Plan" system with automated scanning quotas, paving the way for premium subscriptions.
- 🎨 **Premium UI/UX:** A sleek, neon-dark themed interface built with Tailwind CSS, ensuring a high-end visual experience across all devices.
- 💾 **Cloud Persistence:** Seamlessly integrates with Firebase Firestore to securely store user scan histories and gamification progress in real-time.

---

## 🛠️ Tech Stack & Architecture

This application is built on a robust, modern technology stack:

- **Frontend:** React 18, TypeScript, Tailwind CSS, Vite
- **Backend/BaaS:** Firebase (Authentication, Firestore Database)
- **AI Engine:** Google `@google/genai` SDK (Gemini Models)
- **Icons & UI Elements:** Lucide React

*Architectural Note: Sensitive operations and API Keys are securely managed using environment variables, ensuring the Gemini AI token is never exposed to the client-side bundle in a production environment.*

---

## 🚀 Getting Started

To run this project locally on your machine, follow these steps:

### 1. Prerequisites
Ensure you have **Node.js** (v18+) and **npm** installed on your system. You will also need active API keys for Firebase and Google Gemini.

### 2. Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/Marlius80/PlantDoc-AI.git
cd PlantDoc-AI
npm install
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
# Server-side Gemini API Key
GEMINI_API_KEY=your_gemini_api_key
npm run dev
