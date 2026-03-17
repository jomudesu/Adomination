# 🌍 Adomination

A simple mobile app built with **MIT App Inventor** and **Firebase** — featuring user authentication, email verification, and a personalized welcome screen.

---

## 📱 Screenshots

| Sign Up | Sign In | Welcome |
|--------|---------|---------|
| ![Sign Up](screenshots/login.jpg) | ![Sign In](screenshots/register.jpg) | ![Welcome](screenshots/welcome.jpg) |

---

## ✨ Features

- 📧 **Email & Password Registration** via Firebase Authentication
- ✅ **Email Verification** — users must verify before logging in
- 🔐 **Secure Sign In** with error messages for invalid credentials
- 🎨 **Personalized Welcome Screen** displaying the user's nickname in cyan (Local Only)
- 🔑 **Forgot Password** with email format validation and existence check
- ☁️ **Firestore Integration** — nickname and email saved to cloud database (Incomplete - Email Only)
- 🚪 **Logout** with session clearing

---

## 🛠️ Built With

| Tool | Purpose |
|------|---------|
| [MIT App Inventor](https://appinventor.mit.edu/) | App development platform |
| [Firebase Authentication](https://firebase.google.com/docs/auth) | User login & registration |
| [Cloud Firestore](https://firebase.google.com/docs/firestore) | Cloud database for user data |
| Firebase REST API | Communication between App Inventor and Firebase |
