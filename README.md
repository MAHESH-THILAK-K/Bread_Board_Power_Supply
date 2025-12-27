

# Bread Board Power Supply

**Board Render**

A compact and easy-to-use breadboard power supply PCB designed to deliver stable, regulated DC power for electronics prototyping. This board plugs directly into standard solderless breadboards and provides clean **5V and/or 3.3V outputs**, making it ideal for students, hobbyists, and embedded system developers.

The design focuses on simplicity, reliability, and beginner-friendly usage for powering microcontrollers, sensors, and logic circuits during development and testing.

---

## 📌 Key Features

### Power Regulation

* Regulated **5V and/or 3.3V DC output**
* Linear voltage regulators for low-noise operation
* Suitable for low-power electronic circuits

### Input Power

* DC input via connector
* Input filtering for stable voltage supply
* Reverse polarity and basic protection (as per schematic)

### Breadboard Compatibility

* Designed to plug directly into breadboard power rails
* Eliminates external power wiring
* Compact footprint for easy placement

### User Indicators

* Power indication LED
* Optional voltage selection (based on design)

---

## 📂 Repository Structure

```
Bread-Board-Power-Supply/
│
├── README.md                # Project documentation
├── LICENSE                  # Open-source license
├── Hardware/
│   ├── Schematic/           # KiCad schematic files (.kicad_sch)
│   ├── PCB/                 # KiCad PCB layout files (.kicad_pcb)
│   └── Gerber/              # Gerber files for manufacturing
├── 3DModels/                # STEP / 3D models (optional)
└── Images/                  # Board renders, photos, diagrams
```

---

## 🛠️ Hardware Overview

### Voltage Regulation

* Linear voltage regulators for 5V / 3.3V output
* Decoupling and filtering capacitors for noise reduction
* Stable output suitable for MCUs and sensors

### Power Distribution

* Direct connection to breadboard power rails
* Even voltage distribution across rails
* Designed for safe current levels

### Indicators & Controls

* Power LED for visual confirmation
* Simple, minimal component design

---

## 🚀 Usage Instructions

1. Insert the PCB into the breadboard power rails.
2. Connect a suitable DC power source.
3. Verify output voltage using a multimeter.
4. Power your breadboard circuits directly from the rails.

No additional wiring or setup is required.

---

## 📄 Manufacturing

The `Hardware/Gerber/` folder includes:

* Top and Bottom copper layers
* Solder mask layers
* Silkscreen layers
* Drill files
* Board outline

These files are ready for fabrication with PCB manufacturers such as **PCBWay**, **JLCPCB**, or **OSH Park**.

---

## 📸 Images & Diagrams

Board renders, PCB layout screenshots, and usage diagrams are available in the:

```
Images/
```

---

## 📜 License

This project is released as **open-source**.
You may choose a suitable license such as:

* CERN-OHL-P-2.0 (recommended for hardware)
* MIT License

---

## 🙌 Contributions

Contributions, improvements, and documentation updates are welcome.
Feel free to open issues or submit pull requests.

---

## 📧 Contact

For questions, suggestions, or collaboration ideas, please open an issue in this repository.

---

