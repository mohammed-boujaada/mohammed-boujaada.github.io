---
title: "Identification de cibles médicamenteuses par GNN"
excerpt: "Projet de recherche de Master (avec Mohamed Zahir). PyTorch Geometric, GAT, STRING, DisGeNET.<br/>[Code sur GitHub](https://github.com/mohammed-boujaada/gnn-drug-target-identification)"
collection: portfolio
---

Classification de gènes associés au diabète sur un réseau d'interactions protéine-protéine humain, avec attention parcimonieuse et élagage de neurones.

- Graphe construit à partir de STRING (score ≥ 700) : 15 882 nœuds et 236 712 arêtes, avec 74 gènes positifs issus de DisGeNET.
- GAT de référence évalué sur 5 graines, comparé à SGAT (portes d'arêtes apprenables et régularisation L0) : 71,48 % d'arêtes en moins.
- Élagage structuré : représentation cachée réduite de 128 à 28 neurones, ROC-AUC de test de 0,7140.
- Classement des gènes retrouvant FN1, RAC1 et INS parmi les 30 premiers.

[Code sur GitHub](https://github.com/mohammed-boujaada/gnn-drug-target-identification)
