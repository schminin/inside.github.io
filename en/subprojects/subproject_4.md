---
layout: default
markdown: 1
title: Subproject 4
lang: en
lang-ref: subproj-4
---

### Subproject 4: Coarse-mesh Sewer Network Models

![title_image]({{ site.url }}{{ site.baseurl }}/assets/img/Abwasserkanal.jpg)

In SP4, we are developing approaches for the construction of computational models for metropolitan sewer networks for infectious disease surveillance.\\
Many pathogens are detectable in wastewater, and thus the testing of wastewater samples for epidemiological tracking of pathogens (such as SARS-CoV-2 has proven to be a useful tool. A major advantage of wastewater testing is that it is independent of testing and reporting strategies and can provide a picture of the incidence of infection across the population.\\

For this, however, the quantities of virus particles that originally entered the wastewater must be determined from the measured virus particle load in the wastewater in order to be able to draw conclusions about the infection process. To do this, we need to know how the pathogens or their particles are transported and chemically degraded in the sewage system. The accuracy of the tracing depends on the level of detail of the underlying sewer network model and the knowledge about the sampling conditions.\\
In SP3, we develop detailed sewer network models based on a well-described city district. However, detailed sewer network models are not feasible for all cities. Coarsening is necessary because, on the one hand, constructing detailed models for entire cities is currently too time-consuming and expensive. On the other hand, the detailed information required for detailed modelling may not be available. For example, detailed data on the wastewater system is not available for many cities, especially in countries of the global south.\\
The declared goal of SP4 is to make the integration of sewer network data for large cities possible within the INSIDe plattform. The sewer network of arbitrarily large cities can then be represented either by a single coarse model, or by splitting it into sub-areas, so that the sub-models generated with the determined optimal coarsening can be used computationally well for the INSIDe approach. For this purpose, we develop algorithms and procedures that allow the automated generation of coarse grid models based on information on fine grid models. In addition, we use the data collected in SP5 on flow patterns in the sewer networks of Munich and Adis Abeba to build our models.\\
The coarse mesh models are tested using the detailed models from SP3.\\
Both detailed and coarse-mesh sewer network models will be linked to the INSIDe platform (SP1) to connect the transmission models (SP2) with wastewater observations.\\
\\
**Contact:** Dr. Andreas Hofmann, andreas.hofmann@tandler.com