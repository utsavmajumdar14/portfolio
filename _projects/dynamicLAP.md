---
name: Dynamic Linear Assignment Problem
tools: [C++, Python, Gurobi, HTML]
image: /assets/pngs/dynLAP/dynamicLAP.png
description: Accelerating Dynamic Linear Assignment Problem solver using Primal Algorithms
custom_js:
  # - vega.min
  # - vega-lite.min
  # - vega-embed.min
  # - justcharts
---

# Accelerating Dynamic Linear Assignment Problem solver using Primal Algorithms
The classical Linear Assignment Problem can be solved using established algorithms like Hungarian algorithm quite efficiently within linear time complexity. However, there are other classes of problems like resource capacitated assignment problems that uses Lagrangian relaxation schemes with branch and bound that require LAPs to be solved iteratively multiple times with minor variations on cthe cost matrix. The established methods for solving LAPs require them to re-solve each of the modified cost matrix from scratch.
I built an algorithm that can outperform the established algorithms by leveraging the results of a previous iteration’s result to achieve results quicker.

## Report
<div class="left">
{% include elements/button.html link="https://github.com/utsavmajumdar14/DynamicLAP/blob/main/Majumdar%20et%20al.%20-%20Accelerating%20Dynamic%20Linear%20Assignment%20Problem%20solver.pdf" text="Click here" %}
</div>

## Overview plots
<div class="left">
{% include elements/button.html link="assets/plots/all/balinski_vs_hungarian.html" text="Overview" %}
</div>
<div class="right">
{% include elements/button.html link="/assets/plots/all/balinski_vs_hungarian_simplify.html" text="Simplified" %}
</div>

## Further granularity for different sparsity fractions of cost matrix
<div class="left">
{% include elements/button.html link="/assets/plots/all/1_frac_0.01.html" text="Frac = 0.01" %}
{% include elements/button.html link="/assets/plots/all/2_frac_0.05.html" text="Frac = 0.05" %}
{% include elements/button.html link="/assets/plots/all/3_frac_0.1.html" text="Frac = 0.1" %}
{% include elements/button.html link="/assets/plots/all/4_frac_0.5.html" text="Frac = 0.5" %}
{% include elements/button.html link="/assets/plots/all/5_frac_1.html" text="Frac = 1" %}
{% include elements/button.html link="/assets/plots/all/6_frac_5.html" text="Frac = 5" %}
{% include elements/button.html link="/assets/plots/all/7_frac_10.html" text="Frac = 10" %}
</div>

## Deeper dive into the transition region
This is the area where we notice the size and sparsity for which the performance of the new primal algorithms starts to out-perform the traditional Hungarian algorithm.
<div class="left">
{% include elements/button.html link="/assets/plots/all/balinski_vs_hungarian_transition.html" text="Transition" %}
</div>

## More granularity in the transition region
<div class="left">
{% include elements/button.html link="assets/plots/transition/transition_frac_0.1.html" text="Frac = 0.1" %}
{% include elements/button.html link="assets/plots/transition/transition_frac_0.2.html" text="Frac = 0.2" %}
{% include elements/button.html link="assets/plots/transition/transition_frac_0.3.html" text="Frac = 0.3" %}
{% include elements/button.html link="assets/plots/transition/transition_frac_0.4.html" text="Frac = 0.4" %}
</div>

