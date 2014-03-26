---
layout: page
title : Prestations
group: navigation
---
{% include JB/setup %}

## Audit technique

L'audit technique est une analyse du projet visant à identifier les points qui peuvent limiter l'application tant en
termes de performances que de scalabilité ou encore d'évolutivité. L'étude est focalisée sur la recherche d'anti-patterns
récurrents et de pratiques déconseillées. L'audit est ensuite consolidé avec une observation de l'exécution de
l'application.

### Démarche

L'audit se découpe en deux volets:

**Étude statique**:
- Examen de la couche de persistence: ORM, gestion des transactions, methodes d'interrogation
- Graphe de dépendances
- Recherche d'anti-patterns courants
- Qualité des tests

**Étude dynamique**:
- Observation de l'utilisation CPU
- Empreinte mémoire: taille des caches, taille des sessions http, etc.
- Examen des échanges de l'application dans son environnement : utilisation des systèmes de persistance, échanges
inter-applicatifs (WS, JMS, etc.)

### Enjeux

L'audit ne doit pas être uniquement considéré dans sa dimension technique, le côté humain prend une place primordiale
dans la réussite de l'exercice car le risque est que la démarche ne soit vécue par l'équipe technique comme un constat
d'échec ou une inspection. Son implication dès le début de l'étude est une priorité afin que cette dernière puisse
être considérée comme une opportunité.

Côté donneur d'ordre, la synthèse de l'audit offre des éléments qui permettent de prioriser et de planifier les chantiers
techniques à mener pour augmenter les capacités ou l'aptitude à évoluer du système d'information évalué.

### Livrables

La prestation donne lieu à la livraison d'un document listant les faits techniques relevés. Ils sont évalués sur deux critères:
la criticité et le coût de
leur résolution. Chacun d'entre eux est ensuite accompagné d'une recommandation contextualisée: une décision de
reprise du code dépend fortement de la condition du projet (en production, en qualification, en fin de vie, etc.).

La prestation est clôturée par la restitution finale.


## Expertise ponctuelle

L'expertise ponctuelle est une prestation permettant d'apporter un oeil neuf au sujet d'une application traversant des problèmes
de performance. L'objectif est de produire rapidement une liste de recommandations techniques permettant d'orienter les
travaux de l'équipe de développement afin d'atteindre la conformité vis-à-vis des exigences de tenue de charge ou des
engagements sur les temps de réponse.


