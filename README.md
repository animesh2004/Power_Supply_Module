# ⚡ Power Supply Module PCB (12V → 5V, 3.3V)

A compact dual-output linear voltage regulator module built using **LM7805** and **AMS1117-3.3**, designed in **KiCad**. The module takes an input of 12V DC and provides regulated 5V and 3.3V outputs with basic protection and filtering.

---

## 📦 Features

- ✅ Input Voltage: 9–15V DC
- ✅ Output 1: 5V (LM7805)
- ✅ Output 2: 3.3V (AMS1117)
- ✅ Input protection diode (1N4007)
- ✅ Electrolytic capacitor filtering
- ✅ Dual screw terminal output
- ✅ Standard THT components

---

## 🔧 Tools Used

| Tool     | Version   |
|----------|-----------|
| KiCad    | v7.x      |
| Git      | Yes       |
| Gerber Viewer | Yes  |

---

## 🧩 Components

| Reference | Component       | Value     |
|-----------|------------------|-----------|
| U1        | LM7805_T0220     | 5V Regulator |
| U2        | AMS1117-3.3      | 3.3V Regulator |
| D1        | 1N4007           | Diode |
| C1–C4     | Capacitor        | 10µF |
| J1, J2    | Conn_01x02       | Input/Output |

---

## 📂 Project Files

| File/Folder     | Description                   |
|-----------------|-------------------------------|
| `Schematic/`    | KiCad schematic `.kicad_sch`   |
| `PCB/`          | PCB layout `.kicad_pcb`        |
| `Gerbers/`      | Gerber files for fabrication   |
| `Images/`       | Renders and layout screenshots |
| `README.md`     | This file                      |

---

## 🛠️ How to Use

1. Connect 9–12V DC input to J1
2. Output 1 (J2 Pin 1): 5V
3. Output 2 (J2 Pin 2): 3.3V
4. Verify pinout before powering

---

## 🖼️ Preview

### 📷 3D Render
![3D View](Images/3d_render.png)

### 📐 PCB Layout
![Top View](Images/pcb_layout.png)

---

## 📤 Gerber Export

Gerbers are available in `Gerbers/`. You can upload them directly to JLCPCB, PCBWay, or OSH Park.

---

## 📌 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Animesh Tripathi**  
Designed with 💚 in KiCad  
[GitHub Profile](https://github.com/animesh2004)

---

