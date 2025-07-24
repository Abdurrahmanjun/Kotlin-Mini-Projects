
# 🧪 Kotlin Mini Projects

A hands-on journey into Android development with Kotlin — experimenting with Jetpack Compose 🧱, app architecture ⚙️, and modern Android features 🚀.

---

## 🗂️ Folder Structure

Each folder inside this repo is an independent Kotlin project.  

```
kotlin-mini-projects/
├── README.md

├── ui-compose/
│   ├── compose-basics/                    # Layouts, states, modifiers
│   ├── animated-weather-ui/              # Canvas, animations, transitions
│   ├── instagram-ui-clone/               # Feed/profile layout
│   ├── bottomnav-drawer-demo/            # Multiple navigation patterns
│   ├── dark-light-theme-switcher/        # Dynamic themes

├── architecture/
│   ├── todo-mvvm-stateflow/              # ViewModel, StateFlow, Repository
│   ├── notes-app-room/                   # Room + ViewModel CRUD
│   ├── login-auth-flow/                  # Form validation, nav, state mgmt
│   ├── settings-datastore/               # Preference settings with DataStore

├── firebase/
│   ├── realtime-chat-firestore/          # Chat app with Firestore + Auth
│   ├── firebase-auth-demo/               # Email/password + Google Sign-In
│   ├── firestore-todo-sync/              # Cloud-based Todo app
│   ├── image-upload-storage/             # Upload from Camera to Firebase Storage
│   ├── push-notification-fcm/            # FCM basic integration
│   ├── user-profile-firestore/           # Profile info saved in Firestore
│   ├── firebase-analytics-demo/          # Tracking user events
│   ├── crashlytics-test-app/             # Logging crashes for testing

├── networking/
│   ├── news-app-retrofit-paging/         # REST API + Paging3 + ViewModel
│   ├── graphql-explorer-apollo/          # Explore APIs with Apollo GraphQL
│   ├── http-client-auth-interceptor/     # OkHttp + token management

├── storage/
│   ├── room-bookmark-manager/            # Offline bookmark manager
│   ├── datastore-settings-demo/          # Lightweight persistent settings
│   ├── encrypted-sharedprefs/            # Secure credential/token storage

├── sensors-permissions/
│   ├── camera-app-camerax/               # Custom Camera UI
│   ├── location-tracker-maps/            # Google Maps + user location
│   ├── biometric-auth-demo/              # Fingerprint/face unlock
│   ├── permission-handler-demo/          # Requesting camera, location
│   ├── sensors-accelerometer-demo/       # Shake or tilt interaction

├── experimental/
│   ├── compose-canvas-drawing/           # Freehand drawing with Canvas
│   ├── tictactoe-game-compose/           # Game logic in Compose
│   ├── markdown-viewer-compose/          # Markdown renderer
│   ├── compose-transitions-lab/          # Motion & animation experiments

├── utility-apps/
│   ├── bmi-calculator/                   # Input + output logic app
│   ├── unit-converter/                   # Dropdowns + live calculations
│   ├── pomodoro-timer/                   # Timer logic with Compose
│   ├── expense-tracker-local/            # Monthly budget tracker
│   ├── stopwatch-app/                    # Compose + Timer

```

---

## 📁 Project Categories

This repository is structured into folders by theme — UI, architecture, Firebase, sensors, storage, and more — to make learning organized and repeatable.

I track my progress with ✅ (done), 🛠️ (in progress), or 🔜 (planned).

---

## 🗂️ Table of Contents

| Status | Project Folder                          | Description |
|--------|------------------------------------------|-------------|
| 🔜 | `compose-basics/`                     | Practice layout, modifiers, states |
| 🔜 | `animated-weather-ui/`                  | Animated weather dashboard using `Canvas`, `LaunchedEffect` |
| 🔜 | `instagram-ui-clone/`                   | Feed/profile UI clone |
| 🔜 | `bottomnav-drawer-demo/`                | BottomNav + Drawer navigation |
| 🔜 | `dark-light-theme-switcher/`            | Theme switching in Compose |
| 🔜 | `todo-mvvm-stateflow/`               | MVVM Todo app using ViewModel + StateFlow |
| 🔜 | `notes-app-room/`                       | Room-based notes app with clean architecture |
| 🔜 | `login-auth-flow/`                      | Login UI with validation and state mgmt |
| 🔜 | `settings-datastore/`                   | Preferences/settings using Jetpack DataStore |
| 🔜 | `realtime-chat-firestore/`           | Real-time chat using Firestore + Firebase Auth |
| 🔜 | `firebase-auth-demo/`                   | Sign-in with email & Google |
| 🔜 | `firestore-todo-sync/`                  | Cloud-synced todo app |
| 🔜 | `image-upload-storage/`                 | Upload image from camera/gallery to Firebase Storage |
| 🔜 | `push-notification-fcm/`                | Basic FCM setup with Compose UI |
| 🔜 | `user-profile-firestore/`               | Save/display user profile from Firestore |
| 🔜 | `firebase-analytics-demo/`              | Track events with Firebase Analytics |
| 🔜 | `crashlytics-test-app/`                 | Log and monitor crashes with Crashlytics |
| 🔜 | `news-app-retrofit-paging/`           | News app with paginated API + ViewModel |
| 🔜 | `graphql-explorer-apollo/`              | Query public APIs with Apollo GraphQL |
| 🔜 | `http-client-auth-interceptor/`         | Authenticated HTTP requests using OkHttp |
| 🔜 | `room-bookmark-manager/`             | Bookmark manager using Room |
| 🔜 | `datastore-settings-demo/`              | Lightweight settings app |
| 🔜 | `encrypted-sharedprefs/`                | Secure token/password storage |
| 🔜 | `camera-app-camerax/`               | Capture image with CameraX |
| 🔜 | `location-tracker-maps/`                | Map with live user location |
| 🔜 | `biometric-auth-demo/`                  | App lock using fingerprint/face unlock |
| 🔜 | `permission-handler-demo/`              | Demo app with runtime permission requests |
| 🔜 | `sensors-accelerometer-demo/`           | Motion-based interaction (e.g. shake to refresh) |
| 🔜 | `compose-canvas-drawing/`          | Freehand drawing on canvas |
| 🔜 | `tictactoe-game-compose/`               | Logic + UI game in Compose |
| 🔜 | `markdown-viewer-compose/`              | Render markdown content |
| 🔜 | `compose-transitions-lab/`              | Motion + gesture experiments |
| 🔜 | `bmi-calculator/`                      | Basic BMI app using input fields |
| 🔜 | `unit-converter/`                       | Simple unit conversion tool |
| 🔜 | `pomodoro-timer/`                       | Countdown timer with pause/resume |
| 🔜 | `expense-tracker-local/`                | Local expense manager |
| 🔜 | `stopwatch-app/`                        | Stopwatch with start/pause/reset |

---

## 📌 How to Use

- Pick a folder based on the topic you're learning.
- Open it in Android Studio.
- Follow the `README.md` inside each project for specific instructions (if available).
- Run with `./gradlew installDebug` or from Studio IDE.
