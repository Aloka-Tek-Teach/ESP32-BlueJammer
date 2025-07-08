<details>
  <summary>📘 මෙතන ක්ලික් කරලා සිංහලෙන් වැඩි විස්තර කියවන්න</summary>

---

## 🔍 ESP32-BlueJammer මොකද්ද?

ESP32-BlueJammer කියන්නේ ESP32 Dev Module එකක් සහ nRF24L01+PA+LNA modules 2ක් භාවිතා කරලා 2.4GHz වලින් සන්නිවේදනය කරන උපාංගවලට බාධා කරන device එකක්.

මෙය:
- Bluetooth
- WiFi
- RC drones
- IoT devices
- Audio speakers

වැනි devices වලට **unwanted packets / noise** යවලා සන්නිවේදනය බිඳදමනවා (DoS attack style එකට).  

---

## ⚠️ මෙය භාවිතා කරන්නෙ කෙතරම් සවියෙන්ද?

- **Educational & Security Testing** වලට පමණක් භාවිතා කරන්න.
- **ජම් කරනවා** කියන්නේ බොහෝ රටවල නීතිවිරෝධී ක්‍රියාවක්.
- නීති විරෝධීව භාවිතා කලානම් ඔබට වගකීම් ඇති.

---

## 🧰 අවශ්‍ය උපකරණ

- ESP32-WROOM-32U (Dev Board)
- nRF24L01+PA+LNA modules (2x)
- 10uF capacitor (2x)
- 3.7V Li-Ion battery (විකල්ප)
- TP4056 Charging Module
- JST PH 2.0 Connector
- Mini Slide Switch
- LED 3mm (Blue)
- 470k Ohm resistor

---

## 🔌 සම්බන්ධකරණය (Wiring)

**HSPI (Module 1)**

| Module Pin | ESP32 Pin |
|------------|------------|
| VCC        | 3.3V       |
| GND        | GND        |
| CE         | GPIO 16    |
| CSN        | GPIO 15    |
| SCK        | GPIO 14    |
| MOSI       | GPIO 13    |
| MISO       | GPIO 12    |

**VSPI (Module 2)**

| Module Pin | ESP32 Pin |
|------------|------------|
| VCC        | 3.3V       |
| GND        | GND        |
| CE         | GPIO 22    |
| CSN        | GPIO 21    |
| SCK        | GPIO 18    |
| MOSI       | GPIO 23    |
| MISO       | GPIO 19    |

---

## 💻 Firmware Flash කරන්නෙ කොහොමද?

ඔයාට පහසුවෙන් Flash කරන්න පුළුවන් මේ WebFlasher එකෙන්:

🔗 [https://esp32-bluejammerflasher.pages.dev](https://esp32-bluejammerflasher.pages.dev)

1. ESP32 එක Data USB Cable එකෙන් Connect කරන්න  
2. Chip එක තෝරලා Firmware එකක් පරිශීලනය කරන්න  
3. Flash කරන්න ❤️

---

## 📦 3D Printed Case එක

- PCB size: **7cm x 5.5cm**
- USB Port, Boot/EN Buttons visible
- Charging LED Indicator support
- ON/OFF Switch hole
- Case එකේ `.stl` file එක:  
  [Download STL File](https://dwdwpld.pages.dev/ESP32-BlueJammerBy@emensta3DCase.stl)

---

## 🛑 අවවාදය

මෙම උපාංගය භාවිතා කිරීමෙන් ඔබට ඇතිවන කිසිදු නීතිමය ගැටලුවක් සදහා  
**මම වගකීමක් නොගෙනි**.  
අධ්‍යාපනික අරමුණු සඳහා පමණක් භාවිතා කරන්න.

</details>