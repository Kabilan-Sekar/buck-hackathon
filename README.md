# buck-hackathon
# Buck Converter Design Project

This repository contains the design files, simulation results, and PCB layout for a **Buck Converter** (step-down DC-DC power converter).

---

## 📂 Repository Structure

| Folder | Contents | Key Files Included |
| :--- | :--- | :--- |
| `design/` | Simulation models and control loop analysis. | `finalbuck.slk`, `bode_plot.png`, `waveforms.png` |
| `pcb/` | Printed Circuit Board (PCB) fabrication and assembly files. | `layout.kicad_pcb`, `schematic.kicad_sch`, `bom.xlsx` |
| (root) | General project documentation and high-level files. | `bonus_task.pdf`, `control_diagram.pdf` |

---

## 🛠️ Design and Analysis Files (`design/` folder)

* **`finalbuck.slk`**: The main **Simulink Model** used for the transient and steady-state simulation of the converter.
* **`bode_plot.png`**: Image showing the **Bode Plot** of the control loop, critical for verifying stability (phase and gain margins).
* **`waveforms.png`**: Image of key **time-domain waveforms** from the simulation (e.g., output voltage ripple, inductor current).
* **`notes.txt`**: General observations and design notes.

---

## 🔩 PCB Files (`pcb/` folder)

The PCB was designed using **KiCad Board 9.0**.

* **`schematic.kicad_sch`**: The complete circuit diagram and component definitions.
* **`layout.kicad_pcb`**: The physical board layout and routing.
* **`bom.xlsx`**: The **Bill of Materials (BOM)** listing all required components for assembly.

---

## 📄 Documentation (Root directory)

* **`control_diagram.pdf`**: PDF detailing the **control strategy** and block diagram used for the feedback system.
* **`bonus_task.pdf`**: Document related to an extended design specification or analysis task.
