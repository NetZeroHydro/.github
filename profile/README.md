# Hydropower's low-hanging fruits: Leveraging least impact dams to power a net-zero future
<img width="1800" height="1200" alt="NZH_image" src="https://github.com/user-attachments/assets/c74c120c-e54b-416c-9f8b-b6e1ff9cd132" />

## Background
Renewable energy is crucial to combat climate change. One scalable and efficient renewable energy source is hydropower, which converts energy from natural watershed systems into usable electricity (citation). Hydropower supports global climate action by providing low-carbon electricity generation that can be dispatched flexibly compared to wind and solar energy (USGS, n.d.). Projections about future needs for hydropower vary widely, ranging from +400 gigawatts (GW) to +6000 GW installed hydropower by 2050 (Schmitt et al., 2023). However, hydroelectric power comes with tradeoffs. Dams, constructed to meet various water demands, alter free flowing river continuity, disrupting downstream flow and negatively impacting natural ecosystem services (He et al., 2024). Free flowing rivers provide nutritional value and support economic activity for human development globally (Rivaes et al., 2022). It is now estimated, however, that 63% of the longest rivers are now fragmented (Grill et al., 2019), with impacts on biodiversity, biogeochemical cycles, and livelihoods. In collaboration with the World Wildlife Fund’s Global Science Team, we will utilize geospatial and river network analyses to determine which future dam sites could exert least additional pressure on the  world’s rivers, presenting an opportunity to reconcile goals for a net zero future with the imperative to  conserve biodiversity in the world’s rivers. 

## Specific objectives
The overall objective of this project is to analyse sustainability constraints for expanding future hydropower. Our team aims to achieve this goal by completing the following objectives:
Build an analytical model to assess sustainability constraints for expanding future hydropower
Utilize geospatial and river network to determine least impact dams “Low-hanging fruits”
Present an opportunity to reconcile goals for a net zero future with the imperative to conserve biodiversity in the world’s rivers.

## Deliverables
This project will deliver three main deliverables.
- A scripted workflow to identify the topologic location of future dams in relation to existing dams.
- An updated dataset of future dams and associated sustainability index based on the scripted workflow.
- An Interactive web viewer (ShinyAPP) that enables users to visualize results of deliverable 2. It will also allow additional filtering and analyses, e.g., analyzing how many dams in a country or within a range of installed capacity fall into a sustainability category.

## Organization Structure
The repositories in this organizations include: 
-  **connectivity:** Code and functions for dam network geospatial analysis, including analyzing future hydropower projects in relation to current dam locations and calculating connectivity.
-  **fatal-flaws:** Code for preparing ecological data to assess environmental impact in conjunction with connectivity outputs.
-  **MCDA-model:** Code and function for evaluating future dams via multi-criteria decision analysis.
-  **shiny-app:** Code to visualize future hydropower impact on an interactive shiny dashboard.

## Data Sources
[Global Dam Watch](https://www.globaldamwatch.org/database)

[Future Hydropower Reservoirs and Dams](https://www.globaldamwatch.org/fhred)

[Free Flowing Rivers](https://www.nature.com/articles/s41586-019-1111-9)

[HydroRIVERS](https://www.hydrosheds.org/products/hydrorivers)

[HydroBASINS](https://www.hydrosheds.org/products/hydrobasins)

[Protected Planet](https://www.protectedplanet.net/en)

## Team Members
Megan Hessel | [Website](https://meganhessel.github.io/) | [LinkedIn](https://www.linkedin.com/in/meganhessel) | [GitHub](https://github.com/meganhessel)

Lucian Scher | [Website](lucianbluescher.com) | [LinkedIn]() | [GitHub]()

Aakriti Poudel | [Website](https://aakriti-poudel-chhetri.github.io/) | [LinkedIn]() | [GitHub]()

Leela Dixit | [Website](https://lsdixit.github.io/) | [LinkedIn]() | [GitHub]()

## Advisor and Client
Dr. Rafael Schmitt, Assistant Professor UCSB Department of Environmental Studies 

Dr. Jeff Opperman, Global Freshwater Lead Scientist, World Wildlife Fund Global Science Team

---

*This is a capstone project for the [Master of Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu), University of California, Santa Barbara”*

*For more information, see the [MEDS Capstone Project Website](https://bren.ucsb.edu/projects/hydropowers-low-hanging-fruits-leveraging-least-impact-dams-power-net-zero-future)*
