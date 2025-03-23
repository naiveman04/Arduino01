# Arduino-Based Smartphone Charging Controller  

## Overview  
This project is an **Arduino-powered smartphone charging controller** designed to **prevent overcharging** and **optimize battery life**. It allows users to set a **charging timer** using a **rotary encoder and LCD display**, ensuring controlled and efficient charging.  

## Features  
- 🔋 **Overcharge Protection**: Prevents excessive charging to extend battery life.  
- ⏳ **User-Controlled Charging Timer**: Users can set a timer via a **rotary encoder** and **LCD display**.  
- ⚡ **Efficient Power Management**: Automatically stops charging once the set time is reached.  
- 🔌 **Plug & Play Design**: Simple setup with an Arduino-based circuit.  

## Technologies & Tools Used  
- **Microcontroller**: Arduino UNO (or any compatible board)  
- **Programming Language**: C++ (Arduino IDE)  
- **Components**: LCD Display, Rotary Encoder, Resistors, MOSFET, Power Supply  
- **Development Environment**: Arduino IDE  

## How It Works  
1. **User sets charging time** using the rotary encoder.  
2. **The LCD display** shows the selected duration.  
3. **Once started, the system allows charging** for the specified time.  
4. **Charging is automatically cut off** after the timer expires, preventing overcharging.  

## Circuit Diagram  
![image](https://github.com/user-attachments/assets/11535053-28a1-4c2e-b888-413104d586d9)
![image](https://github.com/user-attachments/assets/61acd649-d331-4041-a1c4-a88e64fc2fd3)

## Installation & Setup  
### Prerequisites  
- Arduino IDE installed  
- Required electronic components (Arduino board, LCD, rotary encoder, etc.)  

### Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/arduino01.git
   cd arduino01
2. Open the .ino file in Arduino IDE.
3. Connect the Arduino board to your PC via USB.
4. Upload the code to your Arduino board.
5. Assemble the circuit as per the provided schematic.
