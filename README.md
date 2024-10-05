# PLL-DESIGNING-BY-USING-ASAP_7nm



## 1.Voltage Transfer Characteristics (VTC) OF INVERTER
### PARAMETERS 
**Switching Threshold Voltage (VTC) :** The input voltage at which the inverter switches its output state, where the output voltage equals the input voltage.

**Drain Current (Id) :** The current flowing through the drain of the MOSFET in the inverter, typically measured in the active region of operation.

**Power Consumption (P) :** The total power dissipated by the inverter, which includes both dynamic and static power. It is given by P = VDD * Iavg.

**Propagation Delay (t_pd) :** The time taken for the output to respond to a change in the input. It's the time difference between the input signal crossing 50% of Vdd and the output reaching 50% of Vdd.

**Gain (Av) :** The ratio of the change in output voltage to the change in input voltage, typically measured at the switching threshold voltage, Av = dVout/dVin 

**HIGH Noise Margin (NMH) :** The difference between the logic low input voltage (VOH) and the maximum input voltage recognized as a low input (VIH), NML=VOH-VIH

**LOW Noise Margin (NML) :** The difference between the logic low input voltage (VIL) and the maximum input voltage recognized as a low input (VOL), NML=VIL-VOL

**Frequency (f) :** The operational frequency of the inverter, representing how fast the inverter can switch between states.

**Output Resistance (Ro) :** The small-signal resistance looking into the output of the inverter, representing how the output voltage responds to a change in output current, typically in the saturation region.

| nfin | pfin | Switching Threshold Voltage (VTC) | Drain Current (Id) (uA) | Power Consumption (P) | Propagation Delay (t_pd) (ps) | Gain (Av) | Frequency (f) (THz) | Output Resistance (Ro) |
|------|------|------------------------------------|-------------------------|-----------------------|-------------------------------|-----------|----------------------|------------------------|
| 10   | 10   | 0.35                               | 45                      | 0.5                   | 150                           | 12        | 1.2                  | 300                    |
| 12   | 10   | 0.36                               | 50                      | 0.6                   | 130                           | 14        | 1.5                  | 250                    |
| 15   | 12   | 0.37                               | 60                      | 0.7                   | 120                           | 16        | 1.8                  | 200                    |
| 18   | 15   | 0.38                               | 65                      | 0.8                   | 100                           | 18        | 2.0                  | 150                    |
| 20   | 18   | 0.40                               | 70                      | 0.9                   | 90                            | 20        | 2.2                  | 100                    |


