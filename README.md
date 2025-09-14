# Analog & Mixed-Signal IC Design Portfolio

This repository showcases key projects from the "Analog Mixed-Signal" course at National Taiwan University of Science and Technology (NTUST). All circuits were designed and simulated using the Cadence Virtuoso platform.

---

## 1. High-Performance Folded-Cascode OP-amp

### Project Description
Designed a Folded-Cascode operational amplifier with a constant-gm input stage to achieve both high bandwidth and a rail-to-rail input common-mode range.

### Specifications & Results
| Parameter              | Target (規格) | Achieved (模擬成果) |
| ---------------------- |:-------------:|:-------------------:|
| Gain-Bandwidth (GBW)   |    > 1 GHz    |      > 1 GHz       |
| Phase Margin (P.M)     |     > 60°     |  60.87° |
| Power Supply           |     1.8 V     |       1.8 V         |


### Schematics & Plots
**Final Schematic:**
![OP-amp Folded Cascode Rail to Rail with Constant Gm Schematic](<<img width="1128" height="342" alt="image" src="https://github.com/user-attachments/assets/47c93a01-5566-4e45-b7d0-378ca296e0b4" />

>)
>![OP-amp Folded Cascode Rail to Rail Schematic](<<img width="1039" height="347" alt="image" src="https://github.com/user-attachments/assets/3e157617-1d45-47f7-ad08-8b696aaafe0d" />
>)

**AC Simulation (Gain & Phase):**
![OP-amp AC Plot](<<img width="949" height="438" alt="image" src="https://github.com/user-attachments/assets/ed80cbf3-3baa-4a48-99d8-3802f3443023" />
>)

---

## 2. Sallen-Key Low-Pass Filter

### Project Description
Implemented a high-order low-pass filter using the Sallen-Key architecture, designed to meet specific pass-band and stop-band requirements.

### Schematics & Plots
**Frequency Response:**
![Filter AC Plot](<<img width="1552" height="714" alt="image" src="https://github.com/user-attachments/assets/2e03f1e9-8f63-46d6-8950-7357ad23883e" />
>)

---

## 3. High PSRR, Low Tempco Bandgap Reference

### Project Description
Designed a stable voltage reference circuit with high power supply rejection and low sensitivity to temperature variations.

### Specifications & Results
| Parameter                  | Result (模擬成果)            |
| -------------------------- |:---------------------------:|
| Temperature Coefficient    | 10.44 ppm/°C                |
| Power Supply Rejection Ratio (PSRR) | -42dB @ 1kHz] |

### Schematics & Plots
**Output Voltage vs. Temperature:**
![Bandgap Tempco Plot](<<img width="738" height="458" alt="image" src="https://github.com/user-attachments/assets/ac1d63bd-d7db-4e89-a6bb-59ca8faff276" />
>)
