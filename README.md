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

| W (Width)pmos(nm) | L (Length)pmos(nm) |  (W/L Ratio)pmos |  W (Width)nmos |L (Length)nmos |(W/L Ratio)nmos| Switching Threshold Voltage (VTC) | Drain Current (Id) (uA) | Power Consumption (P) | Propagation Delay (t_pd) (ps) | Gain (Av) | Output Resistance (Ro) |
|------|------|------------------------------------|-------------------------|-----------------------|-------------------------------|-----------|------------------------|--------------------|--------------|--------------------|-----------|
|987     | 7   |141    | 987                 |  7      | 141                           |         |                     |                     |                    |                            |        |
|1269    | 7   |181    | 987                 |  7      | 141                           |         |                     |                     |                    |                            |        |
|705     |   7 |100.71 | 987                 |   7     | 141                           |         |                     |                     |                    |                            |        |
|1128    |   7 |161.1  | 987                 |   7     | 141                           |         |                     |                     |                    |                            |        |
|1057.5  |  7  |151.07 | 987                 |   7     | 141                           |         |                     |                     |                    |                            |        |
|1057.5  | 7   |151.07 | 916.5               |   7     | 130.9                         |        |                     |                     |                   |                              |        |           
|1057.5  | 7   |151.07 | 846                 |   7     | 120.8                         |        |                     |                     |                   |                              |        |      
| 987    | 7   |141    | 916.5               |   7     | 130.9                         |        |                     |                     |                   |                              |        |      
|916.5   | 7   |130.9  | 846                 |   7     |                          |        |                     |                     |                   |                              |        |      
|775.5   | 7   |110.7  | 916.5               |   7     |                          |        |                     |                     |                   |                              |        |      
|1128    | 7   |161.1  | 1057.5              |   7     |                          |        |                     |                     |                   |                              |        |      
|1057.5  | 7   |151.07 | 1057.5              |   7     |                          |        |                     |                     |                   |                              |        |      
|1128    | 7   |161.1  | 846                 |   7     |                          |        |                     |                     |                   |                              |        |      
|916.5   | 7   |130.9  | 916.5               |   7     |                          |        |                     |                     |                   |                              |        |     
|916.5   | 7   |130.9  | 1057.5              |   7     |                          |        |                     |                     |                   |                              |        |      









## TRANSIENT ANALYSIS

![Screenshot from 2024-10-07 00-31-18](https://github.com/user-attachments/assets/0b782a1b-c7d7-4cf1-9e76-a67e3a6a9bb8)

## DC analysis

![Screenshot from 2024-10-07 01-39-06](https://github.com/user-attachments/assets/dce59d35-70f5-4e0e-977d-0bf9a0835ae2)
