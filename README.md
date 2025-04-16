# 🔐 Smart Door Lock using ESP32-CAM (Arduino IDE)

A smart door lock system using the **ESP32-CAM** module, enabling face recognition-based door access control. Built with the Arduino IDE for a secure, modern, and contactless solution.

---



## 🔧 Components Used

- ESP32-CAM Module  
- FTDI Programmer (for flashing code)  
- SG90 Servo Motor  
- Jumper Wires  
- 5V Power Supply  
- Arduino IDE  

---

## 🚀 Setup & Installation


1. Connect ESP32-CAM to FTDI programmer (TX↔RX, RX↔TX, GND↔GND, 5V↔5V).
2. Connect GPIO0 to GND before uploading code.
3. Open `smart_door_lock.ino` in Arduino IDE.
4. Go to Tools > Board > "AI Thinker ESP32-CAM".
5. Select correct COM port.
6. Upload the code.
7. After successful upload, disconnect GPIO0 from GND and reset the board.
8. ESP32-CAM will now boot into normal mode.


---

## 📸 Features

- Face Detection and Recognition  
- Wireless operation via Wi-Fi  
- Contactless Smart Locking System  
- Arduino IDE Compatible  
- Real-time access control



