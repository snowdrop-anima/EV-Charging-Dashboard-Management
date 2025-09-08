# ⚡ EV Charging Station Admin Dashboard
  1. An interactive web-based admin dashboard for managing EV battery charging stations.
  2. Built using HTML, TailwindCSS, Firebase (Auth + Firestore), this dashboard enables real-time monitoring, battery management, and charging analytics.

## 🚀 Features:-

## 📊 Dashboard Overview
  Displays total batteries, battery types, and available charging slots.

## 🔋 Battery Management
  1. Deposit new batteries into the system.
  2. Monitor status: in-station, charging, ready, withdrawn.
  3. Tracks cycles, health score, and system recommendations.
  4. Withdraw or delete batteries with confirmation modals.

## ⚡ Charging Stations
  1. Two station types supported: Type A & Type B.
  2. Real-time slot visualization with charging progress animations.

## 🔐 Authentication
  Anonymous or custom Firebase authentication supported.

## 🔄 Realtime Updates
  Powered by Firebase Firestore onSnapshot listeners.
  Battery health analysis simulated with machine-learning logic.

## 🛠️ Tech Stack:-
  1. Frontend: HTML, Tailwind CSS, JavaScript (ES Modules)
  2. Backend (Cloud): Firebase Authentication + Firestore Database
  3. Animations/Styling: Tailwind + Custom CSS

### ⚙️ Setup & Installation:-

1. Clone the repository
  git clone https://github.com/snowdrop-anima/EV-Charging-Dashboard-Management.git
  cd EV-Charging-Dashboard-Management

2. Open the ev.html file in your browser.
  (No server required — runs directly in browser with Firebase connection)

3. Configure Firebase
   Replace the placeholder Firebase config inside <script type="module"> with your own from the Firebase Console:
    const firebaseConfig = {
        apiKey: "YOUR_API_KEY",
        authDomain: "YOUR_APP.firebaseapp.com",
        projectId: "YOUR_PROJECT_ID",
        storageBucket: "YOUR_APP.appspot.com",
        messagingSenderId: "YOUR_SENDER_ID",
        appId: "YOUR_APP_ID"
    };
