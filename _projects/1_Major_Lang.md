---
name: Language Family Distribution and Vulnerabilities
tools: [Python, HTML, vega-lite]
image: assets/pngs/langmap.png
description: This is a distribution to see how language families are distributed and their vulnerabilities to extinction.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Major language family distribution

A visualization that represents how major world language families are distributed. 
The interactive chart provides insight on how vulnerable the languages are within a family.
The networks provide an insight on how simialr the languages are and how they can be subcategorized into communities.
At the bottom of the page, I have provided the data and the code for further analysis.
If the code is forked, it can be used for more dynamic interactivity in Jupyter notebook using widgets.
<br>
<br>

### Indo-European

Map
![Indo-European](/portfolio/assets/pngs/Finals/Indo-European.png)
Interactive Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Indo-European.json" style="width: 100%"></vegachart>
Similarity Network on 20 random languages
![Indo-European](/portfolio/assets/pngs/Finals/Networks/Indo-European_main_network.png)
![Indo-European](/portfolio/assets/pngs/Finals/Networks/Indo-European_community_detection.png)

<br>

### Afro-Asiatic

Map
![Afro-Asiatic](/portfolio/assets/pngs/Finals/Afro-Asiatic.png)
Interactive Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Afro-Asiatic.json" style="width: 100%"></vegachart>
Similarity Network on 20 random languages
![Afro-Asiatic](/portfolio/assets/pngs/Finals/Networks/Afro-Asiatic_main_network.png)
![Afro-Asiatic](/portfolio/assets/pngs/Finals/Networks/Afro-Asiatic_community_detection.png)

<br>

### Atlantic-Congo

Map
![Atlantic-Congo](/portfolio/assets/pngs/Finals/Atlantic-Congo.png)
Interactive Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Atlantic-Congo.json" style="width: 100%"></vegachart>
Similarity Network on 20 random languages
![Atlantic-Congo](/portfolio/assets/pngs/Finals/Networks/Atlantic-Congo_main_network.png)
![Atlantic-Congo](/portfolio/assets/pngs/Finals/Networks/Atlantic-Congo_community_detection.png)

<br>

### Austronesian

Map
![Austronesian](/portfolio/assets/pngs/Finals/Austronesian.png)
Interactive Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Austronesian.json" style="width: 100%"></vegachart>
Similarity Network on 20 random languages
![Austronesian](/portfolio/assets/pngs/Finals/Networks/Austronesian_main_network.png)
![Austronesian](/portfolio/assets/pngs/Finals/Networks/Austronesian_community_detection.png)

<br>

### Sino-Tibetan

Map
![Sino-Tibetan](/portfolio/assets/pngs/Finals/Sino-Tibetan.png)
Interactive Chart
<vegachart schema-url="{{ site.baseurl }}/assets/json/Finals/Sino-Tibetan.json" style="width: 100%"></vegachart>
Similarity Network on 20 random languages
![Sino-Tibetan](/portfolio/assets/pngs/Finals/Networks/Sino-Tibetan_main_network.png)
![Sino-Tibetan](/portfolio/assets/pngs/Finals/Networks/Sino-Tibetan_community_detection.png)

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/utsavmajumdar14/Language_Viz/tree/main/Data" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/utsavmajumdar14/Language_Viz/tree/main/Code" text="The Analysis" %}
</div>
