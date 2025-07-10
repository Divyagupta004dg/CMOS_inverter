# CMOS Inverter Design, Simulation, and Characterization using Sky130 PDK

This project demonstrates the complete design, simulation, and electrical characterization of a CMOS inverter using the open-source **Sky130 PDK**.

Both **SPICE-based simulation** and **schematic-level waveform analysis** have been performed. The project is implemented using the **Xschem + Ngspice + Sky130 PDK (Volare)** setup on Ubuntu Linux.

---

## 🔧 Tools Used

| Tool     | Purpose                           |
|----------|-----------------------------------|
| Xschem   | Schematic design                  |
| Ngspice  | DC/Transient simulation           |
| Sky130 PDK | Process Design Kit (via Volare) |
| Magic (Optional) | Layout design              |
| Netgen / KLayout (Optional) | LVS / DRC checks |

---

## 📁 Directory Structure

```bash
CMOS_inverter/
├── spice/                     # SPICE netlists
│   ├── inverter_dc.spice
│   ├── inverter_tran.spice
│   └── inverter_characterization.spice
├── screenshots/               # All waveform outputs
│   ├── vtc_plot.png
│   ├── transient_response.png
│   ├── delay_waveform.png
│   ├── rise_fall_times.png
│   ├── power_plot.png
├── layout/                    # (Optional) Magic layout files
│   ├── inverter.mag
│   └── inverter.ext
├── README.md
└── CMOS_Inverter_Report.pdf   # Full formatted report (optional)
