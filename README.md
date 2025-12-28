# 🍽️ StreetServe

StreetServe is a real-time pre-ordering platform designed for street-food vendors and customers. Customers can place orders before reaching the stall, while vendors receive instant order updates—reducing queues, wait times, and operational stress.
This project focuses on digitizing informal food vendors with minimal learning effort, using modern web technologies and real-time cloud services.

---

## 🚀 Features

### 👨‍🍳 Vendor
- Phone OTP authentication
- Menu management (add/update items)
- Real-time incoming orders
- Order status updates (Pending → Preparing → Ready)
- Hands-free order awareness (future TTS integration)

### 🧍 Customer
- Email & password authentication
- Browse nearby vendors
- View vendor menus
- Place pre-orders
- Track order status in real time

---

## 🧠 Tech Stack

- **Frontend:** React (Vite)
- **Backend:** Firebase
  - Firebase Authentication
  - Cloud Firestore
  - Firebase Hosting
- **Realtime Updates:** Firestore snapshot listeners
- **Architecture:** Role-based access (Vendor / Customer)

---

## 🗂️ Firestore Data Model

