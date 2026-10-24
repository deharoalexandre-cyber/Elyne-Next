# Architecture — Elyne Next

[English](architecture.en.md) · [Présentation](../README.md)

## Flux simplifié

Interaction → orchestration et contexte → modèle résident via EIE → outils bornés → mémoire/RAG/journal persistants → réponse sourcée.

## Composants et frontières

- Le modèle résident fournit l'inférence ; la mémoire, les croyances versionnées et les documents demeurent dans des magasins propres à l'application.
- La récupération combine index lexical et embeddings ; la provenance accompagne les éléments réutilisés dans le contexte.
- Les outils accèdent à des ressources autorisées. La présence d'une interface d'outil ne prouve pas à elle seule l'isolation OS ou le refus de tout chemin direct.

Ce schéma textuel décrit l'architecture du produit. Il ne remplace pas une vérification sur un build, un matériel et une configuration précis. Les [éléments de preuve](evidence.md) indiquent ce qui a été effectivement documenté.
