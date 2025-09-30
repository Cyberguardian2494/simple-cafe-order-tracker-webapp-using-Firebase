# ☕ Café Order Tracker

A real-time café order tracking system built with **Firebase Hosting, Firestore, and Firebase Authentication**.  
Customers can view their orders in real time, while baristas can log in to manage and update order statuses.

---

## 🚀 Features
- Customer page (`index.html`) shows live order queue (In Progress + Ready).
- Barista dashboard (`admin.html`) with secure login.
- Orders update in real time using Firestore listeners.
- Firebase Authentication for barista accounts.
- Firestore security rules to separate customer vs barista access.
- Responsive design with background image and optional overlay.

---

## 🗂️ Project Structure
public/ 
index.html # Customer view 
admin.html # Barista dashboard 
firestore.rules # Firestore security rules


---

## 🔧 Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/Cyberguardian2494/simple-cafe-order-tracker-webapp-using-Firebase.git
cd cafe-order-tracker
```
### 2. Install Firebase CLI
```bash
npm install -g firebase-tools
```
### 3. Initialize Firebase
```bash
firebase init
```
and select:
Hosting
Firestore
Use public/ as hosting folder.

### 4. Configure Firebase
Copy your Firebase project config into index.html and admin.html (or firebase-config.js).

### 5. Deploy
```bash
firebase deploy
```







