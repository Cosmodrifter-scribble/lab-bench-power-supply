# LAB BENCH POWER SUPPLY DIY

# ⚡ DIY Lab Bench Power Supply

> A fully custom-built lab bench power supply with variable CC/CV output, three fixed voltage rails, USB charging, and an AC pass-through socket — all built from scratch for under ₹6,400 (~$67 USD).

---

## 🖼️ 3D Model Preview

---

<img width="1366" height="615" alt="Screenshot 2026-05-12 104958" src="https://github.com/user-attachments/assets/f9aa3dc0-b7f3-48ea-a447-fc71b577cd65" />
<img width="1365" height="619" alt="Screenshot 2026-05-12 105020" src="https://github.com/user-attachments/assets/8516618e-1694-4cf2-b34a-05f1eb94f9e9" />
<img width="1366" height="619" alt="Screenshot 2026-05-12 104818" src="https://github.com/user-attachments/assets/6a1a1035-d2c7-40bf-87e4-b07d1195043e" />
<img width="1366" height="619" alt="Screenshot 2026-05-12 104851" src="https://github.com/user-attachments/assets/b79fb9b2-1b49-4ea2-8579-8f17d8a86546" />
<img width="1364" height="607" alt="Screenshot 2026-05-12 104910" src="https://github.com/user-attachments/assets/bafd8128-272c-4cfc-8e1f-8281c83b378c" />

---
## 💡 Why I Built This

Every electronics hobbyist eventually gets tired of powering projects from phone chargers, cheap USB banks, and borrowed wall adapters. I wanted a **single unit** that could:

- Power **3.3V microcontroller** circuits (ESP32, STM32) without brownouts
- Drive **5V** logic, Raspberry Pi, and charge Li-ion cells over USB
- Supply **12V** for motors, relays, and LED strips
- Provide a **fully adjustable 0–60V / 0–20A CC/CV output** for general lab work, battery testing, and motor characterization

Commercial bench supplies with these specs cost ₹8,000–25,000. This build delivers comparable functionality for **under ₹6,400** including shipping — and it's entirely open and modifiable.

---

## 🔧 What It Does

| Feature | Detail |
|---------|--------|
| Variable output | 0–60V, 0–20A, CC/CV via XY6020L with digital display |
| Fixed 12V rail | LM2596S buck converter, fused at 3A |
| Fixed 5V rail | LM2596S buck converter, fused at 2A + USB charging output |
| Fixed 3.3V rail | LM2596S buck converter, fused at 1A |
| AC pass-through socket | IEC C13 output for powering mains devices from the bench |
| USB charging | 2× USB ports (5V) for charging phones/devices |
| Main power switch | 250V toggle switch on AC input |
| Fused inputs | 5×20mm glass fuses on every output rail |
| Variable output terminal | 2-position screw terminal (KF7.62) for solid wire connections |

---

# 🔧 Bill of Materials — DIY Lab Bench Power Supply
> TRIDEV 36V 10A 360W PSU + XY6020L Variable Output + Fixed 12V / 5V / 3.3V Rails

> 💱 Exchange rate: **1 USD = ₹95.25**

---

## 📦 Components List

