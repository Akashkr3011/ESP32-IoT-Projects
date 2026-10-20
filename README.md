# ESP32-CAM Wi-Fi Robot Car 🚗📷

A Wi-Fi-controlled robot car using the ESP32-CAM module. This project provides live camera streaming and wireless motor control through a web browser.

## ✨ Features

- 📹 Live video streaming from the ESP32-CAM
- 📱 Browser-based control interface
- ⬆️ Forward and backward movement
- ⬅️ Left and right turning
- 🛑 Stop control
- ⚡ Adjustable motor speed
- 💡 Adjustable LED brightness
- 📡 Wi-Fi Access Point mode — no external router required

## 🛠️ Hardware Requirements

- ESP32-CAM module
- OV2640 camera
- Motor driver compatible with your motor supply
- Two DC geared motors
- Robot car chassis and wheels
- Suitable battery and power supply
- Jumper wires

## 💻 Software Requirements

- Arduino IDE
- ESP32 board package
- ESP32 camera libraries
- ESPAsyncWebServer
- AsyncTCP

## 📂 Project Structure

```text
ESP32-CAM-Robot-Car/
├── README.md
└── esp32_cam_robot_car.ino
```

## ⚙️ Setup Instructions

1. Install the Arduino IDE.
2. Install the ESP32 board package.
3. Install the required AsyncTCP and ESPAsyncWebServer libraries.
4. Open `esp32_cam_robot_car.ino` in Arduino IDE.
5. Select the correct ESP32-CAM board and COM port.
6. Configure the Wi-Fi Access Point name and password in the code.
7. Upload the code using the appropriate ESP32-CAM flashing procedure.
8. Open Serial Monitor at `115200` baud.
9. Connect your phone or computer to the configured Wi-Fi network.
10. Open the IP address printed in Serial Monitor in your browser.
11. Use the web interface to control the car and view the camera stream.

## 🎮 Controls

| Control | Action |
|---|---|
| Up arrow | Move forward |
| Down arrow | Move backward |
| Left arrow | Turn left |
| Right arrow | Turn right |
| Speed slider | Adjust motor speed |
| Light slider | Adjust LED brightness |

## 📌 Important Notes

- Verify the motor driver wiring and GPIO pin compatibility before powering the circuit.
- Use a suitable external power supply for the motors.
- Check ESP32-CAM board compatibility and available PSRAM.
- Keep motor power wiring separate from sensitive camera power connections where practical.
- Change the default Wi-Fi password before sharing the project publicly.
- This project uses WebSockets for camera frames and control commands.

## 🚀 Future Improvements

- Add obstacle detection using ultrasonic sensors.
- Add battery-level monitoring.
- Improve mobile-friendly controls.
- Add autonomous navigation features.

## 👨‍💻 Author

**Akash Kumar**

B.Tech CSE | Aspiring Software Engineer | IoT & Embedded Systems Enthusiast

---

⭐ If you find this project useful, consider giving the repository a star!
