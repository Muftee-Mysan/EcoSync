# ECOSYNC: Smart Energy Solution for Hotels

ECOSYNC is an innovative energy-saving solution tailored for the hotel industry. Our system bridges the gap between energy efficiency and guest comfort, addressing key challenges faced by hotels in managing air conditioning systems effectively.

---

## Problem Statement

Hotels often struggle to balance energy efficiency with guest comfort:
- **Keycard Systems** save energy but leave rooms uncomfortably warm for returning guests.
- **Keeping AC On** ensures comfort but wastes energy significantly.

### Our Solution
ECOSYNC optimizes energy usage by dynamically adjusting the air conditioning:
- When the keycard is **removed**, the AC temperature rises to conserve energy without causing discomfort.
- Upon **insertion**, the AC restores the initial, lower temperature for guest comfort.

---

## Key Features

- **Dual PCB Design**: Separate units for Keycard Presence Detection (KPD) and AC Control (ACC).
- **Bluetooth Communication**: Reliable, cost-effective signal exchange between KPD and ACC.
- **Energy Efficiency Modes**:
  - *Eco Mode*: Sets temperature to 25°C (indicated by a green LED).
  - *Luxury Mode*: Sets temperature to 23°C (indicated by a blue LED).
- **IR Sensors**: Detect keycard presence and transmit relevant signals to the AC.
- **Customizable Calibration**: Tailored implementation for each hotel room's air conditioning unit.

---


![ecosyn final ](https://github.com/user-attachments/assets/31bd4a3a-7588-401b-8b5b-15c831b7e90c)



## Technical Details

### Components Used
- **Microcontroller**: ATmega328P-PU
- **Bluetooth Modules**: HC-05 & HC-06
- **IR Proximity Sensor**: Detects keycard presence
- **IR Emitter**: Transmits AC temperature adjustment signals
- **Power Supply**: DC-DC Buck Converter with 3.7V rechargeable batteries

ECOSYNC has two seperate units
### 1. **Keycard Presence Detector (KPD)**
   - The KPD unit is a keycard holder equipped with an IR proximity sensor.
   - **Functionality**: 
     - Detects when the keycard is inserted or removed.
     - Sends a signal to the AC Controller (ACC) via Bluetooth when the keycard is removed.

### 2. **AC Controller (ACC)**
   - The ACC receives the signal from the KPD and adjusts the AC settings based on the mode selected.
   - **Modes**:
     1. **Eco Mode**:
        - Temperature is raised to 25°C.
        - Green LED indicates the Eco Mode is active.
     2. **Luxury Mode**:
        - Temperature is raised to 23°C.
        - Blue LED indicates the Luxury Mode is active.
   - The mode selection is manual and can be controlled by the hotel management.

---


## Future Improvements

- **IoT Integration**: Upgrade to Xtensa LX6 microprocessor for Wi-Fi and Bluetooth capabilities.
- **Mobile Automation**: Control via a dedicated app.
- **AI Scheduling**: Personalized temperature adjustments based on user behavior.
- **Voice Control**: Integration with virtual assistants for enhanced convenience.
- **Air Quality Enhancements**: Address CO2 levels with advanced ventilation systems.

---


