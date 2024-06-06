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

At its core, the optimization of resource allocation hinges upon the intricate task of assigning responsibilities among agents in a manner that minimizes costs while concurrently maximizing productivity and satisfaction. However, this endeavor is markedly complex, given the diverse preferences and valuations inherent to individual agents. 
Neglecting the preferences of agents in real-world scenarios can precipitate adverse outcomes. Task assignment devoid of consideration for individual preferences may engender diminished motivation, reduced productivity, and a pervasive sense of dissatisfaction among workforces. Hence, our research is propelled by the compelling need to explore methodologies that seamlessly integrate agents' individual preferences into the resource allocation process alongside traditional cost-based optimization techniques. 
Our pursuit is motivated by the recognition that while cost minimization is indisputably vital for organizational efficiency, it must not eclipse the significance of upholding high levels of agent morale and performance. This is pivotal for ensuring the sustained productivity of a firm, as employee morale exerts a profound butterfly effect on organizational performance. An organization fixated solely on cost optimization risks entering an unsustainable cycle where diminishing employee performance precipitates increased turnover rates, leading to escalated expenditure and man-hours in recruitment endeavors. Furthermore, there is a consequential decline in overall performance, compounded by the need for additional investment in training new recruits or enduring a period of suboptimal performance until proficiency is attained. This underscores the importance of prioritizing employee satisfaction, considering the long-term cost implications associated with low morale. 
Consequently, our endeavor embarks on a quest to unravel the intricate relationship between cost optimization and agent satisfaction. Through meticulous analysis and simulation, our study aims to shed light on the delicate equilibrium between minimizing costs and maximizing agent contentment. By elucidating this multifaceted interplay, we aspire to furnish decision-makers with invaluable insights and actionable recommendations for refining resource allocation strategies across diverse operational landscapes. Ultimately, our research endeavors to empower decision-makers with the requisite tools to navigate the inherent trade-offs in resource allocation, thereby fostering more efficient and sustainable organizational practices.

## Premise

In a scenario where a manufacturing firm is seeking to efficiently allocate tasks among recruited employees, various factors come into play. Each employee possesses unique skills and efficiency levels, influencing how quickly they can complete assigned tasks. Naturally, the aim is to minimize the overall time required for task completion, a classic optimization challenge where time is the primary cost variable.
However, there's an added layer of complexity: the individual preferences of each employee, whom we'll refer to as 'agents'. We refer to the preference as ‘valuation’ and it is a score that can be obtained by a simple survey among the agents. If an agent isn't assigned their preferred task, it leads to dissatisfaction and a sense of envy within the system. Therefore, the overseer must also consider the subjective valuation that each agent places on their tasks.
This dual objective—minimizing time/cost while maximizing agent satisfaction—often creates a balancing act. Sometimes, the optimal allocation for time efficiency conflicts with satisfying agent preferences, necessitating a compromise that serves the best interests of the firm overall.

## Detailed code and analysis

<div class="left">
{% include elements/button.html link="https://utsavmajumdar14.github.io/resource_alloc_envy/" text="Code and Analysis" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/utsavmajumdar14/resource_alloc_envy" text="Repository" %}
</div>
