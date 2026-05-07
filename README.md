📊 FinTrack Pro — Offline Expense Tracker

FinTrack Pro is a fully offline-first expense tracking application built using Flutter.
It enables users to track expenses, visualize spending patterns, and manage transactions with a smooth and modern UI — all without internet dependency.

🚀 Features
💰 Expense Tracking
Track total expenses in real time
Auto-updates on add/edit/delete transactions
➕ Transaction Management
Add new transactions
Edit existing transactions
Delete transactions
Category-based expense tracking
Instant UI updates
📊 Data Visualization
Bar chart for spending overview
Visual representation of expense trends
Smooth animations and responsive UI
🧾 Recent Transactions
Displays latest transactions
Clean card-based UI
Shows category, amount, and date
🌗 Dark Mode / Light Mode
Fully supported theme switching
Material 3 design
Persistent theme state
📴 Offline First App
Works completely without internet
All data stored locally (SQLite/Drift/Hive)
Fast and reliable performance
No API or backend dependency
🧱 Architecture
UI Layer
   ↓
State Management (Riverpod / BLoC)
   ↓
Repository Layer
   ↓
Local Database (SQLite / Drift / Hive)
✔ Key Principles
Clean Architecture
Separation of concerns
Reactive UI updates
Modular feature-based structure
💾 Local Storage
Fully offline database
Persistent transaction storage
Fast read/write operations
No network calls
📱 Screens Overview
🏠 Dashboard
Total expense summary
Bar chart visualization
Financial overview
💳 Transactions
List of all transactions
Edit & delete support
Recent activity tracking
➕ Add / Edit Transaction
Add new expense
Modify existing entries
Category + amount input
🎨 UI/UX
Clean modern interface
Smooth animations
Responsive layout
Card-based design
Intuitive navigation
🌙 Theme Support
Light Mode
Dark Mode
System theme support
Smooth transitions
🧰 Tech Stack
Layer	Technology
UI	Flutter
State Management	Riverpod / BLoC
Database	SQLite / Drift / Hive
Charts	Flutter UI (Bar Chart / Custom UI)
Storage	Local Database
📂 Project Structure
lib/
 ├── core/
 ├── data/
 │    ├── db/
 │    ├── repositories/
 │    ├── models/
 ├── domain/
 │    ├── entities/
 │    ├── usecases/
 ├── presentation/
 │    ├── dashboard/
 │    ├── transactions/
 │    ├── widgets/
 └── main.dart
🚀 How to Run the App
1️⃣ Clone the Repository
git clone https://github.com/your-username/fintrack_pro.git
2️⃣ Navigate to Project Directory
cd fintrack_pro
3️⃣ Install Dependencies
flutter pub get
4️⃣ Generate Required Files (if using Drift / build_runner)
flutter pub run build_runner build --delete-conflicting-outputs
5️⃣ Run the App
flutter run
🎥 Demo / Screen Recording

A screen recorded video walkthrough of the application is attached below:

👉 🔗 Video & APK Download Link:
https://drive.google.com/drive/folders/1xGaTlEmi43wFlN7WZVW9Qcan0rTOihQQ?usp=drive_link

📌 The demo includes:
Dashboard overview
Adding transactions
Editing & deleting entries
Bar chart updates
Dark / Light mode switching
Full offline functionality
📦 APK

You can directly install and test the application using the APK provided in the above Google Drive link.
