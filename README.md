# Counter_OpenLane
# 4-bit Counter using OpenLane and Sky130

This is a simple 2-bit up-counter implemented in Verilog and synthesized using the OpenLane flow with Sky130 PDK.

## Project Structure

- `counter/src/counter.v`: Verilog RTL code for the counter
- `counter/config.json`: OpenLane configuration
- `counter/pin_order.cfg`: Optional pin order file
- `openlane/`: Reference to OpenLane flow

## How to Run

### Prerequisites
- Docker installed
- OpenLane installed (see: https://github.com/The-OpenROAD-Project/OpenLane)
- Sky130 PDK installed or auto-downloaded via OpenLane

### Steps

1. Clone this repo:
   ```bash
   git clone https://github.com/Awaizlogde/counter_openlane.git
   cd counter_openlane
