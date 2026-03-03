# 🎧 Gesture DJ: Hand-Controlled Audio Mixer

**Gesture DJ** is a real-time computer vision application that allows you to control music and sound effects using simple hand gestures. Powered by **OpenCV** and **MediaPipe**, it transforms your webcam into a touch-free DJ controller.

---

## 🚀 Features
* **Real-time Hand Tracking:** High-speed gesture detection using MediaPipe.
* **Touchless Control:** Play, swap, or stop tracks without touching your keyboard.
* **Visual Feedback:** On-screen HUD showing current detected gestures and playback status.
* **Debounce/Cooldown System:** Prevents accidental double-triggers.

---

## 🎮 How to Control

| Gesture | Action | Sound Triggered |
| :--- | :--- | :--- |
| ☝️ **One Finger** | Play Disco | `disco.wav` |
| ✋ **Open Palm** | Play Clap | `clap.wav` |
| ✌️ **Two Fingers** | Play Amazing | `amazing.wav` |
| ✊ **Fist** | Stop All | (Silence) |

---

## 🛠️ Prerequisites

Before running the script, ensure you have **Python 3.x** installed along with the following libraries:

```bash
pip install opencv-python mediapipe pygame

📂 Project Structure
Make sure your directory looks like this so the script can find your tracks:

.
├── gesture_dj.py      # The main script
├── disco.wav          # Audio file for "ONE" gesture
├── clap.wav           # Audio file for "PALM" gesture
└── amazing.wav        # Audio file for "TWO" gesture
