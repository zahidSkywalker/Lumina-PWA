# Lumina Pro PWA

<div align="center">

![Lumina Pro](https://img.shields.io/badge/Status-Production-success)
![PWA](https://img.shields.io/badge/PWA-Ready-blue)
![Offline](https://img.shields.io/badge/Offline-First-critical)

A **Modern, Offline-Capable Student Management System** built as a Progressive Web App (PWA). Lumina Pro mimics the look and feel of a native iOS/Android application, complete with user authentication, fee tracking, and GPA analytics, without the need for a backend server.

[View Demo](#) • [Report Bug](#)

</div>

---

## 🌟 Features

Lumina Pro is designed for educators and tutors who need a reliable tool on their tablet or phone.

*   **📱 Native Feel:** Bottom navigation, smooth animations, and "Glassmorphism" design.
*   **🌐 100% Offline First:** Works perfectly without internet. Data is stored locally on your device.
*   **👤 Local Multi-User:** Includes a Login/Register system. Each user has their own isolated account and data.
*   **💰 Financial Tracking:** Automatic calculation of overdue fees based on last payment date (30-day cycles).
*   **📊 Analytics:** Real-time calculation of Average GPA and Student Count.
*   **🚀 Zero Server Costs:** Deployable on Vercel (or GitHub Pages) for free. No Python/Node backend required.

---

## 🛠 Technology Stack

This project uses pure client-side technologies to ensure speed and offline capability.

*   **Frontend:** HTML5, CSS3 (Flexbox/Grid, Variables), Vanilla JavaScript (ES6+).
*   **PWA Standards:** Service Workers (`sw.js`) for caching, Web Manifest for installation.
*   **Database:** Browser `localStorage` (Simulates a database for local storage).
*   **Deployment:** Vercel (Static Site).

---

## 📂 Project Structure

```text
lumina-pro/
├── index.html       # The main app (Logic + UI)
├── manifest.json     # PWA Configuration (Colors, Icons)
├── sw.js           # Service Worker (Offline Logic)
├── icon.png        # App Icon (512x512px required)
└── README.md       # This file
```

---

## 🚀 Installation & Usage

### Option 1: Use Live Demo (If hosted)

1.  Visit the deployed link.
2.  On iOS (Safari) or Android (Chrome): Tap **"Share"** -> **"Add to Home Screen"**.
3.  App is now installed on your phone!

### Option 2: Run Locally

1.  Clone the repository.
    ```bash
    git clone https://github.com/your-username/lumina-pro.git
    ```
2.  Ensure you have an `icon.png` (512x512px) in the root folder.
3.  Open `index.html` in your web browser (Chrome or Safari recommended for PWA support).

### Getting Started

1.  **Create Account:** Open the app. You will be prompted to create a username and password.
2.  **Setup Profile:** Upload a photo (optional) via the camera icon.
3.  **Add Students:**
    *   Go to **Students** tab.
    *   Tap the **+ (FAB)** button.
    *   Enter Name, Roll No, GPA, Fee Amount, and Last Payment Date.
4.  **Check Dues:**
    *   Go to **Home** or **Dues** tab.
    *   Students with overdue payments are highlighted in Red.

---

## ⚠️ Important: Data Limitations

Please read carefully before using for critical data:

1.  **Device Isolation:** Data is stored in the browser's `localStorage`.
    *   If you login as "John" on your Phone, **you will not see** that data when you login as "John" on your Laptop.
    *   Data does **not** sync to the cloud automatically.
2.  **Clearing Data:**
    *   If you clear your browser cache or uninstall the PWA, **your data will be deleted**.
    *   Please use this tool with caution for critical records.
3.  **No Server Reset:** There is no "Forgot Password" feature because there is no server. You will need to create a new account if you lose your password.

---

## 🌐 Deployment to Vercel

This app is designed for free, static hosting.

1.  Push this code to your GitHub repository.
2.  Go to [Vercel.com](https://vercel.com) and click **"Add New Project"**.
3.  Import your GitHub repository.
4.  **Framework Preset:** Select **"Other"** (or leave blank).
5.  Click **Deploy**.

*Note: Since there is no build process, deployment is instant.*

---

## 🤝 Contributing

Contributions are welcome! If you want to add features (like Cloud Sync), please open an issue or submit a Pull Request.

1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👨‍💻 Author

**Zahid** - *Initial Work*

*   GitHub: [@your-username](https://github.com/your-username)
*   Project Link: [https://github.com/your-username/lumina-pro](https://github.com/your-username/lumina-pro)

---

## 🙏 Acknowledgments

*   UI design inspired by modern iOS design guidelines.
*   Icons provided by [FontAwesome](https://fontawesome.com).
*   Fonts by [Google Fonts](https://fonts.google.com/) (Plus Jakarta Sans).
