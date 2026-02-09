# **ZX Spectrum Issue 3B — KiCad Reconstruction**

A faithful KiCad recreation of the **Sinclair ZX Spectrum Issue 3B motherboard**, reconstructed from original Gerber data and fully validated through multiple successful builds.  
This project preserves the 3B layout in an editable, open format and includes several companion PCBs designed to modernise, repair, or enhance the original Spectrum hardware.

---

## 🧭 Project Purpose

The aim of this repository is to provide a clean, accurate, and reproducible version of the Issue 3B board for:

- Restoring original machines  
- Building new units from scratch  
- Hardware experimentation and modding  
- Long‑term preservation of Sinclair’s design  

All PCBs included here have been **physically manufactured and tested**.

---

## 🛠️ Included PCBs

### **✔️ Issue 3B Motherboard (KiCad Reconstruction)**  
A complete KiCad recreation of the original Issue 3B board.

- Rebuilt directly from Gerbers  
- Trace‑accurate routing  
- Multiple boards assembled and working perfectly  
- Compatible with original components and modern equivalents  

---

### **✔️ Coil Replacement PCB**  
A compact, reliable drop‑in replacement for the original Spectrum coil assembly.

- Tested and working  
- More consistent output than ageing originals  
- Builder‑friendly footprint and assembly  

---

### **✔️ Composite Mod PCB (Internal Modulator Replacement)**  
This PCB is designed to **fit inside the original RF modulator can**, replacing the internal circuitry while keeping the metal can for authenticity.

- Produces a clean composite video output  
- Eliminates RF noise and modulator‑related issues  
- Fully validated on real hardware  
- Ideal for restorations where the external appearance should remain original  

---

### **✔️ Composite Modulator Replacement PCB**  
A full PCB replacement for the RF modulator can itself.

- Suitable for new builds or heavily damaged modulators  
- Provides modern composite output in a clean, serviceable form  
- Tested and working  

---

## 🧩 Issue 3B Schematic (Work in Progress)

A full schematic for the **Issue 3B motherboard** is currently being drafted.  
It lives in the main **`/src`** directory alongside the KiCad PCB project and is already far enough along to be useful for reference, verification, and troubleshooting.

- Based on the reconstructed PCB  
- Continuously refined as traces and nets are validated  
- Intended to become a complete, accurate representation of the 3B circuitry  
- A PDF export is also included in **`/images`** for quick viewing

This schematic will evolve as the project progresses, but it is already a solid and reliable companion to the board reconstruction.

---

## 📁 Repository Structure

| Path | Description |
|------|-------------|
| `/src` | KiCad project files for the Issue 3B board |
| `/zx_coil` | Coil replacement PCB |
| `/zx_composite_mod` | Composite mod PCB (internal modulator replacement) |
| `/zx_composite_modulator` | Full modulator replacement PCB |
| `README.md` | Project overview |

---

## 🔧 Build Status

All PCBs in this repository have been **successfully manufactured, assembled, and tested**.

| PCB | Status |
|-----|--------|
| Issue 3B Motherboard | ✅ Working |
| Coil Replacement PCB | ✅ Working |
| Composite Mod PCB | ✅ Working |
| Composite Modulator PCB | ✅ Working |

---

## 📐 About the Issue 3B Revision

The Issue 3B is one of the later 48K Spectrum board revisions, featuring:

- Improved manufacturing consistency  
- Minor routing and grounding refinements  
- Updated power regulation layout  
- Compatibility with both early and late ULAs  

This reconstruction preserves the original routing and component placement as closely as possible.

---

## 🚀 How to Use This Project

### **Open in KiCad**
```bash
git clone https://github.com/Bambleweeny57/zxspectrum_issue3b
