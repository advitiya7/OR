The United Nations World Food Program (WFP) supplies food assistance to around 100 million people in 80 countries each year.
Transporting food in a global transportation network is a challenging undertaking.
In this notebook, we will build an optimization model to set up a food supply chain based on real data from WFP.
The optimization model is motivated by the case studies in Syria by [Peters et al. (2021)](https://pubsonline.informs.org/doi/epdf/10.1287/ijoo.2019.0047), [Peters et al. (2022)](https://pubsonline.informs.org/doi/abs/10.1287/inte.2021.1097) and the [Zero Hunger Lab](https://www.tilburguniversity.edu/research/institutes-and-research-groups/zero-hunger-lab).

The idea is to transport food from cities identified as "suppliers" to beneficiary cities in Syria.
The quantity of food arriving at beneficiary cities must be sufficient enough to satisfy basic nutritional needs of the people there.
On the other hand, the procurement and transportation of food comes at a cost, and therefore must be done efficiently.
In this notebook, we will learn how to set up an optimization problem to achieve a cost-efficient food supply chain.

<!-- ![alt text](image/figure_syria.png) -->

<!-- |<img src="image/figure_syria.png" width="1000" align="center">|
|:--:|
| <b>Image Credits: [Peters et al. (2016). The Nutritious Supply Chain: Optimizing Humanitarian Food Aid. NFORMS Journal on Optimization.](https://pubsonline.informs.org/doi/10.1287/ijoo.2019.0047) </b>|  -->
