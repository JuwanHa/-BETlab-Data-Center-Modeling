# -BETlab-Data-Center-Modeling

## Data Center Modeling

### 1) Air-Cooled Data Center (ACDC)

#### Overview

We developed a high-fidelity, physics-based EnergyPlus model of an air-cooled data center (ACDC) with a Computer Room Air Handler (CRAH)-based cooling system. Figure 1 presents the conceptual control sequence diagram of the partial cooling model with a Water-Side Economizer (WSE), while Figure 2 illustrates the major system components, including the chiller plant, Water-Side Economizer (WSE), and Thermal Energy Storage (TES). Using this framework, we demonstrated reductions in energy consumption, operating cost, and electrical demand. The resulting research contributions have been published in the five peer-reviewed papers listed in the references below, and the developed ACDC platform includes the following system configurations:

- ACDC - Option A: Chiller Plant
- ACDC - Option B: Chiller Plant + WSE
- ACDC - Option C: Chiller Plant + WSE + TES

![Figure 1. WSE Control Sequence Diagram](docs/images/figure-1-wse-control-sequence.jpg)

*Figure 1. WSE Control Sequence Diagram (Reference [1])*

![Figure 2. Air-cooled Data Center System Schematic Diagram](docs/images/figure-2-air-cooled-system.jpg)

*Figure 2. Air-cooled Data Center System Schematic Diagram (Reference [4])*

#### Reference

**ACDC- Option A: Chiller Plant**

[1] Yujin Kim, Juwan Ha, Kyung-Soon Park, Young-Hak Song, (2021). A Study on the Energy Reduction Measures of Data Centers through Chilled Water Temperature Control and Water-Side Economizer, *Energies*, 14(12), 3575, https://doi.org/10.3390/en14123575

**ACDC- Option B: Chiller Plant + WSE**

[2] Yujin Kim, Kwanghee Kim, Juwan Ha, Young-Hak Song, (2024). Research on a Plan of Free Cooling Operation Control for the Efficiency Improvement of a Water-Side Economizer, (2024). *Energies*, 17(12), 2804, https://doi.org/10.3390/en17122804

[3] Kwanghee Kim, Yujin Kim, Juwan Ha, Young-hak Song, (2025). Development of an integrated loop control algorithm: Enhancing efficiency and expanding application range for water-side economizers, *International Journal of Refrigeration*, Vol. 177, 29-39, https://doi.org/10.1016/j.ijrefrig.2025.05.008

**ACDC- Option C: Chiller Plant + WSE + TES**

[4] Kwanghee Kim, Yujin Kim, Younghak Song, Development of a thermal storage combined water-side economizer system: Enhancing cooling energy reduction in data centers through expanded free cooling performance, *Journal of Energy Storage*, Vol, 149, 120291, https://doi.org/10.1016/j.est.2025.120291

[5] Kwanghee Kim, Yujin Kim, Juwan Ha, Young-hak Song., AI-based Model Predictive Control of Chiller Plant with Thermal Energy Storage combined a Water-side Economizer System in Data Centers, *Energy and Buildings* (Under review)
