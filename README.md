# 🚛⚡ **Fuzzy Logic Fuel Injection Controller**  

A **fuzzy logic controller** designed to regulate fuel flow based on **vehicle speed**, **load**, and **engine RPM**. Developed as part of the **AI Techniques (MOD006564)** module at **Anglia Ruskin University**, this project demonstrates the power of **fuzzy inference systems (FIS)** for real-time decision-making.

---

## 📂 **Repository Contents**  

- **Supporting Documents**: Project brief, assignment instructions, and other materials provided by the university.  
- **Visual Outputs**: Membership function graphs and 3D surface plots illustrating system behaviour.  
- **MATLAB Implementation**: Core logic for the fuzzy fuel controller (includes `.m` script and fuzzy inference system files).
- **Important Note**: The **MATLAB code**, **FIS files**, and the **final report** have been **excluded** from this repository to maintain academic integrity and comply with university guidelines.

---

## 🧠 **About the Project**

This project uses **fuzzy logic** to control **fuel flow** based on three key vehicle parameters:
- **Speed** (1–120 mph)  
- **Load** (100–1000 kg)  
- **RPM** (1000–6000)

The fuzzy logic controller uses **membership functions** to interpret the inputs and calculates a **continuous fuel output** between **0.5–3.5 L/h**. The system provides smooth and adaptive fuel flow adjustment without abrupt transitions, making it ideal for real-time automotive applications.

---

## 📊 **Visual Outputs**  

Below are the **MATLAB-generated membership functions** and **3D surface plots** used to validate the system’s performance.

---

### 🔹 **Speed Membership Functions**  
![Speed Membership Functions](Graph%20Pictures/Speed%20Membership%20Functions.png)  
_This graph visualises the fuzzy membership functions for speed: Slow, Medium, Fast, and Very Fast._

---

### 🔹 **Load Membership Functions**  
![Load Membership Functions](Graph%20Pictures/Load%20Membership%20Functions.png)  
_The load membership function graph displays fuzzy categories for vehicle load: Light, Medium, Heavy, and Very Heavy._

---

### 🔹 **RPM Membership Functions**  
![RPM Membership Functions](Graph%20Pictures/RPM%20Membership%20Functions.png)  
_This graph shows how RPM is categorised into Green, Yellow, Orange, and Red zones, indicating increasing engine strain._

---

### 🔹 **Fuel Output Membership Functions**  
![Fuel Output Membership Functions](Graph%20Pictures/Fuel%20Output%20Membership%20Functions.png)  
_This graph illustrates the fuzzy membership functions for fuel output, ranging from Very Low to Very High._

---

## 🌐 **3D Fuzzy Surface Plots**  

These surface plots illustrate the relationship between inputs (speed, load, RPM) and fuel output. The plots show how fuel flow logically increases as speed, load, and RPM rise.

---

### 🔸 **Speed vs RPM → Fuel Output**  
![Speed vs RPM vs Fuel](Graph%20Pictures/Speed%20vs%20RPM%20vs%20Fuel.png)  
_This 3D surface plot shows how the controller adjusts fuel flow as vehicle speed and RPM change._

---

### 🔸 **Load vs RPM → Fuel Output**  
![Load vs RPM vs Fuel](Graph%20Pictures/Load%20vs%20RPM%20vs%20Fuel.png)  
_This plot demonstrates how higher load and RPM increase fuel output, confirming the system’s correct behaviour._

---

## 🧩 **How the System Works**

### **Fuzzy Logic**:  
The system uses fuzzy sets to categorise the inputs (speed, load, RPM). The fuzzy sets allow smooth transitions between states, ensuring **human-like reasoning** for fuel flow adjustments.

### **Rule Base**:  
The controller’s rule base consists of simple **if-then rules** to produce the fuel output. The rules are based on logical combinations of input variables, such as "IF Speed IS Fast AND Load IS Heavy THEN Fuel IS High".

### **Surface Plots**:  
Surface plots provide a visual representation of how input variables interact with the fuel output. The system’s output is continuous and smooth, as shown by the surface plots, confirming its capability to handle real-time adjustments.

---

## 🛠️ **Installation & Usage**

To replicate or test the fuzzy logic system, you will need:

1. **MATLAB** with the **Fuzzy Logic Toolbox** installed.

### **Steps to Run the System**:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/QuantumAlchemist03/fuzzy-fuel-injection-controller.git


   # 🚫 **Academic Integrity**

The **MATLAB code** and **FIS files** are excluded from this repository to adhere to **academic integrity** and **university guidelines**.  
Additionally, **final reports** and **assignment-sensitive files** have been **omitted** to ensure full compliance with **university submission protocols**.

---

# 🌌 **Conclusion**

This project demonstrates the use of **fuzzy logic** in real-time systems. By applying fuzzy inference systems (FIS), the controller adapts dynamically to inputs such as **speed**, **load**, and **RPM**. The system ensures **smooth fuel flow** adjustment based on human-understandable fuzzy sets, replacing traditional logic-based control systems with **more adaptable** and **human-like reasoning**.

Feel free to explore the **visual outputs** of the fuzzy system and how it reacts to different conditions in real-time.

---

# 📜 **Custom License**

This repository is for **academic reference** and **educational purposes only**.  
All the files, code, and documents in this repository are **not for commercial use** and are provided under the following terms:

- **Non-Commercial Use**: You may use, copy, modify, or distribute this code and its components for **educational** and **academic** purposes only.
- **Academic Use Only**: You may use this project and its materials for your own academic work or for reference but may not use it for **any commercial purposes**.
- **No Warranty**: The code and materials are provided "as is," with no warranty or guarantee of any kind, either expressed or implied.

---

**Disclaimer**: This license is specifically designed for **educational and academic purposes**. If you wish to use this work outside of the scope of educational activities (e.g., for commercial or professional projects), you must seek permission from the original author (Alif Sathar) and abide by the licensing terms agreed upon.

