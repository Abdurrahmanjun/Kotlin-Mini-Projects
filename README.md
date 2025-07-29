# 🧪 Kotlin Mini Projects

A hands-on journey into **Modern Android development** with Kotlin — exploring Jetpack Compose 🧱, MVVM architecture ⚙️, Firebase 🔥, concurrency 🧵, AI integration 🤖, modularization 🧩, offline-first strategies 💾, and much more.

Each folder in this repository is an **independent runnable mini app** focused on a real-world use case, feature, or best practice.

---

## 🗂️ Folder Structure

```
kotlin-mini-projects/
├── _kmp-crossplatform/
├── ai-mlkit/
├── architecture/
├── compose-advanced/
├── concurrency/
├── experimental/
├── firebase/
├── modularization/
├── networking/
├── offline-sync-patterns/
├── security-and-integrity/
├── sensors-permissions/
├── storage/
├── testing-ci/
├── ui-compose/
├── utility-apps/
├── webview-hybrid/
```


---

## 📁 Categories & Project List

### 🎨 UI with Jetpack Compose

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `compose-basics/`                   | Practice layout, modifiers, states |
| 🔜 | `animated-weather-ui/`              | Animated weather dashboard using `Canvas`, `LaunchedEffect` |
| 🔜 | `instagram-ui-clone/`               | Feed/profile UI clone |
| 🔜 | `bottomnav-drawer-demo/`            | BottomNav + Drawer navigation |
| 🔜 | `dark-light-theme-switcher/`        | Theme switching in Compose |

---

### 🏗 Architecture & State Management

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `todo-mvvm-stateflow/`              | MVVM Todo app using ViewModel + StateFlow |
| 🔜 | `notes-app-room/`                   | Room-based notes app with clean architecture |
| 🔜 | `login-auth-flow/`                  | Login UI with validation and state mgmt |
| 🔜 | `settings-datastore/`               | Preferences/settings using Jetpack DataStore |

---

### 🔥 Firebase Integrations

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `realtime-chat-firestore/`          | Real-time chat using Firestore + Firebase Auth |
| 🔜 | `firebase-auth-demo/`               | Sign-in with email & Google |
| 🔜 | `firestore-todo-sync/`              | Cloud-synced todo app |
| 🔜 | `image-upload-storage/`             | Upload image to Firebase Storage |
| 🔜 | `push-notification-fcm/`            | FCM setup with Compose UI |
| 🔜 | `user-profile-firestore/`           | User profile stored in Firestore |
| 🔜 | `firebase-analytics-demo/`          | Track events with Firebase Analytics |
| 🔜 | `crashlytics-test-app/`             | Log and monitor crashes with Crashlytics |

---

### 🌐 Networking

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `news-app-retrofit-paging/`         | News app with paginated API + ViewModel |
| 🔜 | `graphql-explorer-apollo/`          | Explore APIs with Apollo GraphQL |
| 🔜 | `http-client-auth-interceptor/`     | OkHttp + token management |

---

### 💾 Storage & Preferences

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `room-bookmark-manager/`            | Offline bookmark manager |
| 🔜 | `datastore-settings-demo/`          | Jetpack DataStore for preferences |
| 🔜 | `encrypted-sharedprefs/`            | Secure storage with EncryptedSharedPreferences |

---

### 📡 Sensors & Permissions

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `camera-app-camerax/`               | Custom Camera UI using CameraX |
| 🔜 | `location-tracker-maps/`            | Google Maps with live tracking |
| 🔜 | `biometric-auth-demo/`              | Face/fingerprint unlock |
| 🔜 | `permission-handler-demo/`          | Handle runtime permissions |
| 🔜 | `sensors-accelerometer-demo/`       | Detect shake/motion via sensors |

---

### 🧵 Concurrency: Coroutines & Flow

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `coroutines-basics-demo/`           | Basics: suspend, launch, async, scopes |
| 🔜 | `flow-operators-demo/`              | Operators: debounce, map, filter |
| 🔜 | `sharedflow-stateflow-demo/`        | Hot flows for UI communication |
| 🔜 | `lifecycle-aware-collectors/`       | ViewModelScope, lifecycleScope |
| 🔜 | `parallel-background-tasks/`        | Structured concurrency demo |
| 🔜 | `retry-timeout-flow-demo/`          | Retry, catch, timeout with Flow |

