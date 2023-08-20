# ClimateTrafficSumoRL
Climate Change RL project with Sumo Simulation

sumo emission
● official introduction:https://sumo.dlr.de/docs/Models/Emissions.html#introduction
● model: Second Generation of Pollutant Emission Models for SUMO
● related proj:
○ https://github.com/Simoniuss/Braess-Paradox-Framework
○https://github.com/Ahp06/SUMO_Emissions
○https://www.youtube.com/watch?v=cdUP88FEcPU
○Environmental Impact of Bundling Transport Deliveries Using SUMO
● Demo:
https://www.nsnam.com/2023/04/sumo-emission-of-vehicles-vanets.html

Carbon Monoxide (CO)
Carbon Dioxide (CO2)
Hydro Carbons (HC)
Particle Matter (PMx)
Nitrous Oxide (NOx)

Step 1: Creation of a node file that contains the information about the junctions
Extension of the file would be .nod.xml
Step 2: Creation of edges (roads connecting the junction).
Extn: .edg.xml
Step 3: Create a net.xml file using the node and edge files.
Step 4: Creation of random trips
Step 5: Create a file called file.sumo.cfg (to run with sumo for air pollution)
sumo-gui file.sumo.cfg


Results: emission.csv

Using these data, we can predict or analyze various results of the emission of gases to counter air pollution. These kinds of systems can be demonstrated as Automotive cyber-physical systems 

