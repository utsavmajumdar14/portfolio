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

## Detailed Report

For an in-depth exploration of the algorithm, including methodologies and theoretical underpinnings, refer to the full report:

<div style="text-align:left;">
<a href="https://github.com/utsavmajumdar14/DynamicLAP/blob/main/Majumdar%20et%20al.%20-%20Accelerating%20Dynamic%20Linear%20Assignment%20Problem%20solver.pdf" class="btn btn-primary" role="button">View Full Report</a>
</div>

## Performance Analysis

Discover the performance comparisons between the primal algorithm and the Hungarian algorithm across various matrix sizes and sparsity levels. Detailed results and analysis can be found at the link below:

<div style="text-align:left;">
<a href="https://utsavmajumdar14.github.io/DynamicLAP/" class="btn btn-primary" role="button">View Performance Results</a>
</div>
