## Why CMOS?

| Approach | Challenges |
|---|---|
| VO₂ oscillators | Device variability, fabrication complexity |
| RRAM / memristors | Forming, endurance, sneak paths |
| Analog op-amp oscillators | Higher power and component count |
| CMOS Schmitt-trigger oscillators | Standard process compatible, scalable, low power |

### Advantages of CMOS

- Compatible with standard CMOS fabrication flows
- Can be integrated with digital control logic
- Lower static power consumption
- Scales well with node count
- Suitable for future ASIC implementation

---

### Schmitt trigger (IC 7414) used for Hysteresis

<p align="center">
  <img src="../images/SchmittTriggerOscillator.png" width="45%" />
  &nbsp;&nbsp;&nbsp;
  <img src="../images/images.png" alt="IC 7414 Pinout" width="45%" />
</p>

<p align="center">
  <b>Fig. 1.</b> Schmitt Trigger Oscillator Circuit
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Fig. 2.</b> Hysteresis
</p>

### Breadboard Implementation

#### NOT Gate (2 Node)

