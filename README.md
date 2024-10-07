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

| W (Width)pmos(nm) | L (Length)pmos(nm) |  (W/L Ratio)pmos |  W (Width)nmos(nm) |L (Length)nmos(nm) |(W/L Ratio)nmos| Switching Threshold Voltage (VTC)(v) | Drain Current (Id) (uA) | Propagation Delay (t_pd) (ps) | Gain (Av) | Noise Margin (NMH) |Noise Margin (NML) |
|------|------|------------------------------------|-------------------------|-----------------------|-------------------------------|-----------|------------------------|--------------------|-------------|------------|-----------------|
|987     | 7   |141    | 987                 |  7      | 141                           |.3447      |226.56       | .6086     | 6.48     | .194                           |.176        |
|1269    | 7   |181    | 987                 |  7      | 141                           |.36212     |252.95       | .91331    | 6.434    | .165                           |.198       |
|705     |   7 |100.71 | 987                 |   7     | 141                           |.39323     |192.98       | .21734    | 6.473    | .235                           | .133      |
|1128    |   7 |161.1  | 987                 |   7     | 141                           |.35401     |240.11       | .76929    | 6.429    |  .236                          | .144      |
|1057.5  |  7  |151.07 | 987                 |   7     | 141                           |.34955     |240          | .69124    | 6.43     | .202                           |  .163      |
|1057.5  | 7   |151.07 | 916.5               |   7     | 130.9                         |.35467     |224.16       | .78088    | 6.43     | .179                             |.186      |           
|1057.5  | 7   |151.07 | 846                 |   7     | 120.8                         |.36018     |216          | .87849    | 6.343    | .17                             | .194      |    
| 987    | 7   |141    | 916.5               |   7     | 130.9                         |.34991     |219.31       | .69745    | 6.425    | .187                             |.177     |      
|916.5   | 7   |130.9  | 846                 |   7     | 120.8                         |.35032     |201.31       | .7047     | 6.426    | .185                             |.179         |     
|775.5   | 7   |110.7  | 916.5               |   7     | 130.9                         |.3508      |185.4        | .71326    | 6.43     | .184                             |.179        |     
|1128    | 7   |161.1  | 1057.5              |   7     | 151.07                        |.34925     |249.75       | .68584    | 6.424    | .187                             |.177         |    
|1057.5  | 7   |151.07 | 1057.5              |   7     | 151.07                        |.34478     |243          | .60864    | 6.424    | .196                             |.168           |   
|1128    | 7   |161.1  | 846                 |   7     | 120.8                         |.364       |219.8        | .95785    | 6.44     | .162                             |.202           |  
|916.5   | 7   |130.9  | 916.5               |   7     | 130.9                         |.356       |191.93       | .81027    | 6.426    | .175                             |.188             |
|916.5   | 7   |130.9  | 1057.5              |   7     | 151.07                        |.334       |226          | .43957    | 6.435    | .211                             |.154             |









## TRANSIENT ANALYSIS

![Screenshot from 2024-10-07 00-31-18](https://github.com/user-attachments/assets/0b782a1b-c7d7-4cf1-9e76-a67e3a6a9bb8)

## DC analysis

![Screenshot from 2024-10-07 01-39-06](https://github.com/user-attachments/assets/dce59d35-70f5-4e0e-977d-0bf9a0835ae2)
