# 🌍 World Plugs, Sockets & Voltage Dataset (JSON)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://plugwise.co)

A verified, comprehensive open-source dataset containing national electrical standards, wall socket types (IEC Types A through O), standard grid voltages, and frequencies (Hz) for 195+ sovereign countries.

This dataset powers the interactive travel matcher at **[PlugWise](https://plugwise.co)** — the free global travel power directory.

---

## 📌 Dataset Contents
* **Country Names & ISO Alpha-2 Codes**
* **Primary & Secondary Wall Socket Standards (Types A–O)**
* **National Grid Voltage (V) & Frequency (Hz)**
* **Physical Pin Configurations & Grounding Classifications**

---

## 💻 Sample Data Structure

```json
{
  "name": "Japan",
  "slug": "japan",
  "isoCode": "JP",
  "voltage": "100V",
  "frequency": "50/60Hz",
  "plugs": ["A", "B"],
  "pinDescription": "Two flat parallel blades (ungrounded Type A) and three-prong grounded (Type B)"
}
🚀 Live Interactive Explorer
To test real-time electrical compatibility, compare wall outlets side-by-side, or run high-risk device safety checks (Dyson, CPAP, hair stylers), visit:
👉 PlugWise.co
📄 License & Attribution
This dataset is open-source and licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).
You are free to share, copy, and adapt this data for any purpose (even commercially) as long as you provide appropriate attribution:
Data provided and maintained by PlugWise.
