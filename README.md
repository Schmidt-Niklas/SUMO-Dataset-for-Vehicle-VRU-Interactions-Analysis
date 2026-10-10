# SUMO-Dataset-for-Vehicle-VRU-Interaction-Analysis
This project extends the SUMO Dataset "InTas" with synthetically generated pedestrians to support the fast evaluation of interactions between Vehicles and Pedestrians in new C-ITS Approaches.

Source: S. LOBO, S. NEUMEIER, E. FERNANDEZ, C. FACCHI, "InTAS - The Ingolstadt Traffic Scenario for SUMO". SUMO User Conference Proceedings, 2020, ISSN 2750-4425, DOI 10.52825
https://github.com/silaslobo/InTAS

**The paper reference of this study just published:**
Schmidt, N., Roque, A. S., Bied, M., de Freitas, E. P., Vinel, A. "Generating Synthetic Pedestrian Mobility for Vehicle-Pedestrian Interaction Analysis in SUMO," 2026 IEEE 29th International Conference on Intelligent Transportation Systems (ITSC), Napoli, Italy, 2026, doi: soon.


This repository provides an extended SUMO scenario for the simulation and analysis of interactions between vehicles and vulnerable road users (VRUs). The scenario is based on the open-source InTAS dataset and has been adapted to include synthetic pedestrian mobility, pedestrian crossing infrastructure, and a spatially restricted evaluation area around one urban intersection.

The dataset was developed as the simulation foundation for evaluating infrastructure-based traffic-control and reinforcement-learning approaches in mixed urban traffic.

- Dataset Extensions
The original InTAS scenario was extended through the following steps:

- Pedestrian infrastructure:
Walking areas, pedestrian crossings, and shared spaces were added to the road network.

- Synthetic pedestrian demand:
Additional pedestrian trips were generated to increase the number and diversity of vehicle–pedestrian interactions.

- Spatial filtering:
Vehicle, bus, and pedestrian routes were filtered to the selected urban intersection and its surrounding area.

- Temporal processing:
The generated pedestrian routes were retimed and sorted to ensure consistent insertion into the SUMO simulation.

- Multimodal scenario configuration:
The final SUMO configuration combines passenger vehicles, buses, bus stops, and pedestrians in one executable scenario.
