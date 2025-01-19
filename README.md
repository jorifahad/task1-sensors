 **Arduino-Based Multi-Color Temperature Indicator (Cold, Moderate, Hot)**  
This project uses an Arduino Uno and a TMP36 temperature sensor to monitor the temperature and control three LEDs (green, yellow, red) to indicate different temperature ranges.

 **Features**  
🟢 **Green LED**: Indicates cold temperatures (< 25°C).  
🟡 **Yellow LED**: Indicates moderate temperatures (25°C - 35°C).  
🔴 **Red LED**: Indicates hot temperatures (> 35°C).  

 **Required Components**  
- Arduino Uno  
- TMP36 Temperature Sensor  
- Breadboard  
- 3 LEDs (Green, Yellow, Red)  
- 3 Resistors (220Ω)  
- Jumper Wires  

 **Connection Guide**  
- **TMP36 Temperature Sensor**:  
   - VCC: Connect to the Arduino 5V pin.  
   - OUT: Connect to the analog input pin A0.  
   - GND: Connect to the Arduino GND.  
- **LEDs**:  
   - Positive leg (long): Connect to digital pins (2 for green, 3 for yellow, 4 for red) through a 220Ω resistor.  
   - Negative leg (short): Connect to GND.  

 **Applications**  
- Monitoring room or office temperature.  
- Visual temperature alerts for different thresholds.  


![WhatsApp Image 2025-01-20 at 00 02 17_3bc2b8d8](https://github.com/user-attachments/assets/0acea4b7-a7f4-418b-ab89-abbfd5c3079a)
![WhatsApp Image 2025-01-20 at 00 02 18_ce142d34](https://github.com/user-attachments/assets/769b6119-356e-4797-80d4-14582311add3)
![WhatsApp Image 2025-01-20 at 00 02 19_40ffa556](https://github.com/user-attachments/assets/eb6e419c-304e-4552-8f24-9540a00bd5b9)


