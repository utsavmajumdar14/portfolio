---
name: Route Optimization for Charge constrained EV
tools: [Python, HTML]
image: /assets/pngs/californiaroad.jpg
description: Algorithm to find the shortest route for a charge constrained EV implemented on California road network with Tesla Superchargers
custom_js:
  # - vega.min
  # - vega-lite.min
  # - vega-embed.min
  # - justcharts
---
# **Route Optimization for Charge-Constrained EV**
### **Overview**

This project tackles the critical issue of route optimization for electric vehicles (EVs) constrained by limited battery capacity. The algorithm is implemented on the California road network, incorporating Tesla Superchargers to ensure efficient and seamless travel.

#### **GitHub Repository:**
[Charge-Constrained Route Optimization](https://github.com/utsavmajumdar14/charge_constrained_route_optimization)

---

### **Motivation**

Electric vehicles (EVs) face unique challenges due to limited battery ranges compared to traditional combustion vehicles. When planning a road trip, especially over long distances, strategic routing through EV charging stations becomes essential to avoid being stranded. This project focuses on finding the shortest path for a charge-constrained EV, ensuring optimal stops at charging stations along the route.

---

### **Project Description**

This project solves the problem of determining the most efficient route for an EV, factoring in charging constraints. By implementing a shortest-path algorithm with charge constraints, we optimize the route for reaching the destination while halting at charging points in the most efficient way possible.

- **Assumptions:**
  - Distances are measured using L2 distance (Euclidean), approximating 1 unit to be equivalent to around 60 miles.
  - Tesla vehicle range, charging speed, and capacity are assumed for the purposes of focusing on the algorithm.

---

### **Project Structure**

- **Toy Network:** A hypothetical network used to test the algorithm.
- **Final Implementation:** The algorithm is executed on the California road network.
- **New Data:**
  1. Tesla Supercharger data (sourced from [Kaggle](https://www.kaggle.com/datasets/omarsobhy14/supercharge-locations))
  2. Road network data (sourced from [Spatial Dataset](https://users.cs.utah.edu/~lifeifei/SpatialDataset.htm))

---

### **🛠️ Tech Stack**

- **NumPy & Pandas:** Data manipulation and processing
- **Matplotlib & Seaborn:** Data visualization
- **Folium:** Interactive map visualizations
- **GeoPandas:** Geospatial data handling
- **NetworkX:** Graph operations
- **ipywidgets:** Interactive UI components

---

### **📸 Screenshots**

#### **Geopandas Visualization**
![Route Visualization with Geopandas](/portfolio/assets/pngs/EV/imgs/geopanda_viz.png)

#### **Folium Visualization**
![Folium Route Visualization](/portfolio/assets/pngs/EV/imgs/folium_viz.png)
*Optimal route with charging stations*

#### **California Road Network**
![Interactive UI - California Network](/portfolio/assets/pngs/EV/gif/california_interactive.gif)

#### **Toy Network**
![Interactive UI - Toy Network](/portfolio/assets/pngs/EV/gif/toy_interactive.gif)
*User-friendly interface for route planning*

---

### **Detailed Code and Analysis**

For a detailed analysis and code execution on a section of the California map, visit my [GitHub Repository](https://github.com/utsavmajumdar14/charge_constrained_route_optimization).

<div class="left">
{% include elements/button.html link="https://nbviewer.org/github/utsavmajumdar14/charge_constrained_route_optimization/blob/main/toy/EV_Charge.ipynb" text="Toy Problem" %}
</div>

<div class="right">
{% include elements/button.html link="https://nbviewer.org/github/utsavmajumdar14/charge_constrained_route_optimization/blob/main/final/EV_Charge.ipynb" text="California Study" %}
</div>
