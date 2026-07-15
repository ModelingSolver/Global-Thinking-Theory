# GTT — Global Thinking Theory
### Synthèse de travail — juillet 2026

---

## Point de départ : pourquoi pas GWT tel quel

GWT (Baars/Dehaene) part directement d'un mécanisme (compétition → ignition → broadcast) sans jamais poser de critères objectifs de ce qu'est la conscience — contrairement à des domaines comme la biologie où "la vie" a des briques identifiables (autonomie, reproduction, évolution) même sans définition stricte. GTT part de l'exigence inverse : **extraire des briques vérifiables de l'extérieur avant de statuer sur le mécanisme**, et accepter explicitement qu'on ne sait pas *où* se situe la conscience — seulement ce qu'un système candidat doit présenter.

---

## Les briques (état actuel, 5)

### 1. Architecture modulaire
Le système n'est pas un bloc monolithique — il est composé de sous-systèmes spécialisés distincts (attention, mémoire, action) qui communiquent entre eux. Consensuel à travers toutes les théories (GWT, PP, RPT), même quand elles divergent sur le *comment* de la communication.

### 2. Métacognition
Le système a une représentation de son propre traitement, pas seulement du monde extérieur — capacité à évaluer, monitorer, ajuster ses propres processus. C'est la brique que Graziano (AST) place au centre : la conscience comme sous-produit d'auto-modélisation, pas comme mécanisme de sélection en soi.

### 3. Priorisation dynamique
Mécanisme continu (pas nécessairement une compétition winner-take-all) qui hiérarchise ce qui mérite traitement/ressource maintenant. Explicitement **pas** de la compétition façon GWT — plus proche d'un gradient continu (variance, precision-weighting façon Friston) que d'un switch binaire.

### 4. Continuité temporelle / mémoire
Le système maintient un fil entre l'état actuel et les états passés — sans ça, pas de narrativité, pas de mémoire de travail exploitable. Distincte de la brique 3 : la priorisation opère à l'instant t, la continuité opère à travers le temps.

### 5. Plasticité continue (la brique différenciante)
Le système peut modifier sa propre structure **pendant qu'il opère**, pas seulement dans une phase d'entraînement séparée et gelée ensuite. C'est le point de divergence le plus net avec l'architecture LLM classique (poids figés à l'inférence) — et potentiellement la brique la plus originale de GTT par rapport à la littérature existante, qui n'en fait généralement pas un critère explicite de la conscience.

---

## Mécanisme central

Explicitement **pas la compétition** façon GWT. Un mix des quatre premières briques opérant en parallèle, avec une modulation continue plutôt que des événements discrets de sélection/diffusion. Encore flou à ce stade — c'est le point le moins formalisé de GTT actuellement, à préciser.

---

## Ce que GTT cherche à faire (et ce qu'elle ne cherche pas à faire)

GTT n'a **pas** pour objectif d'expliquer pourquoi un système produirait du ressenti (le hard problem reste explicitement ouvert, non résolu, non contourné par un tour de passe-passe du type "le ressenti est juste encore une loop"). 

L'objectif est **fonctionnel et opérationnel** : servir de socle conceptuel à la construction d'un exocortex utile — un système cognitif augmentatif réel, pas une preuve de conscience artificielle. Les 5 briques sont des critères d'ingénierie autant que des critères théoriques : un système qui les présente toutes est un système cognitivement plus riche et plus utile, indépendamment de la question de savoir s'il "ressent" quoi que ce soit.

---

## Ancrage dans l'existant (BTM / OMEGA / C3)

| Brique | Composant BTM/OMEGA correspondant |
|---|---|
| 1. Modularité | Architecture globale BTM (boucles séparées : attentionnelle, convergence, sédimentation, métacognition) |
| 2. Métacognition | Boucle Métacognition System 3 (Monitor + Tuner, ajustement des seuils) |
| 3. Priorisation dynamique | C3 Cube — variance basse/haute → Mode Direct/Délibératif |
| 4. Continuité | Mémoire organique CT/MT/LT, heat scoring |
| 5. Plasticité continue | HyperNeurones sans backprop — capacité théorique à évoluer en continu, contrairement au LLM figé post-training utilisé pour la formulation |

Point de vigilance déjà identifié : la brique 5 est actuellement plus une **direction ouverte qu'une réalisation** dans l'archi actuelle — le LLM de formulation (Mistral) reste figé, seul le C3/HyperNeurone a le potentiel de plasticité continue. À vérifier si ce potentiel est effectivement exploité ou juste latent dans l'implémentation actuelle.

---

## Ce qui reste non résolu (assumé comme tel)

- Le mécanisme central de la brique 3 (priorisation) est nommé mais pas formalisé — "plus subtil qu'une compétition" reste à date une intuition, pas un modèle.
- Le ressenti n'est délibérément pas traité comme une 6ème brique ni logé dans une des 5 — laissé ouvert plutôt que refermé prématurément.
- Risque identifié et à surveiller : ne pas laisser BTM (l'implémentation) devenir une preuve de GTT (la théorie) par glissement — "ça marche" et "c'est une théorie vraie de la cognition" sont deux critères distincts qu'il faut garder séparés.