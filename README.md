# NUS-RightShip Hackathon 2024
Team Members:
Gopal Radhakrishnan Ramanen Bharatwa
Yan Wei Dong (Evan)
Zhu Yue Chen
Fong Kai Jun

## Abstract
In this report, we explore the current state of greenhouse gas (GHG) emissions at Singapore ports, placing a special emphasis on the electrification of vessels during their berthing at Pasir Panjang Terminal. Carbon emissions and pollutants are expected to be lower when using electricity (from the grid), compared to those propelled by internal combustion engines (ICE) and fossil-based fuels. They can be reduced to zero if charged using renewables (e.g. solar energy) (MPA, 2023). Our results concluded that the use of electrification significantly reduces greenhouse gasses and will propose various recommendations of sets of best practices on the use of electrification throughout the day, as backed by data.
Methodology and process

For Event duration, we will assume that should there be a change in operational mode, there will be a log on the GIS.
For `speed`, `sfc_me`, `sfc_ae`, `p`, `vref`, `AS`, `ael`, we replace null values with 0.
There is no column named `AS`, so we replaced it with `speed`. For engine types in vessel_movements Relabel HSD and MSD-ED to MSD. We will ignore LNG labels since we do not consider LNG tankers according to Step 3.

## Findings
The findings, represented by numerical data and analytical insights, will be comprehensively presented in this section.

### GHG Emissions Baseline at Pasir Panjang Terminal

<img width="556" alt="Screenshot 2024-01-27 at 7 54 06 PM" src="https://github.com/evanyan13/rightship/assets/103996156/16377948-84a1-4d4a-8836-2b1a3160ff21">

As seen in the visualisations above, the bulk of CO2 emissions are from the anchorage and alongside operation mode. 
Estimated Emission Reductions through Electrification
According to the Energy Market Authority, Singapore’s average Operating Margin (OM) Grid Emission Factor (GEF) was  0.4168 kg CO2/kWh in 2022 (n.d.). Using this as the benchmark, we will be able to determine the CO2 reductions based on the Total electrical demand from a ship in alongside mode. 
Electrical Load Demand Variation Analysis

### Electrification Analysis 

![image](https://github.com/evanyan13/rightship/assets/103996156/e5592a8c-0bd9-4f46-9e63-75decda9d42a)

Our investigated trend indicates a recurrent pattern of electrical load across the two months, with nighttime demand generally showing higher variability and more pronounced peaks than daytime. In both months, there is a tendency for the electrical load to dip mid-month. 


## Conclusion
The report concludes with reflections on the implications of the findings, considering the future of port operations, electrification strategies, and GHG emission reduction efforts. By adopting the various recommendations, we aim to achieve a net zero GHG emissions from shipping.
