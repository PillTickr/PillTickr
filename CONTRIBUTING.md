# 🙌 Contributing to PillTickr

Thanks for your interest in contributing to **PillTickr**! We welcome all kinds of contributions — code, design, documentation, testing, and feedback.

---

## 💻 Code Contributions

### 1. Fork the repository
Click the **Fork** button at the top-right of this page.

### 2. Clone your fork

```bash
git clone https://github.com/your-username/PillTickr.git
cd PillTickr
````

### 3. Install dependencies

```bash
npm install
# or
yarn install
```

### 4. Create a new branch

```bash
git checkout -b feature/your-feature-name
```

### 5. Commit and push

```bash
git commit -m "Add your awesome feature"
git push origin feature/your-feature-name
```

### 6. Open a Pull Request

Go to your fork on GitHub and click **"New Pull Request"**. Describe your changes clearly.

---

## 🧪 Running Locally

To test the app on your device:

```bash
npx expo start
```

Then scan the QR code with **Expo Go** on your mobile device.

---

## 📦 Tech Stack

* **React Native + Expo**
* **SQLite / AsyncStorage** (offline storage)
* **Firebase / Supabase** (optional sync)
* **Tailwind CSS + NativeWind** (UI styling)
* **Expo Notifications** (local & scheduled reminders)

---

## 📂 Project Structure (simplified)

```
src/
├── components/     # Reusable UI elements
├── screens/        # App screens (pages)
├── utils/          # Helper functions
├── services/       # Storage and sync logic
└── assets/         # Icons, fonts, images
```

---

## 💬 Get Involved

* Report issues or bugs → [GitHub Issues](https://github.com/PillTickr/PillTickr/issues)
* Propose ideas or improvements → [GitHub Discussions](https://github.com/PillTickr/PillTickr/discussions)
* Join the community (TBD — Discord/Matrix/Forum)

---

## 📜 License

PillTickr is open-source under the [MIT License](./LICENSE). Use it, improve it, and help others stay healthy!
