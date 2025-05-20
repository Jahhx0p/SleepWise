# 😴 SleepWise

**SleepWise** is an AI-based system designed to analyze and improve a user’s sleep quality through sound analysis, movement patterns, and optional journaling. By passively monitoring audio (e.g., snoring, sleep talking, coughing) and movement using a smartphone placed near the bed, the system identifies sleep disturbances and classifies sleep stages.

Built with a focus on privacy, user insights, and passive tracking, SleepWise transforms raw nighttime data into actionable feedback to help users achieve healthier sleep routines.

## 📌 Features

- 🎙️ **Audio-Based Sleep Monitoring**:
  - Detects snoring, sleep talking, coughing, and ambient noise
  - Classifies noise levels and frequency to identify disturbances
  - Local ML models for privacy-preserving audio analysis

- 📱 **Motion Tracking**:
  - Uses smartphone accelerometer and gyroscope
  - Tracks restlessness, position shifts, and wake moments
  - No wearables required

- 📈 **Sleep Stage Classification**:
  - Infers sleep stages (light, deep, REM) using combined audio-motion data
  - Visual sleep cycle charts for nightly reports
  - Anomaly detection for irregular patterns

- 📓 **Optional Sleep Journaling**:
  - User notes for mood, dreams, and routines
  - Correlates lifestyle habits with sleep quality
  - Smart reminders for bedtime consistency

- 🔐 **Privacy-Focused Architecture**:
  - All processing happens on-device by default
  - No audio recordings are stored or uploaded
  - End-to-end encrypted journaling data

## 🛠️ Tech Stack

- **Frontend**: React Native, Recharts
- **Backend**: Python (TensorFlow Lite, Flask)
- **Mobile Integration**: Native modules for iOS/Android sensors
- **Storage**: SQLite (local), optional encrypted sync
- **AI Models**: TFLite for sound classification and stage prediction

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- Python 3.9+
- Android Studio / Xcode
- React Native CLI

### Clone & Run

```bash
git clone https://github.com/your-username/sleepwise.git
cd sleepwise
npm install
npx react-native run-android   # or run-ios
