---
name: Resource Allocation Under Envy Constraints
tools: [Python, HTML]
image: /assets/pngs/gametheory.jpg
description: Exploring methods to balance agent preferences and minimizing overall cost in task allocation in a game theoretic setting
custom_js:
  # - vega.min
  # - vega-lite.min
  # - vega-embed.min
  # - justcharts
---

# Resource Allocation under Envy Constraints


## Motivation

Efficiently allocating resources to strike a balance between minimizing costs and maximizing overall satisfaction among agents

## Significance
Improving productivity and employee morale while simultaneously reducing costs


## Premise


In a scenario where a manufacturing firm is seeking to efficiently allocate tasks among recruited employees, various factors come into play. Each employee possesses unique skills and efficiency levels, influencing how quickly they can complete assigned tasks. Naturally, the aim is to minimize the overall time required for task completion, a classic optimization challenge where time is the primary cost variable.<br><br>
<div>
![image](/portfolio/assets/pngs/gametug.png)
</div>
However, there's an added layer of complexity: the individual preferences of each employee, whom we'll refer to as 'agents'. We refer to the preference as ‘valuation’ and it is a score that can be obtained by a simple survey among the agents. If an agent isn't assigned their preferred task, it leads to dissatisfaction and a sense of envy within the system. Therefore, the overseer must also consider the subjective valuation that each agent places on their tasks. <br><br>
This dual objective—minimizing time/cost while maximizing agent satisfaction—often creates a balancing act. Sometimes, the optimal allocation for time efficiency conflicts with satisfying agent preferences, necessitating a compromise that serves the best interests of the firm overall.

## Formulation

<div>
![image](/portfolio/assets/pngs/gameformulation.png)
</div>

## Detailed code and analysis

<div class="left">
{% include elements/button.html link="https://utsavmajumdar14.github.io/resource_alloc_envy/" text="Code and Analysis" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/utsavmajumdar14/resource_alloc_envy" text="Repository" %}
</div>

## 