# 🛡️ Phisherman

**Phisherman** is an Android app that uses accessibility services to detect and capture phishing URLs in the background while users browse on Chrome. Designed to protect users from potential phishing attacks, the app leverages machine learning with the **Random Forest** algorithm and Google's **Gemini AI API** for enhanced threat detection.

---

## 🚀 Features

- 🔍 **Real-time URL Monitoring**: Captures URLs accessed in Chrome using Android Accessibility Service.
- 🤖 **Phishing Detection**: Classifies URLs using a **Random Forest** model trained to detect phishing attempts.
- 🧠 **AI-Powered Analysis**: Utilizes **Gemini API** to analyze suspicious URLs and provide intelligent feedback.
- 📝 **Minimal User Interaction**: Runs silently in the background, requiring minimal input after setup.
- ⚙️ **Built with Kotlin**: Entirely developed in Kotlin for a modern and robust Android experience.

---

## 🧰 Tech Stack

- **Kotlin** - Android development
- **Android Accessibility API** - For monitoring Chrome browsing
- **Random Forest Algorithm** - For phishing classification
- **Gemini AI API** - For advanced threat analysis

---

## 📱 How It Works

1. **Accessibility Service**: Monitors Chrome for any new URLs accessed.
2. **URL Capture**: Extracts the URL from the Chrome app screen.
3. **Phishing Detection**: Runs the URL through a Random Forest model.
4. **AI Analysis**: Optionally sends the URL to Gemini for deeper analysis.
5. **Alert**: Notifies the user if the URL is deemed suspicious or dangerous.

---

## 🛠️ Installation

> ⚠️ Due to the use of Accessibility Services, the app requires **manual installation (APK)** and enabling the service in accessibility settings.

1. Clone the repository:
   ```bash
   git clone https://github.com/vankaSiddhartha/Phiserman-app.git
