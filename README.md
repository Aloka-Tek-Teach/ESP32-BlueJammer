

---

<h1 align="center">ESP32-BlueJammer</h1>
<div align="center">
  <img src="https://dwdwpld.pages.dev/ESP32-BlueJammerBy@emensta.jpg" alt="ESP32-BlueJammer">
</div>
---

🛠️ ESP32-BlueJammer කියන්නේ මොකක්ද?

ESP32-BlueJammer එකක් කියන්නේ ESP32 NodeMCU එකක් සහ nRF24L01+ modules දෙකක් භාවිතා කරලා 2.4GHz frequency එකේ ක්‍රියා කරන device එකක්.

මෙම device එක:

Bluetooth

WiFi

RC Drones

Audio devices

IoT devices වගේ උපාංග වල සම්බන්ධතාවය බාධා කරයි (DoS – Denial of Service).


👉 මෙය security testing සහ controlled disruption සඳහා පමණක් භාවිතා කරන්න.


---

📡 කෙටි විස්තරයක්

වැඩ කරන range එක: 30m වැඩිදුරටත් (ඇන්ටෙනාව මත රඳා පවතී)

“Router” ඇන්ටෙනා හෝ 2.4GHz amplifier එකක් එකතු කළොත් range එක වැඩි කරන්න පුළුවන්

නවතම Bluetooth version වලටත් support වෙනවා



---

🎥 TikTok Tutorial

මෙතනින් බලන්න TikTok DIY වීඩියෝව


---

📶 වැඩ කරන Channel

Bluetooth = 80 චැනල්

BLE = 40 චැනල්

WiFi = 14 චැනල්

RC drones = 1 - 125 චැනල්



---

🔧 අවශ්‍ය hardware

ESP32 Dev Module (ESP32-WROOM-32U වැනි)

nRF24L01+PA+LNA modules (2ක්)

10UF Capacitor (2ක්) (5V වඩා වැඩි වෝල්ටයේ කිසිම capacitor එකක් OK)


බැටරි එකක් දාන්න ඔනනම්:

3.7V Li-Ion battery

JST PH 2.0 Connector

TP4056 Charging Module

Blue LED (3mm)

470k Ohm resistor

Mini Slide Switch


3D case එකක් Fixed කරන්න නම්:

M3X16 screws (2ක්)

M3 Nuts (2ක්)


🧾 PCB size = 7cm x 5.5cm. Drill holes දෙකක් කරලා M3 screws සදහා adjust කරන්න.


---

🔌 ESP32 Flash කිරීම WebFlasher එකෙන්



Flash කරන ක්‍රමය:

1. මෙතන click කරන්න


2. ESP32 එක USB data cable එකෙන් connect කරන්න


3. Chip එක, firmware එක තෝරලා Flash කරන්න!




---

📌 nRF24L01+ Pinout – HSPI සහ VSPI

📍 HSPI module (1st):

nRF24L01+ Pin	ESP32 Pin	Capacitor

VCC	3.3V	(+)
GND	GND	(–)
CE	GPIO 16	
CSN	GPIO 15	
SCK	GPIO 14	
MOSI	GPIO 13	
MISO	GPIO 12	


📍 VSPI module (2nd):

nRF24L01+ Pin	ESP32 Pin	Capacitor

VCC	3.3V	(+)
GND	GND	(–)
CE	GPIO 22	
CSN	GPIO 21	
SCK	GPIO 18	
MOSI	GPIO 23	
MISO	GPIO 19	



---

🔋 බැටරි සම්බන්ධකරණය

කොටස	සම්බන්ධය

Battery +	JST PH 2.0 +
Battery -	JST PH 2.0 -
OUT + from TP4056	Switch input (+) → ESP32 3V3
OUT - from TP4056	ESP32 GND
LED +	ESP32 3V3
LED -	470k Resistor → GND



---

🖨️ 3D Printed Case

📌 ESP32 USB Port, EN, Boot buttons එකට යා හැකි ආකාරයට!



📌 TP4056 Charging Port එක සහ LED indicators (Red = Charging | Blue = Fully Charged)



📌 On/Off Switch එක සහ Blue LED indicator



📎 3D Model එක මෙතනින් බාගන්න (.stl)




---

🧩 PCB (සහය දක්වන ආකාරය)

📌 PCB size = 7cm x 5.5cm – වැඩි එකක් use කරන්න බැහැ




---

⚠️ අවවාදයෙකියි!

<h4 align="center">මෙය අධ්‍යාපනික අරමුණු සඳහා පමණි! නීති විරෝධී හෝ අසදාචාරවත් ක්‍රියා සඳහා මෙය භාවිතා නොකරන්න. Jamming කිරීම බොහෝ රටවල නීතිවිරෝධී ක්‍රියාවකි.</h4><h4 align="center">ඔබගේ ක්‍රියා වලට මම කිසිදු වගකීමක් නොගෙනි.</h4>
---

ඔබට අවශ්‍ය වුනහොත්, මම මේක PDF එකක් වශයෙන් convert කරලා දෙන්න පුළුවන්. කියන්න 😎

