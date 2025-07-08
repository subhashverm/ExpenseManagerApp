# 💸 Expense Manager App – UPI SMS Parsing + Firebase + Jetpack Compose

A smart Android Expense Tracking App built using **Jetpack Compose**, **Firebase**, and **UPI SMS Parsing**.  
Track your expenses automatically by reading UPI SMS, manage them manually, and view insightful charts & summaries — all with a beautiful UI!

---

## 📱 Features

✅ **Auto UPI SMS Parsing** (GPay, Paytm, PhonePe, BHIM)  
✅ **Manual Expense Add/Edit/Delete**  
✅ **Firebase Auth (Email/Password login)**  
✅ **Firestore Database Integration**  
✅ **Live Transaction History (RecyclerView / LazyColumn)**  
✅ **Dashboard Pie Chart with Category Filters**  
✅ **Group Expense Split (like Splitwise)**  
✅ **Jetpack Compose UI with Navigation**  
✅ **Room Database for offline support**  
✅ **Material 3 + Responsive UI**

---

## 🧩 Tech Stack

| Layer         | Technology                          |
|---------------|-------------------------------------|
| Language      | Kotlin                              |
| UI            | Jetpack Compose, Material 3         |
| Architecture  | MVVM + Repository Pattern           |
| Auth & DB     | Firebase Authentication, Firestore |
| Local Storage | Room Database, SharedPreferences    |
| SMS Parsing   | BroadcastReceiver + SMS Filter      |
| Charting      | MPAndroidChart (or equivalent)      |

---

## 📷 Screenshots

| Home | Add Expense | Dashboard |
|------|-------------|-----------|
| ![home](https://github.com/subhashverm/ExpenseManagerApp/blob/98c0aac83280f2bfb1a729630f5a3a57a8d76507/login%20%20.jpg) | ![add](screenshots/add.png) | ![chart](screenshots/chart.png) |

> *(Upload your actual screenshots in `screenshots/` folder)*

---

## 🛠 How It Works

- **SMS Listener** reads new UPI messages in background
- **SMS Parser** filters valid transactions and extracts amount, sender, and category
- **Auto-save** to Firebase Firestore in real-time
- **Manual entries** allowed via custom form screen
- **Charts** show daily/monthly expenses with filtering
- **Group Expenses** sync with friends for shared costs

---

## 📁 Folder Structure

