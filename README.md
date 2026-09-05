# Circularly Polarized Patch Antenna Array using High Impedance Surface (EBG)

## 📌 Overview
This project focuses on the design, simulation, fabrication, and characterization of a 2x2 Circularly Polarized Patch Antenna Array operating at the 2.4 GHz ISM band. To overcome the inherent limitations of microstrip patch antennas (such as narrow bandwidth and surface wave losses), a Mushroom-type Electromagnetic Band Gap (EBG) structure is integrated as a high-impedance ground plane.

## 🧠 Motivation & Research Context
Microstrip patch antennas are essential for modern wireless communication, but they suffer from low gain, narrow bandwidth, and surface wave propagation issues. This project addresses these challenges by implementing an EBG structure to suppress surface waves, reduce back lobe radiation, and enhance overall antenna efficiency, making it suitable for Wi-Fi, Bluetooth, and satellite communication applications.

## 🛠️ Technologies & Tools Used
- **Simulation Tool:** ANSYS HFSS (High Frequency Structure Simulator)
- **Substrate:** FR-4 (Dielectric constant: 4.4, Thickness: 1.6 mm)
- **Fabrication:** Photolithography (Photo-etching process)
- **Testing:** Vector Network Analyzer (VNA)
- **Feeding Technique:** Inset / Microstrip Line Feed
- **Polarization Technique:** Truncated Edges (Circular Polarization)

## 📊 Results & Validation
- **Resonant Frequency:** 2.4 GHz
- **Return Loss (Simulated):** -37.42 dB
- **Return Loss (Measured):** -39.9 dB
- **VSWR:** 1.02 (Simulated) | 1.03 (Measured)
- **Gain:** 7.49 dB (Simulated) | 8.02 dB (Measured)
- **Bandwidth:** 180 MHz
- **EBG Reflection Phase Bandwidth:** 390 MHz
- **Radiation Efficiency:** Improved from 38% to 61% with EBG
- **Correlation:** High correlation achieved between simulated and measured results.

## 🖼️ Project Images

### 📊 Simulated Results (HFSS)

**Figure 1: Flowchart showing design methodology**
<img src="SimulatedImages/Flowchart.png" alt="Design Flowchart" width="600"/>

<br>

**Figure 2: 3D Simulation of the Antenna Array in HFSS**
<img src="SimulatedImages/Simulated_Antenna.png" alt="Simulated Antenna" width="350"/>

<br>

**Figure 3: Simulated Return Loss Plot**
<img src="SimulatedImages/Return_Loss.png" alt="Return Loss" width="350"/>

<br>

**Figure 4: Simulated VSWR Plot**
<img src="SimulatedImages/VSWR.png" alt="VSWR" width="350"/>

<br>

**Figure 5: Axial Ratio Plot**
<img src="SimulatedImages/Axial_Ratio_Plot.png" alt="Axial Ratio" width="350"/>

<br>

### 🏭 Fabricated Hardware & Testing

**Figure 6: Measured Return Loss on VNA**
<img src="FabricatedImages/VNA_ReturnLoss.png" alt="VNA Return Loss" width="350"/>

<br>

**Figure 7: Additional VNA Return Loss Result**
<img src="FabricatedImages/VNA_ReturnLoss_Antenna.png" alt="VNA Return Loss Antenna" width="350"/>

<br>

**Figure 8: Measured Smith Chart**
<img src="FabricatedImages/VNA_SmithChart.png" alt="VNA Smith Chart" width="350"/>

<br>

**Figure 9: Measured VSWR**
<img src="FabricatedImages/VNA_VSWR.png" alt="VNA VSWR" width="350"/>

<br>

## 🧑‍💻 Author
**[Your Name]**
- B.E. Electronics & Communication Engineering
- M.E. Embedded Systems & IoT | PhD Aspirant
- Focus: RF & Microwave Engineering, Embedded Systems

## 📜 License
This project is licensed for academic and research purposes.
