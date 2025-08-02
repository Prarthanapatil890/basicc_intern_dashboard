project:
  name: "**Intern Rise Portal**"
  description: >
    A clean, full-stack intern dashboard prototype built using **React (Vite)** for the frontend and **Firebase Static** 
  tech_stack:
    frontend: "**React + Vite**"
    backend: "**Firebase Static**"
    hosting:
      frontend: "**Vercel**"
      backend: "**Firebase (Static)**"

live_links:
  frontend: "**[Live Vercel Link]**(https://basicc-intern-dashboard.vercel.app/)

features:
  frontend:
    - "**Login Page** (UI only, no auth)"
    - "**Signup Page** (UI only)"
    - "**Dashboard**"
    - "Intern name display"
    - "Static referral code (e.g., `prarthana2025`)"
    - "Total donations raised (fetched from static backend)"
    - "Static rewards/unlockables section"
    
screenshots:
  - name: "**🔐 Login Page**"
    path: "login.png"
  - name: "**📝 Signup Page**"
    path: "signup.png"
  - name: "**📊 Dashboard**"
    path: "dashboard.png"
  - name: "**🌐 Firebase**"
    path: "backend.png"

project_structure: |
  **Project Structure**
  ──────────────────────────────
  intern-rise-portal/
  ├── public/
  │   └── data.json             # Static backend data hosted on Firebase
  ├── src/
  │   ├── components/           # UI components like Login, Signup
  │   ├── pages/                # App pages (Dashboard, etc.)
  │   ├── App.tsx
  │   ├── main.tsx
  ├── index.html                # App root mount and meta
  ├── vite.config.ts
  ├── README.md
  ├── package.json
  └── screenshots/              # Contains all preview images

getting_started:
  steps:
    - step: "**Clone the Repository**"
      command: |
        git clone https://github.com/Prarthanapatil890/basicc_intern_dashboard.git
        cd basicc_intern_dashboard
    - step: "**Install Dependencies**"
      command: npm install
    - step: "**Run the Project Locally**"
      command: npm run dev
  
deployment:
  frontend:
    platform: "**Vercel**"
    steps:
      - "Connect GitHub repo to Vercel"
      - "Deploy directly from dashboard"
    note: "**No extra setup needed** for frontend—auto-deploy from repo"
  backend:
    platform: "**Firebase Hosting**"
    static: true
    steps:
      - "firebase init"
      - "firebase deploy"
    note: >
      This backend is purely **static**. No database or real-time updates.
      

submission_format:
  - "✅ **Frontend deployed via Vercel**"
  - "✅ **Backend hosted via Firebase**"
  - "✅ **Screenshots placed in and referenced in README**"
  - "✅ **GitHub repo with complete README and deployment guide**"

developer:
  name: "**Prarthana Patil**"
  github: "https://github.com/Prarthanapatil890"
  repo: "https://github.com/Prarthanapatil890/basicc_intern_dashboard"


