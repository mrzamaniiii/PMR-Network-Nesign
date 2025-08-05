# Shahr-e Bābak PMR Network Design

Design and simulation of a Private Mobile Radio (PMR) network for Shahr-e Bābak City, Iran, using Radio Mobile software.  
The project features VHF and microwave link configurations, optimized repeater placement, and comprehensive coverage analysis (~99.78% area coverage).

---

## Project Overview
This project aims to deliver a robust, wide-area PMR network for both digital voice and data transmission.  
The network covers a 100 km × 100 km area with Shahr-e Bābak at the center, providing reliable communication between users and the operations center.

---

## Network Design

### VHF Links
- **Frequency:** 166 MHz  
- **Modulation:** ETSI Digital Mobile Radio (DMR)  
- **Mobile Units:** Motorola DM4000e (40 W, sensitivity 0.18 µV)  
- **Repeaters:** Motorola SLR5500 (50 W, gain 5 dBi, height 10 m)

### Microwave Links
- **Frequencies:** 7–38 GHz (depending on link distance)  
- **Configuration:** Each repeater connects to at least two others for redundancy  
- **Antennas:** THP 08 100 D WB, gain 36.7 dBi, diameter 0.8 m

---

## Results
- **Coverage Area:** ~9978 km² (**99.78%** of target region)  
- **Safety Margin:** ≥ 10 dB above modulation threshold for all links  
- **Repeaters Used:** 3 strategically placed at elevated sites  
- **Microwave Connectivity:** All links clear line-of-sight

---

## Project Files
- **PDF & PPTX Report** – Detailed technical documentation and presentation  
- **Radio Mobile Files** – `.dat`, `.net`, `.geo`, `.inf`, and coverage maps (`.bmp`)  

---

## Key Features
- Wide-area digital voice & data PMR network
- Optimized repeater placement for cost-efficiency
- Dual VHF & microwave link design
- High reliability with redundancy
- Scalable for future expansions

## 👤 Authors
- Mohammadreza Zamani  
- Asal Abbas Nejad Fard  

Supervisor: Prof. Michele D’Amico
