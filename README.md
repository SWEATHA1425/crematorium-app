# Crematorium Service App 🕊️

A complete Flutter-based cremation slot booking and document verification system powered by **Supabase**.

---
## 📁 Project Structure
<pre>
lib/
├── helpers/
│   └── time_helper.dart
├── models/
│   └── booking_model.dart
├── screens/
│   ├── admin_dashboard.dart
│   ├── admin_login_screen.dart
│   ├── booking_form.dart
│   ├── booking_status_screen.dart
│   ├── date_selection.dart
│   ├── document_upload.dart
│   ├── home_screen.dart
│   ├── login_screen.dart
│   ├── medical_certificate.dart
│   ├── signup_screen.dart
│   ├── slot_availability_screen.dart
│   ├── splash_screen.dart
│   ├── user_dashboard.dart
│   └── waiting_confirmation_screen.dart
├── services/
│   ├── auth_service.dart
│   ├── booking_service.dart
│   ├── database_service.dart
│   ├── notification_service.dart
│   ├── storage_service.dart
│   └── supabase_service.dart
├── theme/
│   └── app_theme.dart
├── use_cases/
│   ├── auth_provider.dart
│   └── use_cases.dart
├── widgets/
│   └── [your custom widgets]
├── main.dart
└── supabase_config.dart
</pre>
## 📱 About the App

This app simplifies the cremation process by enabling users to:
- Book cremation slots (max 6 per day)
- Upload required documents securely
- Get real-time status updates from the admin
- Receive reminders & notifications

The app supports **user and admin login**, handles **slot availability**, and provides a **dashboard for admins** to manage bookings and documents.

---

## 🔐 Features

### 👤 User Features
- Secure signup/login using Supabase Auth
- View available slots based on selected date
- Upload necessary documents:
  - Deceased Photo
  - Aadhaar Card
  - Death Certificate
  - Doctor Verification
  - Applicant Aadhar card
- Slot booking with real-time status

### 🛠️ Admin Features
- Admin login (username & password)
- View all booking requests
- Access uploaded documents via Supabase
- Accept or decline requests
- View user & deceased details
- Monitor slot usage per day

---

## 🧱 Tech Stack

- **Flutter** – Frontend UI
- **Supabase** – Auth, Realtime DB, and Storage
- **Dart** – Logic and State Management

---

## 🚀 Getting Started

### Requirements
- Flutter SDK
- Supabase account (configured with Auth, Database, and Storage)
- Android Studio or VS Code

### Run the app

flutter pub get
flutter run
