# 📡 PMR Network Design for Shahr-e Bābak

This repository presents the design and simulation of a **Private Mobile Radio (PMR)** network using Radio Mobile software, covering an area of 100 km x 100 km centered around Shahr-e Bābak, Iran.

The goal of this project is to ensure robust digital voice and data coverage using a minimal yet strategically optimized repeater network.

---

## 📁 Contents

- 📝 `Wireless And Mobile Propagation Project.pdf` – Complete project report with all configurations and coverage analysis.
- 🎞️ `Wireless And Mobile Propagation Project.pptx` – Presentation slides summarizing network design and results.
- 📐 Diagrams and simulation results from Radio Mobile (included in PDF).
- 📶 Technical specifications of all VHF and microwave components.

---

## 🛰️ Technologies Used

- **Radio Mobile software** for link and coverage simulation
- **ETSI DMR (Digital Mobile Radio)** for VHF communication
- **Microwave backhaul** operating at 10 GHz
- **Motorola DM4000e** and **SLR5500** equipment specifications

---

## 📡 Network Overview

### 🔹 Mobile Unit
- Frequency: 166 MHz (VHF)
- Transmit Power: 40 W
- Sensitivity: 0.18 µV
- Antenna Gain: 0 dBi

### 🔹 Repeater
- Type: Motorola SLR5500 (DMR)
- Output Power: 50 W
- Gain: 5 dBi
- Height: 10 meters

### 🔹 Microwave Links
- Frequency Bands: 7–10 GHz (Long Haul), up to 38 GHz (Urban)
- Minimum requirement: Each repeater must connect to at least 2 others
- Antenna Gain: 36.7 dBi
- Wind-resistant industrial design

---

## 🌍 Coverage Results

- **Total Area Covered**: ~9978 km² (99.78% of the target region)
- All repeaters have 10 dB+ link margin over modulation threshold
- Full connectivity and redundancy via microwave loops

---

## ✅ Key Highlights

- 📶 Full PMR network coverage with just 3 repeater stations+*
- 🧭 Terrain-aware positioning using elevation & LoS
- 🔁 VHF downlink with microwave backhaul for redundancy
- 📈 High signal integrity & low infrastructure cost
