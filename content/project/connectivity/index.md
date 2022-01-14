---
title: Network topology and connectivity
summary: PhD research exploring the role of network topology and connectivity in shaping extinction risk and patterns of richness.
date: "2020-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

For my PhD I used metapopulation/community models to examine how network topology and connectivity can affect extinction risk and patterns of species richness.

{{< figure src="connect_fig_1.png" caption="River networks generated via different algorithms" numbered="false" >}}

First we examined differences among network generating algorithms and the metrics frequently used to quantify topology. 

Currently, two main algorithms are used, stochastic branching networks (SBNs) and optimal channel networks (OCNs). The topology of these simulated networks and “real” rivers is often quantified using graph theoretic metrics. We aim to provide guidance as to which algorithm and metrics should be used, and under what circumstances.

We performed an extensive simulation study in which we i) identified orthogonal sets of metrics that describe the network topology of real and simulated networks, ii) analysed the relationship between algorithm hyper-parameters and node topology metrics, iii) determined if simulated rivers are able to replicate graph metric scores of real rivers, and iv) examined how patterns of species abundances compare across the three network types.

Both SBNs and OCNs can replicate the node topology of real rivers. The choice of which algorithm to use will depend on the research aims, SBNs are faster to generate and more tractable, whereas OCNs can reproduce a wider variety of the characteristics of real rivers, but are more time-consuming to generate. When quantifying node topology in river networks we recommend the orthogonal node metrics eccentricity, when interested in network centrality, and mean neighbour degree, when interested in local node importance. 

Article: **River networks: an analysis of simulating algorithms and graph metrics used to quantify** *In review* 


{{< figure src="connect_fig_2.png" caption="Trait response to disturbance. C = Competition, R = Reproduction, D = Dispersal" numbered="false" >}}

In the second part of my PhD we presented a mechanistic model of a freshwater fish metacommunity and used the model to understand how environmental variability can interact with disturbance to shape patterns of species richness. Understanding how species coexist remains a long-running challenge in ecology. Coexistence, and hence patterns of richness and diversity, result from a combination of selection, drift, speciation, and dispersal, the relative importance of each being context and scale-dependent. Here, we have outlined a simple, but flexible model that focuses on variability in species traits and that explicitly considers network structure when representing freshwater fish metacommunity dynamics. Our findings suggest that when looking to understand how species may respond to disturbance regimes in the future, an understanding of environmental spatial structure (ESS) is also needed as ESS can mediate the effects of disturbance.

Article: **Environmental spatial structure mediates metacommunity response to disturbance in dendritic ecological networks** *In prep* 


{{< figure src="connect_fig_3.png" caption="Spatiotemporal aspects of connectivity in rivers" numbered="false" >}}

We then used the model above to examine how spatiotemporal aspects of connectivity affect patterns of species richness.

In riverine ecosystems, factors that vary through space and time, such as flow variability, the presence of barriers to movement, and network topology determine connectivity, and in turn shape patterns of richness. While the effects of network topology and changes in spatiotemporal connectivity regimes on patterns of species richness have been studied in isolation, they have not been studied simultaneously. 

We used a discrete-time logistic growth metacommunity model to analyse the role of spatial and temporal functional connectivity in determining patterns of local (patch-level) species richness in freshwater fish metacommunities.

Our modelling suggests that: i) the effect of spatial loss of connectivity on local species richness is mediated by network topology and where in the system richness is measured; and ii) increasing temporal autocorrelation in connectivity results in increasing temporal autocorrelation in patch occupancy.

Spatial and temporal loss of connectivity is a ubiquitous issue for river ecosystems globally, making understanding and predicting its effects of fundamental importance to both improving theory and guiding river management. Our findings highlight the importance of network topology (and hence context dependency) in shaping metacommunity response to changing connectivity regimes. 

Article: **Network topology mediates freshwater fish metacommunity response to loss of connectivity** *In review* 


{{< figure src="connect_fig_4.png" caption="An upokororo, image source: Te Papa: 1992-0035-2278/1" numbered="false" >}}

Finally, we examined how intercatchment connectivity, facilitated by amphidromy of the upokororo may have contributed to the species extinction. Some extinctions have obvious drivers (e.g. over harvesting), while others can be less obvious and arise from multiple interacting factors. The extinction of the New Zealand grayling (*Prototroctes oxyrhynchus*) has been blamed on over‐fishing and predation by introduced trout, but these explanations fail to account for the species disappearance from isolated, uninvaded rivers. We investigated if source–sink dynamics, facilitated by *P. oxyrhynchus*'s amphidromous dispersal habit, could account
for the species’ rapid extinction.

We created a database of *P. oxyrhynchus* sightings by surveying newspapers dating back to 1839, along with a review of traditional scientific literature. We used this database to update *P. oxyrhynchus*'s known distribution map and inform sighting models to predict *P. oxyrhynchus*'s extinction date. Finally, we implemented a meta‐population model to explore how source–sink dynamics could interact with off‐take (over‐fishing or predation) to drive extinction.
*Prototroctes oxyrhynchus* was found across New Zealand, except the north of the North Island. Based on sightings methods, the earliest predicted extinction date was 1924, although the species may have persisted until 1972, later than previous estimates have suggested. In the absence of source-sink dynamics, relatively high levels of off‐take were sustainable (up to 30% per generation). When the species was modelled as a panmictic meta‐population including 5% sink habitats, the sustainable off‐take rate was reduced to as low as 5% per generation.

*Prototroctes oxyrhynchus* was a widespread, abundant species that underwent rapid declines and ultimately went extinct. Previous attempts to explain this extinction have failed to account for the species extinction from isolated, pristine rivers. Our modelling shows that treating the species as a panmictic metapopulation and including source–sink dynamics rapidly increases the probability of extinction. We suggest that source–sink dynamics may be an important aspect of the population dynamics of amphidromous species and should be considered when managing taxa with similar dispersal habits.

Article: **Assessing the role of off-take and source-sink dynamics in the extinction of the amphidromous upokororo (*Prototroctes oxyrhynchus*)**  [Freshwater Biology](https://onlinelibrary.wiley.com/doi/abs/10.1111/fwb.13366)
