# 📝 To-Do List Application
A simple, fast, and interactive To-Do List app to keep your daily tasks organized. Beyond the standard task controls, it includes **voice commands** so you can add or manage your tasks completely hands-free using your mic.

## 🔥 Features

- **Core Task Management:** Quick-add tasks, mark items complete, edit details on the fly, or clean up finished tasks.
- **Voice Controls:** Built using the Web Speech API—talk directly to the app to add, modify, or clear items.
- **Persistent Storage:** Your tasks save automatically in your browser's local storage so you never lose your list on refresh.
- **Fully Responsive:** Clean UI built to work smoothly across both mobile and desktop screens.

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **Vanilla JavaScript** (Web Speech API)

## 🚀 How to Run It
Since this is a lightweight static site, you don't need to run `npm install` or configure complex build tools.

### 1. Clone the repository
Bash

```
git clone https://github.com/Kritika30032002/To-Do-List-Application.git
cd To-Do-List-Application
```

### 2. Launch the app

- **Using Live Server in VS Code (Recommended):**
Open the project folder in VS Code (`code .`), right-click `index.html`, and choose **Open with Live Server**. *(This works best for browser microphone permissions).* 
- **Using Python:**
Run `python -m http.server 8000` in your terminal, then open `http://localhost:8000` in your browser.
- **Directly in Browser:**
Double-click `index.html` or drag it directly into any browser tab.

## 🎙️ Voice Command Guide
To start using voice input:

1. Click the **Start Voice Command** button.
2. Grant microphone access if your browser prompts you.
3. Speak one of the following phrases clearly:

- **To add a task:** *"Add assignment due date 16th Nov priority High"*
- **To edit a task:** *"Edit task assignment to project submission"*
- **To delete a task:** *"Delete task assignment"*
*(Note: Voice recognition works best in Chrome or Edge.)*

## 🤝 Contributing
Got ideas to improve the UI or add new features? Pull requests are always welcome!

1. Fork the repo.
2. Create your feature branch (`git checkout -b feature/CoolNewFeature`).
3. Commit your changes (`git commit -m 'Add some cool feature'`).
4. Push to the branch (`git push origin feature/CoolNewFeature`).
5. Open a Pull Request.

## 📜 License
Distributed under the MIT License. See `LICENSE` for more details.
