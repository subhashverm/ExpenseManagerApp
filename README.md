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
| ![home](https://github.com/subhashverm/ExpenseManagerApp/blob/3c1613abd21311f7fabe777aa250e0536d97ee63/home%20.jpg) | ![add](https://github.com/subhashverm/ExpenseManagerApp/blob/45ced40eb7b394fdd48d8188a30421df4d71c53f/add%20expense.jpg) | ![chart](https://github.com/subhashverm/ExpenseManagerApp/blob/45ced40eb7b394fdd48d8188a30421df4d71c53f/deshbooard.jpg) | 


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
ExpenseManagerApp/
├── ui/
│ ├── screens/
│ ├── navigation/
│ └── components/
├── data/
│ ├── model/
│ ├── repository/
│ ├── local (Room DB)
│ └── remote (Firestore)
├── utils/
├── auth/
├── MainActivity.kt
└── App.kt
---

## 🔐 Permissions Used

- `RECEIVE_SMS`
- `READ_SMS`
- `INTERNET`
- `ACCESS_NETWORK_STATE`

Open in Android Studio

Add your Firebase google-services.json file

Add required permissions in AndroidManifest.xml

Enable Firestore + Auth in Firebase Console

Run on Android device or emulator

🔗 Live Preview (Optional GIFs)
Auto-read UPI SMS → Save → Show in transaction list

Add manual expense → View in dashboard chart

Edit/Delete → Firestore updates in real-time

✅ Future Scope
Export to CSV

Budget Planning per category

Monthly summary email

Dark mode + Offline sync with Room

👨‍💻 Author
Developed by Subhash Verma
📧 subhash27042004@gmail.com

📜 License
This project is licensed under the MIT License.