| # | Component | Qty | Unit Price (₹) | Total (₹) | Total (USD) | Source | Link |
|---|-----------|-----|----------------|-----------|-------------|--------|------|
| 1 | TRIDEV 36V 10A 360W AC-DC PSU | 1 | ₹1,769 | ₹1,769 | $18.57 | Tridev | [Buy](https://tridevpowersupply.com/product/my-tridev-36volt-10amp-360wat-switching-power-supply-universal-regulated-transformer-ac-110v-220v-to-dc-36v-10a/) |
| 2 | XY6020L 6-70V 20A 1200W CC/CV Buck Module (Variable Output) | 1 | ₹2,025 | ₹2,025 | $21.26 | Banggood | [Buy](https://www.banggood.com/XY6020L-6-70V-CNC-Adjustable-Stabilized-Voltage-Power-Supply-Constant-Voltage-Constant-Current-20A-or-1200W-Buck-Module-p-1995536.html?rmmds=detail-left-hotproducts&cur_warehouse=CN&ID=6336066&trace_id=792e1778318863213) |
| 3 | LM2596S DC-DC Step-Down Power Supply Module | 3 | ₹111 | ₹333 | $3.50 | ElectroPi | [Buy](https://www.electropi.in/lm2596s-with-smd-led-dc-dc-step-down-power-supply) |
| 4 | 4mm Banana Socket Binding Post — Red/Black Pair | 4 | ₹156 | ₹624 | $6.55 | ElectroPi | [Buy](https://www.electropi.in/4mm-banana-socket-binding-post-nut-banana-plug-jack-connector-black-red-pair) |
| 5 | Banana Plug to Alligator Clip Test Leads (Pair) | 1 | ₹89 | ₹89 | $0.93 | MakerBazar | [Buy](https://makerbazar.in/products/banana-plug-to-alligator-clip-test-leads-pair?variant=42113572897008) |
| 6 | USB Female to 2.54mm Breakout Board Module | 2 | ₹26 | ₹52 | $0.55 | ElectroPi | [Buy](https://www.electropi.in/usb-female-to-2.54mm-breakout-board-with-direct-4p-adapter-board) |
| 7 | Press Push Type Speaker Terminal Block (Variable Output Screw Terminal) | 1 | ₹349 | ₹349 | $3.66 | MakerBazar | [Buy](https://makerbazar.in/products/press-push-type-speaker-terminal-block-spring-release-connector?variant=48632428069104) |
| 8 | AC 250V 10A IEC320 C14 Male Inlet Socket with Fuse Holder (AC Input) | 1 | ₹30 | ₹30 | $0.31 | MakerBazar | [Buy](https://makerbazar.in/products/ac-250v-10a-iec320-c14-male-power-cord-inlet-socket-with-fuse-holder?variant=44619924111600) |
| 9 | IEC320 C14 Male to C13 Female Pair (AC Pass-Through Socket) | 1 | ₹20 | ₹20 | $0.21 | MakerBazar | [Buy](https://makerbazar.in/products/ac250-10a-iec320-c14-male-to-c13-female-pair?variant=48251127922928) |
| 10 | 250V Mini Toggle Switch | 1 | ₹17 | ₹17 | $0.18 | MakerBazar | [Buy](https://makerbazar.in/products/250v-mini-toggle-switch?variant=46817292681456) |
| 11 | Multifunction Digital Multimeter Test Probe / Multi Connector Kit | 1 | ₹349 | ₹349 | $3.66 | MakerBazar | [Buy](https://makerbazar.in/products/multifunction-digital-multimeter-test-probe-wire-pen-with-different-connectors-kit?variant=44739198353648) |
| 12 | 3A 250V Glass Fuse 20mm | 1 | ₹7 | ₹7 | $0.07 | ElectroPi | [Buy](https://www.electropi.in/3-amp-250v-glass-fuse-20mm) |
| 13 | 2A 250V Glass Fuse 20mm | 1 | ₹7 | ₹7 | $0.07 | ElectroPi | [Buy](https://www.electropi.in/2-amp-250v-glass-fuse-20mm) |
| 14 | 1A 250V Glass Fuse 20mm | 1 | ₹7 | ₹7 | $0.07 | ElectroPi | [Buy](https://www.electropi.in/1-amp-250v-glass-fuse-20mm) |
| 15 | Fuse Holder 20mm | 4 | ₹15 | ₹60 | $0.63 | ElectroPi | [Buy](https://www.electropi.in/fuse-holder-20mm) |
| 16 | M4 x 10mm Phillips CSK Screw (Mild Steel, Nickel) | 8 | ₹0.88 | ₹7 | $0.07 | OnlyScrews | [Buy](https://onlyscrews.in/products/m4-x-10mm-phillips-csk-mild-steel-with-nickel-plating-screw-dia-4mm-length-10mm?variant=51740028469561) |
| 17 | M4 Nut SS 304 | 10 | ₹1.20 | ₹12 | $0.13 | OnlyScrews | [Buy](https://onlyscrews.in/products/m4-nut-ss-304?variant=48892376809785) |
| 18 | M4 x 40mm Phillips CSK SS 304 Screw | 2 | ₹4.50 | ₹9 | $0.09 | OnlyScrews | [Buy](https://onlyscrews.in/products/m4-x-40mm-phillips-csk-ss-304-screw-dia-4mm-length-40mm?variant=50494911250745) |
| 19 | M3 x 8mm Phillips Pan Head Screw (Pack of 20) | 4 | ₹1.75 | ₹7 | $0.07 | OnlyScrews | [Buy](https://onlyscrews.in/products/phillips-pan-head-m3-x-8mm-pack-of-20?variant=48468586987833) |
| 20 | M3 Nut SS 304 | 4 | ₹1.00 | ₹4 | $0.04 | OnlyScrews | [Buy](https://onlyscrews.in/products/m3-nut-ss-304?variant=48892379988281) |
| 21 | AC Power Board (IEC socket board / mains distribution) | 1 | ₹10 | ₹10 | $0.10 | **Buy from local** | — |
| 22 | 3-Pin AC Wire / Power Cord Plug | 1 | ₹100 | ₹100 | $1.05 | **Buy from local** | — |

---

## 💰 Cost Summary

| Category | Cost (₹) | Cost (USD) |
|----------|----------|------------|
| Components subtotal | ₹5,886 | $61.79 |
| Shipping total | ₹475 | $4.99 |
| **Grand Total** | **₹6,361** | **$66.78** |

---

## 🛒 Buy From Local

| Component | Approx. Cost (₹) | Approx. Cost (USD) |
|-----------|-----------------|-------------------|
| AC Power Board | ₹10 | $0.10 |
| 3-Pin AC Wire Plug | ₹100 | $1.05 |

---

## 🔌 Wiring Overview

```
AC 220V Mains
    │
    ├──► [AC Pass-Through Socket] ──► External mains devices
    │
    └──► [Toggle Switch] ──► TRIDEV 36V 10A 360W PSU
                                        │
                              ┌─────────┴──────────────────────┐
                              │         36V DC Bus             │
                  ┌───────────┼──────────────┬─────────────────┤
                  │           │              │                 │
             [XY6020L]  [Buck 12V]     [Buck 5V]        [Buck 3.3V]
             CC/CV mod   LM2596S        LM2596S           LM2596S
                  │           │              │                 │
             [15A fuse]  [3A fuse]     [2A fuse]         [1A fuse]
                  │           │         ┌───┴───┐               │
           [Screw term.]  [12V ports]  [5V port] [USB/Charger] [3.3V port]
            VAR votage
            and curret

```

## 📁 Repository Structure

```
/
├── README.md           ← this file
├── BOM.md ← full bill of materials with links
├── wiring.md ← full wiring diagram 
└── 3D model/
    └── (3D model files in STL AND STEP)
```

---

*Built with ❤️ in Indore, India*
