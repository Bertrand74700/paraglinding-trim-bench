# 🪂 Paragliding Trim Bench — 3D Printable Measurement Jig

A low-cost, open-source jig designed for trimmer measurement on paragliding wings, using laser rangefinders and a dedicated calculation tool.

---

> ## ⚠️ IMPORTANT WARNING
>
> **Paraglider trimming is a technical and safety-critical operation.**
>
> Incorrect trimmer settings can significantly alter the flight behaviour of a wing and may lead to dangerous situations in flight.
>
> **This tool is strictly intended for trained and experienced professionals or advanced pilots who have the necessary knowledge of paraglider geometry and certification standards (EN/LTF).**
>
> If you are not familiar with paraglider line plan analysis, do not use this tool without supervision from a qualified technician or the wing manufacturer.
>
> The authors of this project accept no liability for any damage, injury, or accident resulting from improper use of this tool or incorrect trimmer adjustments.

---

## 📋 Overview

The **Trim Bench** is a 3D-printed alignment jig that holds laser rangefinders at a precise, repeatable angle and position above a paraglider wing. It enables consistent measurement of riser lengths and trimmer settings across multiple points of the wing for quality control and certification checks.

When combined with a dedicated calculation spreadsheet or the **[we-measure.io](https://we-measure.io)** web app, the bench allows technicians to:

- Measure trimmer lengths across the full wingspan
- Compare measurements against the manufacturer's reference values
- Detect asymmetries or wear-related deviations
- Document results for certification or maintenance records

---

## 📐 How It Works

### Measurement principle

The jig is positioned along the leading edge of the wing. Each axis holds a laser rangefinder pointed at a specific attachment point on the riser or line cascade. Distances are recorded and fed into the calculation tool, which computes the effective trimmer setting relative to the reference geometry.

### Recommended rangefinders

The bench is designed to be compatible with compact laser distance modules. The following are recommended:

- **Leica DISTO D1** or equivalent
- **Bosch GLM 50** or equivalent compact Bosch GLM series
- Any rangefinder with a flat front face fitting the 6 mm axis rod mount

> ℹ️ The rangefinder is **not included** — it must be sourced separately and mounted on the aluminium axis rods.

### Calculation tools

Once measurements are taken, use one of the following to process your data:

- **[we-measure.io](https://we-measure.io)** — a dedicated web application for paraglider trim analysis. No installation required, browser-based.
- A compatible **Excel / LibreOffice spreadsheet** adapted to your wing's line plan (available from wing manufacturers or certified repair stations).

---

## 🖨️ How to Print

### Recommended materials

| Material | Recommendation |
|----------|----------------|
| **PLA**  | ✅ Suitable for indoor/workshop use — easy to print, good dimensional accuracy |
| **ABS**  | ✅ Better heat and UV resistance — recommended if the bench will be used outdoors or stored in a vehicle |
| PETG     | Acceptable alternative |

### Print settings

- **Layer height:** 0.2 mm
- **Infill:** 30–40% (gyroid or honeycomb pattern recommended)
- **Perimeters / walls:** 3 minimum
- **Supports:** As needed (check orientation before slicing)
- **No special bed adhesion required for PLA**

---

## 🔩 Bill of Materials

In addition to the printed parts, you will need to purchase:

| Item | Specification | Qty |
|------|--------------|-----|
| Aluminium rod | Diameter **6 mm** | 1 length (~250 mm minimum) |
| → Axis 1 | Cut to **100 mm** | 1 |
| → Axis 2 | Cut to **100 mm** | 1 |
| → Axis 3 | Cut to **30 mm** | 1 |

The rods can be cut from a standard 6 mm aluminium bar available at most hardware stores (e.g. 300 mm or 500 mm lengths). A metal hacksaw or pipe cutter is sufficient.

> 💡 **Tip:** Lightly deburr the cut ends with fine sandpaper before inserting into the printed parts to avoid cracking the plastic.

---

## 📁 Repository Contents

```
paragliding-trim-bench/cad files/
├── stl/          — Print-ready STL files
├── step/         — Universal STEP file
├── cad source/   — Native CAD source files (Solidwork 2024)
└── images/       — Assembly images
```

---

## 📄 License

This project is released under the **CERN Open Hardware Licence v2 – Strongly Reciprocal (CERN-OHL-S)**.

You are free to use, modify, and manufacture this design, provided that any derivative work is shared under the same licence and credits the original authors.

---

## 🤝 Contributing

Feedback, improvements, and adaptations for other rangefinder models are welcome. Please open an issue or submit a pull request.

---

*Designed with ❤️ for the paragliding community.*
