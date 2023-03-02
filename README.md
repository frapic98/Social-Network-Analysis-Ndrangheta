# Social-Network-Analysis-Ndrangheta
The project is based on ["Disrupting Resilient Criminal Networks through Data Analysis: The case of Sicilian Mafia",](https://arxiv.org/abs/2003.05303v1) in which they try to unravel the structure of Sicilian mafia gangs, based on two real data sets, and get insights on how to effectively disrupt them.

The work done by Cavallaro et al. was reproduced using different data obtained from [Ucinet](https://sites.google.com/site/ucinetsoftware/datasets/covert-networks/ndrangheta-mafia-2) based on pp.87-110 of the document named "Operazione Infinito"(a court document related to the pre-trial custody order issued by the judge for preliminary investigations in Milan concerning the investigation related to the Ndrangheta criminal organization that operated in Lombardy in the early 2000s.).

The process of removing nodes within the network (represents arrests by law enforcement of one or more network elements) essay robustness and will be analyzed on the two types of capital in criminal networks (human and social capital). Following the social capital approach we will use metrics to identify the most influential individuals with a central role in the criminal network. To this end, we will test four different centrality metrics : Degree centrality, Betwenness centrality, Clossness centrality, and Collective Influence.

Cavallato et al. [1] apply the social capital approach to dismantle the criminal network by referring only the connections or ties between actors in a network. The other type type of approach, human capital originates from economics, and refers to the personal attributes and/or resources possessed by actors within a social network. 

In order to apply the human capital approach, it will be necessary to modify the dataset based on "Operazione Infinito". On pp. 21-32 there is a list of the various "locali"(structure that organizes the underworld management of the territory) with the various members and their roles within. 

The experimental process used to disrupt the network and evaluate the effects of node removal(represents arrests by law enforcement of one or more network elements) will be tested under different conditions and strategies, such as network unweighted/weighted or apply different node elimination methods.

# Data Description
156 x 47 Bipartite graph - persons X events (summits), undirected binary ties. Attendance at events have been registered by police authorities through wiretapping and observations during the large investigation called "Operazione Infinito".

156 Nodes - Ndrangheta members + events (meetings attended by the criminal to discuss activity and other matters)

156 Nodes - Ndrangheta members + "locale"(small local power management organization) + ruolo  ----> nodebis.csv


![visualization7](https://user-images.githubusercontent.com/33379163/222515244-208cdc29-18b7-401f-9882-52d220da10ee.png)




---

[1] Cavallaro, L., and Ficara, A., and De Meo, P., and Fiumara, G., and Catanese, S., and Bagdasar, O., and Liotta, A. (2020). Disrupting Resilient Criminal Networks through Data Analysis: The case of Sicilian Mafia. http://arxiv.org/abs/2003.05303v1

Dataset Ndrangheta2 from Ucinet: https://sites.google.com/site/ucinetsoftware/datasets/covert-networks/ndrangheta-mafia-2
