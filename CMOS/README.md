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

---

### Breadboard Implementation

#### - NOT Gate (2 Node)

<p align="center">
  <img src="../images/2node_output.jpg" alt="Description" width="60%">
</p>

<p align="center">
  <b>Fig. 1.</b> 2 node coupled with a capacitor acting like a NOT gate
</p>

#### - 2x2 (4 Node)

<p align="center">
  <img src="../images/4node_circuit.jpg" width="45%" />
  &nbsp;&nbsp;&nbsp;
  <img src="../images/4node_output.jpg" alt="IC 7414 Pinout" width="45%" />
</p>

<p align="center">
  <b>Fig. 1.</b> 4 Node Maxcut Circuit on Breadboard
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Fig. 2.</b> Output waveforms for the four nodes on Oscilloscope.
</p>


#### - 3x2 (6 Node)

<p align="center">
  <img src="../images/6node_circuit.jpg" width="45%" />
  &nbsp;&nbsp;&nbsp;
  <img src="../images/6node_output.jpg" alt="IC 7414 Pinout" width="45%" />
</p>

<p align="center">
  <b>Fig. 1.</b> 6 Node Maxcut Circuit on Breadboard
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Fig. 2.</b> Output waveforms for the six nodes on Oscilloscope.
</p>

#### - 4x2 (8 Node)

<p align="center">
  <img src="../images/8node_circuit.jpg" width="20%" />
  &nbsp;
  <img src="../images/8node_output_1.jpg" width="20%" />
  &nbsp;
  <img src="../images/8node_output_2.jpg" width="20%" />
</p>

<p align="center">
  <b>Fig. 1.</b> Circuit on Breadboard
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Fig. 2.</b> Output waveforms of four of the eight nodes
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <b>Fig. 3.</b> Output waveforms of the other four nodes
</p>


