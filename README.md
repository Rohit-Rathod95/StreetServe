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
-vendors/{vendorId}
└── menu/{itemId}
-customers/{customerId}
-orders/{orderId}
-vendorId
-customerId
-items
-status
-createdAt  

---

## 🔐 Authentication

- Vendors: Phone OTP (Firebase Auth)
- Customers: Email & Password (Firebase Auth)

---

## 🎯 Problem Solved

StreetServe addresses long queues and inefficient ordering at street-food stalls by enabling:
- Advance ordering
- Timed preparation
- Real-time communication between customers and vendors

This improves customer experience and helps vendors manage peak hours more efficiently.

---

## 🛠️ Setup Instructions

1. Clone the repository
2. Install dependencies
3. Create a Firebase project
4. Configure Firebase Authentication and Firestore
5. Add Firebase config to the project
6. Run the app locally

*(Detailed step-by-step setup coming soon)*

---

## 📌 Status

🚧 MVP in progress  
Future improvements:
- Audio alerts using Text-to-Speech
- Location-based ETA triggers
- Firestore security rules hardening
- Deployment on Firebase Hosting

---

## 👨‍💻 Author

Built as a learning-focused, real-world project to explore Firebase, real-time systems, and role-based application design.
