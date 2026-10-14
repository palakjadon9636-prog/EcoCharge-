# EcoCharge: IoT-Based Rewards & Mobile Recharge System

EcoCharge is an innovative, tech-driven solution designed to automate plastic waste management by integrating it with digital incentives (mobile data and talktime recharges) for users across rural and semi-urban India.

## 🚀 Key Features
- **Automated Segregation & Weighing:** Uses an Arduino/Raspberry Pi setup with an IR Sensor and Load Cell to accurately detect and weigh deposited plastic bottles.
- **Dynamic QR Code Generation:** Displays a unique QR code on the smartbin screen after successful trash deposition.
- **Digital Wallet & Instant Rewards:** Allows users to scan the QR via a Flutter mobile application to earn Eco-Points and instantly redeem them for mobile network data recharges (Jio, Airtel, Vi).
- **Anti-Fraud Security System:** Implements a daily user limit to prevent exploitation and system gaming.
- **Emergency Retrieval Mechanism:** Features a remote bypass button in the mobile app to temporarily unlock the bin if a user accidentally drops cash or personal items inside.

## 💻 Tech Stack
- **Hardware/IoT:** Arduino / ESP32, Load Cell (Weight Sensor), IR Proximity Sensor, Solenoid Electronic Lock, OLED Display.
- **Mobile Application:** Flutter / React Native (Cross-platform frontend).
- **Backend & Database:** Node.js, Express, Firebase / MongoDB, Third-Party Mobile Recharge API.

## 🛠️ Setup and Installation Instructions
1. Clone this repository onto your local system.
2. For the backend: Run `npm install` to download dependencies and set up your `.env` variables for Firebase and Telecom APIs.
3. For the mobile app: Install the Flutter SDK, connect a device, and run `flutter run`.
4. For IoT hardware: Flash the provided controller script using the Arduino IDE after connecting the sensors to the designated pins.

## ⚖️ Open-Source License
This project is fully open-source and distributed under the **MIT License**.
