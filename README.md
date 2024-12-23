This project focuses on simulating chillers at the Moy Park food factory at two sites, Anwick and Dungannon, to compare and predict chiller consumption for optimization using a multi-agent system, aiming to reduce CO2 emissions. The capacity of the chillers is up to 40,000 chicken carcasses, and they spend two and a half hours in the chillers. We simulated this in Butterfly8.nlogo and applied the heat transfer equation to predict the temperature of each carcass.

![Screenshot](https://github.com/user-attachments/assets/3a2a4945-d6f2-4297-9e65-270801d83e94)
<p align="center" >
Figure1. Simulation of chiller at the Moy Park

We plotted the data gathered from iButton sensors in MATLAB and then attempted to fit the figure obtained from the simulation in NetLogo.

<p align="center" >
<img src="https://github.com/hgolshanian/Netlogo/blob/main/Photos/Capture4.PNG" width=450 height=300>
<p align="center" >
Figure2. Heat transfer model after tuning


We then calculated the time constant using the parameters obtained from the previous step to compare chiller consumption at different sites.
<p align="center" >
<img src="https://github.com/hgolshanian/Netlogo/blob/main/Photos/Capture5.PNG" width=30 height=300>
<p align="center" >
Figure3. Calculating time constant
