# eyeDoc 👁️

**eyeDoc** is a smart, privacy-first menu bar application for macOS designed to reduce digital eye strain and improve productivity. It helps you follow the 20-20-20 rule by reminding you to take breaks, blink, and look away from your screen, while also offering hydration and posture reminders.

Unlike standard timers, eyeDoc is intelligent—it knows when you are in a meeting, watching a movie, or away from your desk, and adjusts accordingly.

## ✨ Key Features

### 🧠 Smart & Adaptive
*   **Meeting Detection:** Automatically pauses timers when your **Microphone** or **Camera** is in use (e.g., Zoom, Teams, Google Meet).
*   **Calendar Integration:** Detects "Busy" events in your calendar and pauses reminders during scheduled meetings.
*   **Idle Detection:** Pauses the timer when you step away from your computer and resumes when you return.
*   **App Exclusions:** Postpones breaks when specific apps (games, presentation software) are focused.

### 🎨 Customizable Breaks
*   **Multiple Overlay Styles:** Choose between a strict **Blackout**, a gentle **Blur**, or a subtle **Corner Pop-up**.
*   **Soundscapes:** Optional calming sounds (Birds, Chime) to play during breaks.
*   **Exercises:** Built-in guidance for Eye Yoga and Mindful Breathing during breaks.

### 🧘‍♂️ Wellness & Tracking
*   **Secondary Reminders:** Separate, customizable timers for **Posture** checks and **Hydration**.
*   **Usage Statistics:** Track your focus time, breaks taken, and skips over time.
*   **Achievements:** Gamified milestones to keep you motivated.

## 🔒 Privacy First
eyeDoc is built with a strict privacy philosophy.
*   **All data processing happens locally on your Mac.**
*   Calendar events, microphone status, and input monitoring data **never** leave your device.
*   We do not use third-party analytics or tracking SDKs.

## 🛠️ Requirements
*   **macOS 12.0** or later (macOS 13+ recommended for Login Item support).
*   **Permissions:**
    *   *Accessibility:* For idle detection (mouse/keyboard activity).
    *   *Calendar:* To detect meeting times.
    *   *Notifications:* To alert you before a break starts.

## 🚀 Installation & Development

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YourUsername/eyeDoc.git
