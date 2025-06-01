# Postify 🧠💪

## Overview
**Postify** is a smart wearable system designed to monitor arm posture during strength training, such as the inclined chest press. By using an MPU-6050 gyroscope/accelerometer, Postify detects unsafe arm angles in real time. When improper form is detected, a vibration motor delivers haptic feedback to alert the user — helping to prevent shoulder and upper chest injuries. Through Bluetooth, Postify connects to a mobile app where users can select exercises and get personalized angle settings.

---

## 💡 Key Features

- 🎯 Real-time posture tracking using the MPU-6050
- 🔔 Instant vibration alerts for improper form
- 📱 Mobile app integration via Bluetooth (e.g., HC-05)
- 🧠 Exercise-specific calibration to improve safety
- 🧩 Compact, wearable design powered by Arduino Nano

---

## 🔩 Components

- **MPU-6050** — Motion sensor (gyro + accelerometer)  
- **Arduino Nano** — Microcontroller for real-time processing  
- **Bluetooth Module (e.g., HC-05)** — Wireless data communication  
- **Vibration Module** — Provides instant physical alerts  
- **Breadboard & Jumper Wires** — For prototyping  
- **Power Supply** — USB or portable battery pack

---

## 🔄 How It Works

1. User opens the Postify mobile app and selects a training exercise.
2. The system loads the recommended safe angle range for that movement.
3. The MPU-6050 monitors arm angle as the user performs reps.
4. If the movement exceeds the safe range, the vibration motor is triggered.
5. (Optional) Data is sent to the app for feedback or logging.

---

## 📲 Mobile App Integration

- **Bluetooth Module**: Communicates with mobile app
- App features:
  - 🔘 Select specific exercises
  - 📏 Customize or display angle thresholds
  - 📊 View logs or feedback (future update)

---

## 🚀 Getting Started

1. Assemble the hardware on a breadboard.
2. Upload the Arduino sketch (coming soon) to your Nano board.
3. Connect your Bluetooth module and pair with your mobile app.
4. Launch the app, select an exercise, and train with real-time feedback!

---

## 🧭 Project Roadmap

- [ ] Build mobile app interface
- [ ] Develop angle detection logic for Arduino
- [ ] Integrate Bluetooth communication
- [ ] Add support for more exercises
- [ ] Design wearable casing (optional)

---

## 🧠 Why Postify?

Improper form during workouts is one of the top causes of injury — especially in shoulder- and chest-heavy movements like the inclined bench press. **Postify** helps users train smarter with real-time guidance and feedback. It promotes safer workouts and better technique — perfect for athletes, beginners, or personal trainers.

---

## 🤝 Contributing

Have an idea or feature suggestion? Feel free to open a pull request or issue. Let’s improve safe training together.

---

## 📄 License

Licensed under the **MIT License**.

---

## 📧 Contact

For support, collaboration, or questions, contact [Your Name] at [your.email@example.com].

