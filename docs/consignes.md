# Introduction
Les sujets proposés ont pour ambition de vous amener à exercer une activité d’architecte dans le cadre des miniprojet.
On distingue deux types de sujets, méthodologique ou technologique : les premiers portent sur
l’amélioration d’un processus de développement alors que les seconds portent sur l’amélioration d’un produit
(une application logicielle produite par le processus de développement).
L’architecture étant tournée de manière prépondérante vers le respect des facteurs de qualité, ces derniers
constitueront un point de repère tout au long de ce mini-projet. La norme ISO9126 :2001 sera utilisée comme
référentiel avec ses 6 « caractéristiques » et ses 27 « sous-caractéristiques ». 

# Structure du sujet
Chaque sujet est décrit par 3 sections :
 - titre : sans commentaire
 - technique : définit les principes qui devront être étudié (pour être en particulier appliqué au contexte).
 - contexte : définit le client ou l’équipe de développement qui appliquera la technique. 
# Exemple de sujet
Sujet 01 : outil de gestion de la relation client
• Technique étudiée : ce sujet est orienté architecture fonctionnelle. On s’attachera à définir ce qu’on
entend par GRC (gestion de la relation client, ou CRM, Customer Relatiobship Management). On
définira les grandes briques fonctionnelles de ce type de système ainsi que les points clés d’un plan de
déploiement. On expliquera également la différence entre un PGI (ERP) et une GRC. On s’appliquera
enfin à étudier les capacités des GRC à gérer et à s’interconnecter avec des réseaux sociaux pour par
exemple organiser des évènements, suivre les clients en fonction de leur activité sur le réseau social, …
• Contexte : mise en place d’une GRC pour la gestion de la relation avec les anciens et les industriels du
département ASI

# Résultats attendus (deliverables)

## Monographie - Partie A
 A0 : texte synthétique. On précisera notamment si ce projet a pour but d’améliorer un
processus ou un produit.
 A1. liste de 10 mots-clés
 A2. webographie de 3 sites qualifiés
 A3. bibliographie de 3 livres avec la mise en exergue des sections qui vous semblent
pertinentes dans la table des matières
 A4. liste des trois grandes organisations dans le secteur de cette technique (qu’ils
soient des organisme de standardisation, des communautés du logiciels libres ou des
sociétés privées), on décrira chaque organisation en une dizaine de lignes et on
montrera sa contribution à la technique étudiée. Au moins une des organisations doit
mettre à disposition un livre blanc sur le sujet étudié
 A5. liste de 3 sous-caractéristiques prises parmi les 21 de ISO9126 (qu’on appelle
aussi critères chez McCall) auquel répond cette technique, et ce tout particulièrement
dans le contexte indiqué.
 A6. Liste d’au moins deux indicateurs de base (ou mesures au sens ISO9126) et d’au
moins un indicateur dérivé pour chacun des trois facteurs/sous-facteurs identifiés dans
la question A5.
 A7. Structurer les différentes références du référentiel théorique (ainsi que les
références que vous avez identifiées). Dans le cas où le référentiel théorique
comprend un (voire des) catalogue(s) de patterns, on précisera notamment la liste des
thématiques (problem area) ainsi que la grille de présentation des patterns (les
rubriques de la description d’un pattern, et leur sémantique). 

## Monographie - Partie B
 B1. texte de 2 à 3 pages qui montre les principales caractéristiques des approches
techniques sur le sujet (on utilisera de manière privilégiée les patterns pour étayer la
description)
 B2. liste des solutions technologiques concurrentes mettant en œuvre une des
approches techniques (de manière plus ou moins explicite), et parmi cette liste, le
choix de deux solutions technologies Y et Z pour prototypage. Pour les solutions 
choisies, assurez-vous que vous êtes bien en mesure de les mettre en œuvre (prérequis
accessibles, licences d’évaluation disponibles en cas de modèle payant, …)
 B3. description technique des deux solutions choisies (X et Y)
 B4. liste de métriques permettant de comparer (benchmarker) les deux solutions
choisies tout particulièrement sur les facteurs retenus en conclusion de la partie A
 B5. découpage en tâches (Work Breakdown Structure) montrant comment vous allez
parvenir à réaliser deux prototypes. 
Partie C
o C1. Description de l’architecture mise en place pour réaliser une expérience
permettant sur la solution technique X de mesurer les indicateurs contribuant à la
comparaison. Par description de l’architecture est entendu un diagramme de déploiement (au
sens UML) faisant apparaître le(s) noeud(s) matériel(s), les composants ainsi que les artefacts
utilisés par les composants. On veillera à ce que les composants présentés aient, dans leur
ensemble, une granularité cohérente.
o C2 : idem à C1 appliqué sur Y (décrire l'architecture technique du test, sachant que
description technique de la solution a été réalisée en B
o Remarque générale
 citez vos sources : vous avez probablement utilisé quelques ressources (billet dans des
blogs, tutoriels, …) sur le web pour rédiger votre monographie. 

## Prototype pY 
avec la technologie Y sélectionnée

## Prototype pZ
avec la technologie Z sélectionnée
