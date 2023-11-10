# ClimateTrafficSumoRL
Climate Change RL project with Sumo Simulation

## sumo emission
- official introduction:https://sumo.dlr.de/docs/Models/Emissions.html#introduction
- model: Second Generation of Pollutant Emission Models for SUMO (https://elib.dlr.de/89398/1/2ndGenEmissions.pdf)
- related proj:
  1) https://github.com/Simoniuss/Braess-Paradox-Framework
  2) https://github.com/Ahp06/SUMO_Emissions
  3) https://www.youtube.com/watch?v=cdUP88FEcPU
  4) Environmental Impact of Bundling Transport Deliveries Using SUMO
### Demo:
https://www.nsnam.com/2023/04/sumo-emission-of-vehicles-vanets.html

	Carbon Monoxide (CO)
	Carbon Dioxide (CO2)
	Hydro Carbons (HC)
	Particle Matter (PMx)
	Nitrous Oxide (NOx)

- Step 1: Creation of a node file that contains the information about the junctions
Extension of the file would be .nod.xml
- Step 2: Creation of edges (roads connecting the junction).
Extn: .edg.xml
- Step 3: Create a net.xml file using the node and edge files.
- Step 4: Creation of random trips
- Step 5: Create a file called file.sumo.cfg (to run with sumo for air pollution)
sumo-gui file.sumo.cfg

- Results: emission.csv

Using these data, we can predict or analyze various results of the emission of gases to counter air pollution. These kinds of systems can be demonstrated as Automotive cyber-physical systems 


## Background papers about climate change
Climate change AI papers:

### Part1: most relelated
- https://www.climatechange.ai/papers/neurips2022/54
Measuring and attributing greenhouse gas (GHG) emissions remains a challenging problem as the world strives towards meeting emissions reductions targets. As a significant portion of total global emissions, the road transportation sector represents an enormous challenge for estimating and tracking emissions at a global scale.
- https://www.climatechange.ai/papers/neurips2022/90
Transportation plays a major role in global CO2 emission levels, a factor that directly connects with climate change. Roadway interventions that reduce CO2 emission levels have thus become a timely requirement.
- https://www.climatechange.ai/papers/neurips2021/50
Greenhouse gases (GHGs), particularly carbon dioxide, are a key contributor to climate change. The transportation sector makes up 35% of CO2 emissions in the US and more than 70% of it is due to land transport.
These findings are a stepping-stone for near-term deployment of vehicle-based congestion mitigation.

### Part2: may be useful
- https://www.climatechange.ai/papers/neurips2020/28
We present a simple and versatile framework for estimating the quantity of four air pollutants (CO2, NOx, PM, VOC) emitted by private vehicles moving on a road network, starting from raw GPS traces and information about vehicles' fuel type, and use this framework for analyses on how such pollutants distribute over the road networks of different cities.

- https://www.climatechange.ai/papers/icml2019/40

### Part3: interesting
- https://www.climatechange.ai/papers/iclr2023/15
- https://www.climatechange.ai/papers/iclr2023/34
- https://www.climatechange.ai/papers/neurips2022/100
- https://www.climatechange.ai/papers/icml2021/55
- https://www.climatechange.ai/papers/icml2021/64
- https://www.climatechange.ai/papers/neurips2020/1
- https://www.climatechange.ai/papers/neurips2019/33
