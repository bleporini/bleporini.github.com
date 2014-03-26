---
layout: page
title : Formation profiling applicatif
group: navigation
---
{% include JB/setup %}

Le profiling applicatif est l'observation de l'exécution d'une
application dans son environnement à l'aide de l'outil associé
 à cette activité, le profiler.

L'objectif est d'identifier rapidement des éléments qui nuisent
à la performance de l'application, aussi bien en termes de
temps de réponse que de scalabilité, en collectant des
 informations telles que:
- Consommation abusive de ressources aussi bien CPU que mémoire
- Temps d'exécution excessifs
- Détection de points de contentions
- Observations des échanges inter-applicatifs ou avec les
systèmes de gestion de persistance

## Programme
La formation porte sur l'utilisation de JProfiler et des outils
fournis dans le JDK. Elle s'étend sur deux jours et aborde les points suivants:

- Rappel des concepts de traitements parallèles et de
concurrence en Java.
- Rappel de l'organisation de la gestion de la mémoire sur la machine
virtuelle Java
- Découverte du logiciel de profiling
- Entraînement à la détection des problèmes de performance
et de scalabilité sur une application web pédagogique. Les
stagiaires doivent en analyser le comportement afin de localiser
les composants responsables des ralentissements.
Chaque hypothèse est validée
par le formateur et donne lieu au déblocage du problème, permettant
de passer à l'analyse du point suivant.
- Intégration du profiling dans le processus du développement
- Snapshotting et profiling hors ligne.

## Objectifs

A l'issue de la session les stagiaires sont en capacité de
- Qualifier les consommations de CPU
- Examiner le contenu de la mémoire et expliquer les fuites
- Apprécier l'utilisation des systèmes de persistance
- Dimensionner les pools de threads et les pools JDBC
- Identifier le code induisant la contention dans l'application
(concurrence sur les verrous)
