# -E-safepath-ai- 
# 🛡️ SafePath AI

![Live Deployment](https://img.shields.io/badge/Status-Live_on_Vercel-success?style=for-the-badge&logo=vercel)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite_8-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)

**SafePath AI** is a next-generation predictive crime analysis and secure urban navigation platform. Built with a highly responsive, glassmorphic aesthetic, the dashboard merges real-world demographic data with dynamic mapping to intelligently calculate the safest travel routes across high-density cities.

### 🌐 Live Demo
Access the production application securely here: **[https://safepath-ai-beta.vercel.app](https://safepath-ai-beta.vercel.app)**

---

## ✨ Core Features
*   **Intelligent Pathfinding:** Analyzes spatial crime clusters and time-of-day variables to generate the mathematically safest travel trajectories between two coordinates.
*   **Predictive Heatmaps:** A dynamic Canvas-powered rendering engine plots localized crime hotspots using critical real-world subsets.
*   **Real-World Telemetry:** Integrated with authentic **NCRB 2019** dataset metrics locally, utilizing advanced `Recharts` visualizations to chart arrest demographics (juveniles, youth, adults, seniors) securely.
*   **SafePath Copilot:** An intelligent localized AI sidebar widget simulating conversational geospatial memory to provide instant regional security context.
*   **Admin Dashboard:** Role-based secure entryway opening into a system telemetry view tracking continuous active network connections.
*   **Premium Glassmorphism:** Deep mid-night responsive UI architected entirely from scratch via CSS utilizing staggered keyframes and mesh blur filters.

## 🛠️ Technology Stack
*   **Core:** Javascript, HTML5, Vanilla CSS3 (Strict flex/grid logic, no external bloated CSS frameworks).
*   **Libraries:** React DOM 19, Recharts 3.8.
*   **Compiler:** Vite v8.
*   **Architecture:** Entirely Client-Side Rendered (CSR), hosted securely on Vercel's Edge Network.

---

## 🚀 Running SafePath AI Locally

To launch the secure platform on your local environment:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankitadpawar898-png/e-safepath-ai.git
   cd e-safepath-ai
   ```

2. **Install core dependencies:**
   ```bash
   npm install
   ```

3. **Initialize the local Vite satellite:**
   ```bash
   npm run dev
   ```

4. Open `http://localhost:5173` in your browser. (Any valid credentials, e.g., Username: `admin`, will successfully mock authorization into the system).

---

> Note: Current data sets actively injected (`citiesData.js`) are derived from the official *NCRB_CII-2019 Table 19B.2* distribution. The pathfinding algorithms and live threat-predictions are statically modeled abstractions for UX/UI demonstration purposes.
