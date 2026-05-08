# Circuit Design — ICS 4111: Embedded Systems & IoT

**Practical Exercise 2**

This repository contains circuit design work completed as part of the ICS 4111 Embedded Systems & IoT unit. It includes DC circuit calculations and EasyEDA schematic diagrams.

---

## Repository Structure

```
Circuit-Design/
├── Arduino Nano.png       # Arduino Nano DHT 22
├── Series Schema.pdf          # EasyEDA schematic — series circuit
├── Parallel Schema.pdf        # EasyEDA schematic — parallel circuit
└── pe2.pdf        # Calculations
```

---

## Part A — Circuit Calculations

### Circuit A: Series Circuit
**Supply:** 125 V | **Resistors:** R1 = 20 Ω, R2 = 30 Ω, R3 = 50 Ω

| Parameter | Value |
|---|---|
| Total Resistance | 100 Ω |
| Total Current | 1.25 A |
| Voltage Drop — R1 | 25.00 V |
| Voltage Drop — R2 | 37.50 V |
| Voltage Drop — R3 | 62.50 V |
| Power — R1 | 31.250 W |
| Power — R2 | 46.875 W |
| Power — R3 | 78.125 W |

### Circuit B: Parallel Circuit
**Supply:** 125 V | **Resistors:** R1 = 20 Ω, R2 = 100 Ω, R3 = 50 Ω

| Parameter | Value |
|---|---|
| Total Resistance | 12.5 Ω |
| Total Current | 10 A |
| Voltage Drop (all branches) | 125 V |
| Current — R1 | 6.25 A |
| Current — R2 | 1.25 A |
| Current — R3 | 2.50 A |
| Power — R1 | 781.25 W |
| Power — R2 | 156.25 W |
| Power — R3 | 312.50 W |

---

## Part B — Schematic Diagrams

### Circuit A & B Schematics
Designed using [EasyEDA](https://easyeda.com). Each schematic includes a component table listing all parts used.

### Arduino Nano + DHT22 Sensor
A schematic showing an Arduino Nano microcontroller interfaced with a DHT22 temperature and humidity sensor, with a 10 kΩ pull-up resistor on the data line.

| Designator | Component | Value |
|---|---|---|
| U2 | Arduino Nano | ATmega328P, 5V |
| U3 | DHT22 Sensor | 3.3V – 5V |
| R1 | Pull-up Resistor | 10 kΩ |

---

## Tools Used
- [EasyEDA](https://easyeda.com) — Schematic design
- Ohm's Law & Watt's Law — Circuit calculations

---


