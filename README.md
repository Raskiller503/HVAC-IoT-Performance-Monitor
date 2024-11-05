# Realtime HVAC system performace ckeck kit

This is a IoT based BI-Tech(Behavioral Insight X Technology) platform for check Coefficient of Performance (COP) real-time in VRF system.\ 

<div align=center>
<img src="Image/BI-Tech.gif" width="300" > 
</div>


## Introduction
This platform consists of 3 parts: 
- Offline Training.
- Cloud compution.
- Apllication.

<div align=center>
<img src="Image/flowchart.png" alt="flowchart" width="500" style="display: block; margin: 0 auto;" />
</div>


## Hardware
- Power monitor part
- Indoor outlet part
<div align=center>
<img src="Image/Check_kit.png" alt="flowchart" width="700"/>
</div>

## Algorithm--Coefficient of Performance (COP) Calculation

<div align=center>
<img src="Image/Algorithm.png" alt="flowchart" width="500" style="display: block; margin: 0 auto;" />
</div>

## Comparing experiment result
We conducted comparing experiment and data analyzation via random forest model.
### With commerical power monitor
For ensuring the energy consumption result measruing by proposed IoT kit, we conducted a compare experiment with commerical power monitore (T&D clamp sensor). The result shows the 5% difference for 10 days experiment.

<div align=center>
<img src="Image/Result1.png" alt="flowchart" width="500"/>
</div>

<div style="display: flex; justify-content: space-between align=center;">
    <img src="Image/Electricity_1.png" alt="flowchart1" width="45%">
    <img src="Image/Electricity_2.png" alt="flowchart2" width="45%">
</div>

### With Testo 420 commerical outlet sensor
<div align=center>
<img src="Image/Result2.png" alt="flowchart" width="500"/>
</div>

### Analyzation via Random Forest model
<div align=center>
<img src="Image/RF_importance_partial.png" alt="flowchart" width="700"/>
</div>


## Reference
For more detailed information, please refer to the following paper:
- __Yutong CHEN__,
[An IoT-Based Interactive Diagnostic System for HVAC Performance in Office Buildings](https://publications.ibpsa.org/asim-conference-proceedings/), ASim 2024 (The 5th Asia Conference of International Building
Performance Simulation Association).
