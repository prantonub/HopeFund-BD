# 🌍 Smart Donation Platform

A **region-specific online donation system** built with Firebase Authentication. 
This platform enables users to donate securely, track their donation history, and 
support multiple causes through a simple, user-friendly interface.

---

## 🚀 Features

- 🔐 **Secure Authentication** using Firebase (Email/Password + Google Sign-In).  
- 🎯 **Cause-Specific Donations** – donate directly to different causes.  
- ✅ **Input Validation** – ensures valid donation amounts within available balance.  
- 💳 **Real-Time Balance Updates** – donation amount deducted from main balance and credited to selected cause.  
- 📜 **Donation History Tracking** – view past donations for each cause.  
- 💡 **Interactive UI** – DaisyUI-powered modals for confirmation and history popups.  
- 🗂️ **LocalStorage Integration** – temporary transaction tracking for smooth user experience.  

---

## 🛠️ Technologies & Tools Used

- **Frontend:** HTML, Tailwind CSS, JavaScript  
- **Authentication:** Firebase Authentication (Email/Password + Google)  
- **UI Components:** [DaisyUI](https://daisyui.com/) Modals  
- **Data Storage:** LocalStorage  

---

## 📌 Step-by-Step Workflow

1. User securely **signs up or logs in** using Firebase Authentication.  
2. Donor **selects a cause** to contribute to.  
3. **Validation checks** ensure the donation amount is valid and within the available balance.  
4. On confirmation:  
   - The donation amount is **deducted from the main balance**.  
   - The selected **cause balance increases**.  
5. A **confirmation popup** (DaisyUI modal) displays donation success details.  
6. **Donation history** is updated and can be viewed via a modal for each cause.

---

## 🔮 Future Improvements

💾 Cloud Database Integration – move from LocalStorage to MongoDB for persistent donation records.
📊 Admin Dashboard – manage causes, track donations, and view analytics.
💳 Payment Gateway Support – integrate Stripe, PayPal, or regional gateways (bKash/Nagad).
📩 Email Notifications – send donors confirmation and updates automatically.
📱 PWA & Mobile-Friendly UI – responsive design with offline access and app-like experience.
