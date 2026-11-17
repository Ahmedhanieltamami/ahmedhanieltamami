<p align="center">
  <a href="https://ahmedhanieltamami.github.io/"><img src="lockup.svg" alt="AH - Ahmed Hani: PCB, firmware, IoT" width="520"></a>
</p>

### KiCad PCB design + STM32 firmware for sensor and measurement devices

I design the board in KiCad and write the firmware that runs on it, from schematic to a working prototype.
Cairo, Egypt (UTC+2/+3): a full working-day overlap with Europe and a morning overlap with the US East Coast.

**Built and fabricated**

- **24-bit USB data acquisition board**: 277 parts, STM32G474, about 3,700 lines of C including the precision ADC driver and the USB device stack.
- **Six-board gas analyser electronics**: sensing, heating, flow and control, 420 parts, all six fabricated.
- **14 field failures fixed in firmware** on a deployed industrial controller, for +3.0% flash and no hardware change.
- **FID readout**: 4,451 measured samples at 52 Hz, with a documented zero/span calibration.

**Reference designs of my own** (not fabricated, nothing measured yet)

- **Wi-Fi 6 sensor node**: ESP32-C6, USB-C charger with power path, fuel gauge, buck-boost, 4 layers on 45 × 30 mm, 0 DRC errors.
- **48 V BLDC motor driver**: STM32G431, three half bridges, FOC current sensing, CAN. Layout in progress.

**Tools:** KiCad · STM32 (C, HAL and bare metal) · Python · LTspice · Freerouting

**Portfolio:** [ahmedhanieltamami.github.io](https://ahmedhanieltamami.github.io/) · client work shown with permission, customer and product names removed.
**Hire:** through my [Upwork profile](https://www.upwork.com/freelancers/~01e4284d3324532310).
