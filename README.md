# YapNotes - Simple Voice Transcription App

## Description

YapNotes is a web-based application designed for quick and easy voice-to-text transcription directly in your browser. It captures your speech using the microphone, converts it into text, and saves the entries locally in your browser's storage, organized by date. It also features a real-time audio visualizer that reacts to your voice input.

## Features

- **Voice-to-Text:** Utilizes the browser's Web Speech API for real-time speech recognition.
- **Local Storage:** Saves transcriptions directly in the browser's localStorage, allowing you to access past entries from the same browser.
- **Daily Organization:** Entries are automatically grouped by the date they were created.
- **History View:** A modal allows viewing entries from previous days.
- **Audio Visualizer:** Provides visual feedback by displaying bars that react to microphone input volume during recording.
- **Live Transcript:** Shows interim and final speech recognition results as you speak.
- **Word Count:** Displays the total word count of the saved entries for the current day.
- **Modern UI:** Features a clean, dark-themed interface with subtle animations and a glassmorphism effect.
- **Responsive Design:** Adapts to different screen sizes.

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **APIs:**
    - Web Speech API (`SpeechRecognition`)
    - Web Audio API (`AudioContext`, `AnalyserNode`)
    - LocalStorage API
    - Intl (Date/Time Formatting)

## How to Use

1. Clone or download the project files.
2. Open the `index.html` file in a modern web browser that supports the Web Speech and Web Audio APIs (e.g., Chrome, Edge).
3. Allow microphone access when prompted by the browser.
4. Click the microphone button to start recording.
5. Speak clearly. Your transcription will appear in the live area and then be saved in the main display when you stop recording.
6. Click the microphone button again to stop recording.
7. Click the history button (bottom right) to view entries from previous days.

## Browser Compatibility

This application relies heavily on the **Web Speech API** and **Web Audio API**. Browser support for these APIs can vary:

- **Chrome (Desktop & Android):** Generally good support.
- **Edge (Chromium-based):** Generally good support.
- **Firefox:** May require enabling flags or might have partial support for Web Speech API. Web Audio API support is generally good.
- **Safari (macOS & iOS):** Support for Web Speech API might be limited or require specific OS versions. Web Audio API support is generally good.

Always use the latest version of a supported browser for the best experience. Microphone access permission is required.

## Future Improvements (Ideas)

- Add functionality to edit or delete entries.
- Implement search functionality for past entries.
- Offer different language options for transcription.
- Add export functionality (e.g., download as text file).
- Improve error handling for specific API limitations.
- Refine the background bubble animation.
