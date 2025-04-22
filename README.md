# TrafficLightCycle_Sustainability

This repository was developed by [Adamo Cerioli](www.linkedin.com/in/adamo-cerioli-739881348) for academic purposes.  
Feel free to reach out for questions or collaborations!

This repository contains open-access code for exploring the effects of traffic light signal timing on urban mobility and modal choices. The model simulates a city as a circular grid of intersections, where each node represents a potential crossing regulated by traffic lights. Commuters choose between private cars and alternative transport modes (e.g., walking, cycling, public transit) and iteratively update their choices to minimize commuting time. This process continues until a stable equilibrium is reached, where no commuter can further reduce their travel time — a setting inspired by Nash equilibrium from game theory.

The simulation allows users to adjust key parameters such as the share of green light allocated to cars versus alternative transport modes and the overall cycle duration of traffic lights. By doing so, it becomes possible to evaluate how these changes impact both commuting times and modal share across the city.

In particular, the model highlights a counterintuitive result — the traffic light paradox — where, under certain conditions, increasing green light time for cars leads to more congestion and longer travel times. This effect reflects the Price of Anarchy, in which individual decisions driven by self-interest can produce suboptimal outcomes at the system level.

The code is designed for accessibility and extensibility, requiring minimal data to reproduce complex urban dynamics. It can serve as a base for further studies, integration with spatial datasets, or development into digital twins for mobility planning. By appropriately choosing transport parameters (e.g., free-flow speeds, congestion sensitivities), adjusting the number of commuters, and customizing the size and shape of the urban area, the model can be specialized to represent specific cities. This includes the potential to import real-world road networks and intersection layouts from platforms such as OpenStreetMap, allowing for realistic simulations of how traffic light timing influences commuting behavior in diverse urban contexts.

All simulations are freely available for academic and research purposes.
