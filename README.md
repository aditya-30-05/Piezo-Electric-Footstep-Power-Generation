# ⚡ Piezoelectric Footstep Power Generation System

> Harvesting clean, renewable energy from every human step 👣

---

## 📌 Project Overview

The **Piezoelectric Footstep Power Generation System** is a renewable energy project that converts **mechanical pressure from human footsteps into electrical energy** using piezoelectric sensors.

When pressure is applied on the sensors, electrical voltage is generated, stored, and monitored using an **Arduino microcontroller**. The system is suitable for **low-power applications** and demonstrates the concept of **energy harvesting**.

---

## 🎯 Objectives

- ⚡ Generate electricity using footstep pressure  
- 🧠 Understand the working of piezoelectric sensors  
- 🌱 Promote renewable and sustainable energy solutions  
- 🏙️ Explore applications in smart cities and public infrastructure  

---

## 🧠 Working Principle

The project is based on the **piezoelectric effect**:

> Certain materials generate electrical voltage when mechanical stress is applied to them.

### Step-by-step Working:
1. Human footstep applies pressure on the piezo sensor  
2. Piezo sensor generates AC voltage  
3. Bridge rectifier converts AC to DC  
4. Capacitor stores the generated energy  
5. Arduino measures the voltage  
6. Output is displayed on a 16×2 LCD  

Using multiple piezo sensors increases the total generated output.

---

## 🛠️ Components Used

- Piezoelectric Sensors  
- Bridge Rectifier (Diodes)  
- Capacitor (Energy Storage)  
- Arduino UNO  
- 16×2 LCD Display (I2C)  
- LED (Indicator / Load)  
- Resistors  
- Connecting Wires  
- Wooden / Acrylic Base  

---

## 🔌 Circuit Diagram

- Piezo Sensor → Bridge Rectifier → Capacitor  
- Capacitor Output → Arduino Analog Pin (A0)  
- LCD (I2C) → Arduino (A4, A5)  
- LED → Arduino Digital Pin  

*(Refer to circuit diagram image in the project folder)*

---

## 📈 Power & Energy Calculation

### Voltage Calculation:




> Note: Generated power is in **milliwatts**, suitable only for low-power devices.

---

## 📟 Output Display

- LCD displays:
  - Generated Voltage
  - Total Footsteps Count
- LED glows when a footstep is detected

---

## 🔌 Applications

- 🚉 Railway stations  
- 🛍️ Shopping malls  
- 🚶 Footpaths and walkways  
- 🏙️ Smart cities  
- 🔋 Energy harvesting systems  
- 🌐 IoT-based low-power devices  

---

## 🌱 Advantages

- ♻️ Renewable and eco-friendly  
- 🌍 Pollution-free energy  
- 🔧 Low maintenance  
- 👣 Utilizes wasted human energy  
- 🔌 Ideal for demonstration and research  

---

## ⚠️ Limitations

- 🔋 Low power output  
- 🚶 Depends on foot traffic  
- 📉 Output varies with pressure applied  

---

## 🚀 Future Scope

- 🔋 Improved energy storage systems  
- 📊 IoT-based energy monitoring  
- 🧠 Smart floor integration  
- 🌐 Smart grid connectivity  
- 🏢 Large-scale public deployment  

---

## 📌 Conclusion

The **Piezoelectric Footstep Power Generation System** proves that small amounts of energy can be harvested from daily human activities. While it cannot replace conventional power sources, it plays a vital role in **sustainable energy awareness** and **smart infrastructure development**.

---



