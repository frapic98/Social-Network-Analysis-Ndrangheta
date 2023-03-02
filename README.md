# Social-Network-Analysis-Ndrangheta
The project is based on ["Disrupting Resilient Criminal Networks through Data Analysis: The case of Sicilian Mafia".](https://arxiv.org/abs/2003.05303v1)

The work done by Cavallaro et al. was reproduced using different data obtained from [Ucinet](https://sites.google.com/site/ucinetsoftware/datasets/covert-networks/ndrangheta-mafia-2) based on pp.87-110 of the document named "Operazione Infinito"(a court document related to the pre-trial custody order issued by the judge for preliminary investigations in Milan concerning the investigation related to the Ndrangheta criminal organization that operated in Lombardy in the early 2000s.).

Tests were also carried out using a human capital approach by extending the source work. This required the generation of a real dataset, based on raw data derived from legal acts, related to a mafia organization that operated in Lombardy in the first decade of the 2000s.

# Data Description
156 x 47 Bipartite graph - persons X events (summits), undirected binary ties. Attendance at events have been registered by police authorities through wiretapping and observations during the large investigation called "Operazione Infinito".

156 Nodes - Ndrangheta members + events (meetings attended by the criminal to discuss activity and other matters)

156 Nodes - Ndrangheta members + "locale"(Small local power management organization) + ruolo (nodebis.csv)

---
Dataset Ndrangheta2 from Ucinet: https://sites.google.com/site/ucinetsoftware/datasets/covert-networks/ndrangheta-mafia-2

[1] Cavallaro, L., and Ficara, A., and De Meo, P., and Fiumara, G., and Catanese, S., and Bagdasar, O., and Liotta, A. (2020). Disrupting Resilient Criminal Networks through Data Analysis: The case of Sicilian Mafia. http://arxiv.org/abs/2003.05303v1
