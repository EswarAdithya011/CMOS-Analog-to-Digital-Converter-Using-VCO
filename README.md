# **CMOS-Based ADC Using VCO and D Flip-Flops in 90nm Technology**  

## 📌 **Project Overview**  
This project presents the design and implementation of a **CMOS-Based Analog-to-Digital Converter (ADC)** utilizing a **Voltage-Controlled Oscillator (VCO)** and **D Flip-Flops (DFFs)** in **90nm technology** using **Cadence Virtuoso**. The ADC leverages a **Voltage-to-Frequency Converter (VFC)** followed by a **Frequency-to-Digital Converter (FDC)** for efficient signal processing, offering a power-optimized solution for high-speed and low-power applications.  

## ⚡ **Key Features & Achievements**  
- **Efficient Analog-to-Digital Conversion** using a VCO-based architecture.  
- **Power Optimization**: Achieved a **minimum power consumption of 124.1 µW** at the **SS corner**.  
- **Robust Circuit Design**: Designed and simulated critical submodules, including:  
  - **Voltage-Controlled Oscillator (VCO)**  
  - **D Flip-Flop (DFF) based Frequency-to-Digital Converter (FDC)**  
  - **Logic Gates (2-input & 3-input NAND)**  
- **Comprehensive Simulations**: Validated using **DC, transient, and AC response analyses** across multiple voltage levels (**0.4V, 0.6V, 0.8V, 1.0V**) and process corners (**TT, SS, FF**).  
- **Scalability**: Suitable for applications in **low-power ADCs, signal processing, and sensor interfaces**.  

## 🏗 **Project Structure**  
```plaintext
├── Schematic Designs  
│   ├── VCO Circuit  
│   ├── D Flip-Flop Circuit  
│   ├── NAND Gates (2-input, 3-input)  
│   ├── ADC Full Schematic  
│
├── Simulations  
│   ├── VCO Output Waveforms  
│   ├── DFF Waveforms  
│   ├── ADC Response at Various Voltages  
│   ├── Power Analysis (Process Corners: TT, SS, FF)  
│
└── Documentation  
    ├── Report  
    ├── Presentation Slides  
```  

## 🖥 **Software & Tools Used**  
- **Cadence Virtuoso** – Schematic design & simulation  
- **LTSpice/Xilinx Vivado (optional)** – Additional circuit validation   

## 📊 **Simulation Results**  
- **VCO Output**: Demonstrates frequency variation with input voltage.  
- **D Flip-Flop Response**: Ensures accurate frequency-to-digital conversion.  
- **Power & Corner Analysis**: Verified across NN, SS, SF, FF, FS corners (Refer to power analysis table).  

## 🚀 **Future Enhancements**  
- Implementing higher-resolution ADCs with **multi-bit quantization**.  
- Exploring **lower technology nodes(FinFET)** (18nm) for enhanced performance.  
- Optimizing VCO design for improved **linearity and phase noise reduction**.  

## 📚 **References**  
- CMOS VLSI Design by Neil Weste & David Harris  
- Analysis and Design of Analog Integrated Circuits by Paul R. Gray  
- IEEE papers on **VCO-based ADCs**  

---
```sdjfs
### 🎯 **Contributors**  
👤 **Eswar Adithya** – Circuit Design & Simulation  
👤 **Sarath Kumar Suda** – Optimization & Debugging  

Feel free to **⭐ star** this repository if you found it useful! 🚀 

---
---
