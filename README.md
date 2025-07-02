# 4 -bit Counter_OpenLane
# Counter - OpenLane Physical Design Project

This project implements a simple digital counter using Verilog and performs full RTL-to-GDSII flow using OpenLane and the Sky130 PDK.

## 📁 Project Structure

- `counter/src/counter.v` — RTL code for the counter
- `counter/config.json` — OpenLane configuration for the design
- `runs/counter_run/results/final/gds/counter.gds` — Final GDSII layout output
- `runs/counter_run/results/final/mag/counter.mag` — magic layout output
- 
## 🧰 Tools Used

- [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane)
- Sky130A Process Design Kit (PDK)

## 🔍 Viewing Layout

You can view the layout using Magic or KLayout:
```bash
magic -T sky130A.tech runs/counter_run/results/final.gds

## 💬 Ask Questions

Have questions or suggestions? Start a discussion in the [Discussions tab](../../discussions)
