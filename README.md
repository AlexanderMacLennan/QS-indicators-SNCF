# qsindicators

## OBJECTIF
Le but de ce projet est d'extraire les informations concernant les indicateurs de service d'un contrat. Ce contrat se trouve à l'adresse : https://portail-idfm.cdn.prismic.io/portail-idfm/da6142b2-d07c-474a-8aff-18c3cb9e0291_Contrat+IDFM_SNCF_Annexes_VDef_HorsConfidentielles.pdf
A priori, la majorité des informations concernant les indicateurs de qualité de contrat se trouvent dans la section : D. INDICATEURS DE QUALITE DE SERVICE SOUMIS A PENALITES ET BONUSMALUS
On veut récupérer la liste des indicateurs de Qualité de services
Pour chaque indicateurs, on veut récupérer:
	- La thématique de l'indicateur
	- La méthode de mesure, c’est-à-dire la formule mathématique permettant de calculer l'indicateur
	- Les exonérations, c'est-à-dire la liste des situations pour lesquelles la mesure peut-être neutralisée
	- Le système d'intéressement, c’est-à-dire les valeurs "Objectif", "Inférieur" et "Supérieur"

## Détail du fonctionnement du document
La section D : INDICATEURS DE QUALITE DE SERVICE SOUMIS A PENALITES ET BONUSMALUS, comprend en introduction (dans l'annexe II-D-1) un tableau récapitulatif de l'ensemble des indicateurs


Extrait du tableau des indicateurs de Qualité de service

Dans la suite du document, chaque thématique fait l'objet d'une annexe dans laquelle chaque indicateur dispose de sa section. 

## DISCLAIMER & CONTEXTE
La MEC du réseau de transport d'IDFM va entrainer la multiplication des contrats de ce type entre les OT (opérateur de transport) et IDFM. A ce titre, il est essentiel que l'outil d'extraction des indicateurs de QS (qualité de service) soit agnostique de tout format.
L'extraction des indicateurs de QS se fait manuellement à l'heure actuelle. Avec la multiplication des contrats à prévoir avec la MEC, il apparait essentiel d'être en capacité d'automatiser ce processus. 

