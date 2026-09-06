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
<img src="SimulatedImages/FlowChart.png" alt="Design FlowChart" width="800"/>

<br>

**Figure 2: 3D Simulation of the Antenna Array in HFSS**
<img src="SimulatedImages/Simulated_Antenna.png" alt="Simulated Antenna" width="400"/>

<br>

**Figure 3: Simulated Return Loss Plot**
<img src="SimulatedImages/Return_Loss.png" alt="Return Loss" width="400"/>

<br>

**Figure 4: Simulated VSWR Plot**
<img src="SimulatedImages/VSWR.png" alt="VSWR" width="400"/>

<br>

**Figure 5: Axial Ratio Plot**
<img src="SimulatedImages/Axial_Ratio_Plot.png" alt="Axial Ratio" width="400"/>

<br>

### 🏭 Fabricated Hardware & Testing

**Figure 6: Fabricated Antenna (Front View)**
<img src="FabricatedImages/FabricatedAntenna_Frontview.png" alt="Fabricated Antenna Front View" width="400"/>

<br>

**Figure 7: Fabricated Antenna (Back View)**
<img src="FabricatedImages/FabricatedAntenna_Backview.png" alt="Fabricated Antenna Back View" width="400"/>

<br>

**Figure 8: Measured Return Loss on VNA**
<img src="FabricatedImages/VNA_ReturnLoss.png" alt="VNA Return Loss" width="400"/>

<br>

**Figure 9: Detailed Measured Antenna Return Loss**
<img src="FabricatedImages/VNA_Antenna_ReturnLoss.png" alt="VNA Antenna Return Loss" width="400"/>

<br>

**Figure 10: Measured Smith Chart**
<img src="FabricatedImages/VNA_SmithChart.png" alt="VNA Smith Chart" width="400"/>

<br>

**Figure 11: Measured VSWR**
<img src="FabricatedImages/VNA_VSWR.png" alt="VNA VSWR" width="400"/>


<br>
## 💡 Design Justifications & Key Takeaways

**Why did I use a 2x2 Array?**
Using a single patch antenna at 2.4 GHz only provides a gain of around 6 dB. By using a 2x2 array, I was able to achieve a much higher gain of **7.49 dB**, which is critical for overcoming path loss in long-distance wireless communication.

**Why did I use the EBG (High Impedance) Structure?**
Traditional microstrip patch antennas suffer from "surface waves" that travel along the substrate. These waves cause loss of energy and reduce efficiency. By adding a Mushroom-type EBG structure, I was able to suppress these surface waves, reduce back lobe radiation, and improve the antenna's radiation efficiency from **38% to 61%**.

**Why did I use FR-4 Substrate?**
While FR-4 has a higher loss tangent compared to expensive substrates like Rogers, it was chosen for this project because of its **extremely low cost, ease of availability, and simplified fabrication process** using standard photolithography. This makes the design highly feasible for commercial mass production.

**Key Validation Step:**
One of the most important aspects of my B.E. project was ensuring the simulation matched reality. By testing the fabricated antenna with a Vector Network Analyzer (VNA), I achieved a **high correlation** between the simulated (-37.42 dB) and measured (-39.9 dB) return loss, proving the reliability of my HFSS design.

---

### 🎓 How this project connects to my PhD goals:
This project gave me hands-on experience with **Electromagnetic Simulation tools (HFSS), CAD modeling, photolithography-based fabrication, and RF testing equipment**. These skills are directly transferable to advanced research in **RF front-end design, wearable antennas, and low-power IoT communication systems**, which I aim to explore in my doctoral studies.

## 🧑‍💻 Author
**Khatija Mahveen**
- B.E. Electronics & Communication Engineering
- M.E. Embedded Systems & IoT | PhD Aspirant
- Focus: RF & Microwave Engineering, Embedded Systems

## 📜 License
This project is licensed for academic and research purposes.