---

### 🔄 Offline-First Sync Patterns

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `room-paging-remote-mediator/`      | Paging3 + RemoteMediator |
| 🔜 | `offline-todo-conflict-resolution/` | Conflict resolution in synced Todo app |
| 🔜 | `background-sync-workmanager/`      | WorkManager chaining, constraints, retries |

---

### 🔐 Security & App Integrity

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `encrypted-file-storage/`           | Encrypted file I/O with Jetpack Security |
| 🔜 | `safetynet-integrity-api-demo/`     | Tamper/root detection using SafetyNet |
| 🔜 | `app-integrity-checks/`             | App integrity and environment checks |

---

### 🤖 AI & MLKit Integrations

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `mlkit-text-translation/`           | On-device text translation |
| 🔜 | `mlkit-face-barcode-detection/`     | Camera + MLKit barcode/face |
| 🔜 | `tflite-custom-model-demo/`         | TensorFlow Lite with custom model |
| 🔜 | `chatgpt-ai-integration/`           | GPT/OpenAI/Gemini-powered assistant UI |

---

### 🧱 Compose Advanced Patterns

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `custom-slot-layouts/`              | Reusable slots like Scaffold |
| 🔜 | `remember-savable-demo/`            | Handle config changes & backstack |
| 🔜 | `modifier-performance-demo/`        | Explore recomposition cost |
| 🔜 | `collectAsState-vs-LaunchedEffect/` | Compare Compose collection patterns |

---

### 🧩 Modularization

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `dynamic-feature-modules/`          | Feature delivery with Play Store |
| 🔜 | `clean-arch-feature-modules/`       | MVVM + use case + DI by module |
| 🔜 | `di-multimodule-hilt-koin/`         | Hilt vs Koin in modular setups |

---

### 🧪 Testing, CI/CD, Performance

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `github-actions-android-ci/`        | Build + test pipeline with GitHub Actions |
| 🔜 | `espresso-ui-tests/`                | Traditional UI tests |
| 🔜 | `compose-ui-test-cases/`            | Compose-specific test samples |
| 🔜 | `baseline-profiles-performance/`    | Speed up launch time with Baseline Profiles |

---

### 🌐 WebView, MPP, JS Interop

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `compose-webview-bridge/`           | WebView + JS communication in Compose |
| 🔜 | `compose-multiplatform-preview/`    | Preview Jetpack Compose for Desktop/iOS/Web |
| 🔜 | `kotlin-js-mini-tool/`              | Simple tool/app built with Kotlin/JS

---

### 🧪 Experimental

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `compose-canvas-drawing/`           | Freehand canvas drawing |
| 🔜 | `tictactoe-game-compose/`           | Game logic in Compose |
| 🔜 | `markdown-viewer-compose/`          | Markdown rendering |
| 🔜 | `compose-transitions-lab/`          | Motion and transition playground |

---

### 🔧 Utility Apps

| Status | Project                          | Description |
|--------|----------------------------------|-------------|
| 🔜 | `bmi-calculator/`                   | Input + logic based mini tool |
| 🔜 | `unit-converter/`                   | Real-time conversion UX |
| 🔜 | `pomodoro-timer/`                   | Timer-based productivity tool |
| 🔜 | `expense-tracker-local/`            | Monthly expense logging |
| 🔜 | `stopwatch-app/`                    | Stopwatch with Compose Timer logic |

---

## ✅ Progress Tracking

I track the learning progress with:

- ✅ Done
- 🛠️ In progress
- 🔜 Planned

---

## 🚀 Getting Started

1. Clone the repo  
2. Open any folder inside `Android Studio`
3. Run with `./gradlew installDebug` or via IDE
4. Follow inline documentation and `README.md` inside each project (if present)

---

## 🧑‍💻 Contributing

This is a personal learning grind, but PRs and feedback are welcome!  
If you'd like to contribute:

- Add a project under the correct category
- Follow consistent naming, folder style, and comment structure
- Open a PR with a short description and demo screenshots

---

## 🌟 License

MIT — use these examples for learning, teaching, or prototyping freely.


