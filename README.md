# ⚡ Units Tracker Pro (Enterprise Edition)
<div align="center">
  <img src="https://img.shields.io/badge/version-v19.8.2_Beta-blue" alt="Version">
  <img src="https://img.shields.io/badge/architecture-Serverless_Single--File-success" alt="Architecture">
  <img src="https://img.shields.io/badge/status-Active-success" alt="Status">
</div>

## 📖 Overview
Units Tracker Pro is a highly advanced, ultra-lightweight, and fully serverless web application designed to track electricity consumption across multiple independent meters. Built for pure utilitarian efficiency, the system operates entirely within the browser while delivering enterprise-grade analytics, precise burn-rate pacing, and sophisticated reporting—all contained within a single portable `index.html` file.

The primary mission of the dashboard is to ensure electricity consumption stays strictly under the **200-unit monthly limit** by projecting end-of-month usage based on live reading telemetry.

## 🚀 Key Features

### 📊 Advanced Predictive Analytics
- **Live Consumption Tracking:** Calculates exact units consumed based on your custom baseline reading.
- **Predictive Engine:** Analyzes current usage velocity to forecast your exact Month-End Total.
- **Pacing Metrics:** Displays your "Actual Burn Rate" vs the "Safe Allowed Rate" so you know exactly how many units you can afford to use per day.
- **Visual Alerting:** Real-time color-coded alerts (Green/Yellow/Red) trigger dynamically based on your projected trajectory.

### 🏢 Multi-Meter Architecture
- Seamlessly toggle between **Self Meter** and **Malik Meter** workspaces.
- Both meters maintain 100% isolated state, configurations, and reading logs.

### 💾 Secure Local Persistence
- **No Database Required:** 100% of telemetry and configuration data is persistently stored in the browser's native `localStorage`.
- **Zero Privacy Risk:** Data never leaves the client device. No external API calls, no cloud syncing.

### 📑 Enterprise Export & Reporting
- **Multi-Tab Excel (.xlsx):** Click one button to compile reading histories from *all* meters into a single, beautifully structured Microsoft Excel workbook with multiple tabs.
- **Print-Ready HTML:** Generates an ASCII-style, CSS-stripped document designed specifically for flawless black-and-white A4 printing.
- **JSON Database Backup:** Export your entire raw state tree to a `.json` file for secure cold-storage backups or migration to a new device.

### ⏱️ Precision Logging
- **Live Telemetry Clock:** The dashboard utilizes an integrated live clock algorithm perfectly synced to your local machine timezone to ensure meter readings are recorded with millisecond accuracy.
- **Full Audit Control:** Complete capability to securely Edit or Delete historical reading logs with immediate metric recalculation.

## 🛠️ Technical Stack
- **Core:** HTML5, CSS3, Vanilla JavaScript (ES6)
- **Visualization:** `Chart.js` (via CDN)
- **Data Exportation:** `SheetJS / xlsx` (via CDN)
- **Design System:** Custom responsive flexbox/grid layout optimized for both Desktop monitors and Mobile screens.

## ⚡ Installation & Usage

**Zero Build Process Required.**
1. Download the `index.html` file to your local machine or mobile device.
2. Double-click the file to open it in any modern web browser (Chrome, Edge, Safari, Firefox).
3. Navigate to the **Cycle Config** card to establish your Start Date, End Date, and Baseline Meter Reading.
4. Use the **Log Reading** card to begin inputting telemetry.

## 👥 Author
Developed and maintained by **Naveed Ahmed**.
📧 Contact: [iamnaveed.cs@gmail.com](mailto:iamnaveed.cs@gmail.com)
