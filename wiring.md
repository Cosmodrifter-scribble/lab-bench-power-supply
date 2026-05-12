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
            variable votage
            and curret

```
## more detail diagram

<img width="1408" height="768" alt="Gemini_Generated_Image_1fdo9n1fdo9n1fdo" src="https://github.com/user-attachments/assets/ba7da768-c6e4-4138-8865-0723b1d9f119" />




