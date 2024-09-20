# EcoSync

In today's industrial world, one of the major concerns is the energy deficit, leading to rising
energy costs and significant wastage. The hotel industry exemplifies this challenge, as it
struggles to balance energy efficiency with guest comfort.
Many hotels have implemented a key card system to automatically switch off electricity when
guests leave their rooms, aiming to conserve energy. However, this solution is not without its
flaws. When guests return, they often find their rooms uncomfortably warm and must
manually readjust the air conditioning, leading to dissatisfaction. Some hotels, to ensure
guest comfort and protect room furnishings, keep the air conditioning running even after the
key card is removed. This practice, while improving guest experience, results in considerable
energy wastage.
Therefore, the hotel industry faces a critical dilemma: how to achieve energy efficiency
without compromising guest comfort. Our startup aims to address this pressing issue by
developing an innovative solution that optimizes energy consumption while maintaining a
comfortable environment for hotel guests.

![ecosyn final ](https://github.com/user-attachments/assets/31bd4a3a-7588-401b-8b5b-15c831b7e90c)

ECOSYNC has two separate units.  
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
