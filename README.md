# linguify_snap

# AI-Powered Visual Translator App

A real-time image-to-text translation app

## 📌 Overview

This is an AI-powered mobile application that allows users to translate text from images into multiple languages. The app leverages Optical Character Recognition (OCR) to detect and extract text from images and integrates with a translation API for accurate multilingual translations.

## ✨ Features

📷 Image-to-Text Extraction: Uses OCR (Google ML Kit, Firebase ML, or Tesseract) to detect text.

🎥 Real-Time Camera Translation: Translate text from live camera input.

🌍 Multi-Language Support: Supports translation into multiple languages.

🔄 Offline Mode: Preload language packs for offline translation.

🎙️ Voice Input & Output: Speech-to-text translation and text-to-speech for pronunciation.

✍️ Text Editing & Copying: Modify detected text before translating.

🛠️ User-Friendly UI/UX: Clean and intuitive interface with dark mode support.

☁️ Cloud Storage & History: Save and access past translations.

## 🏗️ Tech Stack

Frontend: React, TypeScript, Tailwind CSS, Shadcn UI
OCR: Tesseract OCR
Mobile: Capacitor for Android/iOS

## 🚀 Installation & Setup

### Prerequisites

- Node.js and npm/yarn
- Android Studio (for Android development)
- Git

### Steps to Run as Web App

1. Clone the Repository
```
git clone https://github.com/your-username/visual-translator.git
cd visual-translator
```

2. Install Dependencies
```
npm install
```

3. Run the App
```
npm run dev
```

### Steps to Run on Android

1. Build the web app
```
npm run build
```

2. Add Android platform (first time only)
```
npx cap add android
```

3. Sync the web app with Android
```
npx cap sync
```

4. Open in Android Studio
```
npx cap open android
```

5. Run the app on an emulator or connected device from Android Studio

### Updating the Android App

After making changes to the web app:

1. Rebuild the web app
```
npm run build
```

2. Sync changes to Android
```
npx cap sync
```

3. Open in Android Studio and run
```
npx cap open android
```

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙌 Contributing

Pull requests are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## 📬 Contact

For questions or suggestions, reach out via dineshkumaryaram17@gmail.com or create an issue in this repository.
