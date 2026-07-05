---
title: "Optimal vaccination in aging populations under age-dependent infection fatality risks."
collection: publications
category: preprints
permalink: /publication/2026-06-26-optimal-vaccination
excerpt: 'We use PDE models implemented in Julia to assess age-dependent vaccination strategies in aging populations.'
date: 2026-06-26    
venue: 'MedRxiv'
paperurl: 'https://doi.org/10.64898/2026.06.24.26356423'
citation: 'van Boven, M. et al. (2026). &quot;Optimal vaccination in aging populations under age-dependent infection fatality risks.&quot; <i>MedRxiv</i>.'
---

The premise of this study is that in counties like the Netherlands, the life expectancy keeps increasing, and old age is associated with increased frailty to e.g. common seasonal respiratory pathogens. Moreover, as immunity due to natural infection and vaccination wanes over time, the choice of at what age people are vaccinated could lead to complex interactions between age-dependent infection-induced mortality, loss of immunity, and age distributions. Therefore, we developed an age-structured partial differential equation model (with calendar time and age as independent variables) based on Dutch demographic data and contact patterns to game out multiple vaccination scenarios. We found that the optimal age for vaccination depends on pathogen properties such as transmissibility and the duration of immunity. In some situations, vaccination can even increase mortality by shifting infections to older ages where fatality risks are highest. The model is implemented in the Julia programming language and is easily modified to different situations.