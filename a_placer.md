#### Choses à places

Au départ je n’avais aucune connaissance et compétence en « React Native ». Je me suis donc mis à recueillir des informations utiles pour me familiariser avec cette dernière.

Grâce à des tutos sur YouTube [Mettre les liens]
J’ai d’abord créé une première application pour me familiariser au Framework. Elle devait uniquement pouvoir afficher un « Hello World ! ». Le premier programme classique dans chaque langage.

Après cette première étape d’apprentissage je suis passé à la rechercher d’informations sur les compétences nécessaires permettant de comprendre comment l’espace client web procède pour proposer le paiement en ligne.

J’ai découvert qu’elle utilise l’API du service de paiement en ligne appelé « Payzen ».

[Détaillé Payzen ] [Mettre des images]

Ce qui permet aussi aux locaux de régler leurs factures en utilisant des cartes bancaires locales.

[Exemple de carte] [Mettre des images]

C’est une des raisons pour laquelle il est nécessaire d’utiliser cette l’API pour l’application.

Les autres solutions possibles sont [Donnés exemples] sont orientées mono-plateforme [Définir] (Android et Apple)

J’ai donc effectué des recherches sur l’API de Payzen me permettant d’obtenir une documentation sur son utilisation dans une application mobile « React native » ou web.

De plus notre service client web le faisait déjà aussi du coup je savais que j’avais une autre voie de recherche.

Je n’ai pas trouvé de doc sur l’utilisation de Payzen dans une app mobile mais il y a possibilité de l’utiliser dans une app web et la façon de le faire était de rediriger l’utilisateur vers une page web où se trouve le montant qu’il souhaite régler et le choix des cartes.

Du coup j’ai pensé à ouvrir une page web directement dans l’application pour avoir l’API Payzen de l’entreprise directement affiché. Ce qui m’a mené vers la deuxième partie de mes recherches.

A ce point de mes recherches il fallait savoir s’il est possible d’ouvrir une fenêtre web dans une app mobile faite avec « React Native ». J’ai trouvé dans la documentation d’expo que la fonction « openBrowserAsync » existe et qu’elle permet de faire cela.
Après avoir créé une application test pour voir si elle ouvre bien le navigateur (ce qui a été réussi)

#### Pas certains d'intégrer

###### Stripe et PayPal

Pour intégrer une expérience de paiement, « Expo » expose dans sa documentation un guide détaillé sur la mise en place et l’utilisation du kit de développement (Software Development Kit ou SDK) de « Stripe » pour « React Native » nommé « @stripe/stripe-react-native ».

![alt text](image.png)

https://docs.expo.dev/versions/latest/sdk/stripe/

Pour plus de précision, le kit de développement « @stripe/stripe-react-native » est une bibliothèque d’outils pouvant être facilement utilisé avec Expo et qui permet d’intégrer les fonctionnalités de

Il y a deux exemples populaires Stripe et Paypal.

#### CHATGPT

Plan d'Actions pour l'Amélioration de la Gestion des Stocks chez XYZ

1. Introduction du Plan d'Actions
   1.1. Contexte
   L'entreprise XYZ, spécialisée dans la distribution de matériel électronique, rencontre depuis plusieurs années des problèmes récurrents liés à la gestion de ses stocks. Ces problèmes se manifestent principalement par des surstocks coûteux, des ruptures de stock fréquentes, et une inefficacité générale du processus logistique. Ces dysfonctionnements ont un impact direct sur la satisfaction des clients, la compétitivité de l'entreprise, et ses coûts opérationnels.

Les causes identifiées incluent une mauvaise prévision des demandes, une coordination insuffisante entre les départements des ventes, des achats et de la logistique, ainsi qu'une absence d'outils adaptés pour suivre les niveaux de stock en temps réel.

1.2. Objectifs du Plan d'Actions
Le principal objectif de ce plan d'actions est de restructurer la gestion des stocks pour réduire les coûts liés au surstockage, éviter les ruptures de stock, et améliorer la satisfaction des clients. Pour atteindre cet objectif, il sera nécessaire de :

Implémenter un système de prévision des demandes plus précis.
Optimiser les niveaux de stock minimum et maximum.
Améliorer la communication entre les différents départements concernés.
Former le personnel aux nouvelles procédures et aux outils mis en place. 2. Définition des Actions
2.1. Action 1 : Analyse des Processus Actuels de Gestion des Stocks
2.1.1. Contexte et Justification
L'analyse des processus actuels est essentielle pour comprendre les causes profondes des problèmes de gestion des stocks. Actuellement, les systèmes de commande sont gérés de manière indépendante par chaque département, ce qui entraîne des incohérences dans les niveaux de stock et des erreurs dans la prévision des besoins.

2.1.2. Détails Opérationnels
Étapes de l'analyse : Cette analyse comprendra un audit interne des processus actuels, des interviews avec les responsables des départements concernés, et un examen des données historiques de stock.
Outils : Utilisation de diagrammes de flux de processus (process mapping) pour visualiser le fonctionnement actuel, et analyse des écarts (gap analysis) pour identifier les points faibles.
Résultats attendus : Identification des inefficacités actuelles et recommandations pour les améliorations nécessaires.
2.1.3. Scénarios Alternatifs
En l'absence d'une analyse approfondie, les problèmes pourraient être abordés de manière superficielle, ce qui ne permettrait pas d'identifier les véritables causes des dysfonctionnements.

2.1.4. Interdépendance
Cette action est cruciale car elle servira de base pour toutes les autres actions. Une fois les problèmes actuels clairement identifiés, il sera possible de concevoir des solutions adaptées.

2.1.5. Calendrier
Début : Semaine 1
Fin : Semaine 3
Responsable : Chef de projet logistique
2.2. Action 2 : Mise en Place d’un Système de Prévision des Demandes
2.2.1. Contexte et Justification
La prévision des demandes actuelle repose principalement sur l'expérience des responsables des ventes, ce qui entraîne des erreurs fréquentes. Un système de prévision automatisé permettrait de baser les décisions sur des données historiques et des algorithmes prédictifs.

2.2.2. Détails Opérationnels
Choix du logiciel : Sélectionner un logiciel de prévision des demandes qui peut être intégré avec le système ERP existant.
Formation : Organiser des sessions de formation pour les équipes de vente et de logistique sur l'utilisation du nouveau logiciel.
Implémentation : Paramétrer le logiciel, importer les données historiques, et tester les prévisions sur une période d’essai de 3 mois.
2.2.3. Scénarios Alternatifs
Sans ce système, l'entreprise continuerait à subir les inconvénients d'une gestion approximative des stocks, avec des impacts financiers significatifs.

2.2.4. Interdépendance
Les résultats de cette action influenceront directement l'efficacité de l'optimisation des niveaux de stock (Action 3).

2.2.5. Calendrier
Début : Semaine 4
Fin : Semaine 8
Responsable : Responsable IT et Responsable des achats
2.3. Action 3 : Optimisation des Niveaux de Stock Minimum et Maximum
2.3.1. Contexte et Justification
Les niveaux de stock actuels sont basés sur des approximations qui ne tiennent pas suffisamment compte des fluctuations de la demande. Cela conduit à des surstocks ou à des pénuries, selon les cas.

2.3.2. Détails Opérationnels
Revue des niveaux actuels : Utiliser les données issues du nouveau système de prévision pour recalculer les niveaux de stock minimum et maximum pour chaque produit.
Mise à jour des procédures : Documenter les nouvelles procédures de réapprovisionnement basées sur les niveaux de stock optimisés.
Suivi : Mettre en place un système de surveillance continue des stocks pour ajuster les niveaux en fonction des variations de la demande.
2.3.3. Scénarios Alternatifs
Sans ajustement des niveaux de stock, les problèmes de surstockage et de ruptures persisteraient, entraînant des coûts supplémentaires pour l'entreprise.

2.3.4. Interdépendance
Cette action dépend directement des résultats de la mise en place du système de prévision des demandes (Action 2).

2.3.5. Calendrier
Début : Semaine 9
Fin : Semaine 12
Responsable : Responsable des stocks
2.4. Action 4 : Amélioration de la Communication Interdépartementale
2.4.1. Contexte et Justification
La coordination entre les départements est actuellement insuffisante, ce qui entraîne des décisions incohérentes et des actions désynchronisées. Une meilleure communication est nécessaire pour aligner les objectifs et les actions des différents départements.

2.4.2. Détails Opérationnels
Mise en place de réunions hebdomadaires : Organiser des réunions inter-départementales pour discuter des prévisions de demande, des niveaux de stock, et des besoins d'approvisionnement.
Utilisation d'outils collaboratifs : Implémenter un logiciel de gestion de projet (comme Asana ou Trello) pour faciliter le suivi des actions et la communication entre les équipes.
Définition de processus clairs : Établir des protocoles pour la communication des informations clés, comme les prévisions de vente et les besoins en réapprovisionnement.
2.4.3. Scénarios Alternatifs
Sans cette amélioration de la communication, les efforts individuels des départements seraient mal coordonnés, ce qui nuirait à l'efficacité globale du plan d'actions.

2.4.4. Interdépendance
L'amélioration de la communication soutient l'implémentation efficace des autres actions, notamment l'optimisation des niveaux de stock.

2.4.5. Calendrier
Début : Semaine 2 (et en continu)
Fin : Continu (réunions hebdomadaires)
Responsable : Directeur des opérations
2.5. Action 5 : Formation du Personnel à la Gestion Optimisée des Stocks
2.5.1. Contexte et Justification
Pour assurer la durabilité des améliorations, il est essentiel que le personnel comprenne et adhère aux nouvelles pratiques de gestion des stocks. La formation est un élément clé pour garantir l'efficacité du plan d'actions.

2.5.2. Détails Opérationnels
Contenu de la formation : Les formations porteront sur l'utilisation du nouveau logiciel de prévision, les nouvelles procédures de réapprovisionnement, et l'importance de la communication inter-départementale.
Planification des sessions : Organiser plusieurs sessions de formation pour couvrir tous les départements concernés, avec un suivi post-formation pour évaluer l'impact et les besoins supplémentaires.
Documentation : Créer des manuels et des guides pratiques que le personnel pourra consulter après les formations.
2.5.3. Scénarios Alternatifs
Sans une formation adéquate, le personnel pourrait mal appliquer les nouvelles procédures, ce qui compromettrait les améliorations prévues.

2.5.4. Interdépendance
Cette action est fondamentale pour assurer la mise en œuvre correcte des autres actions, en particulier celles qui introduisent de nouveaux outils et processus.

2.5.5. Calendrier
Début : Semaine 10
Fin : Semaine 13
Responsable : Responsable RH 3. Méthodologie et Mise en Œuvre
3.1. Méthodologie
La méthodologie adoptée pour ce plan d'actions combine une approche analytique (audit et prévision) avec une mise en œuvre pratique (formation, communication). Chaque action sera déployée en suivant une méthodologie structurée, comprenant :

Analyse des processus actuels pour identifier les inefficacités.
Mise en œuvre d’outils technologiques pour optimiser la prévision des demandes.
Optimisation des processus existants pour s'assurer que les niveaux de stock sont adaptés.
Amélioration de la coordination inter-départementale pour synchroniser les efforts.
Formation continue pour garantir la durabilité des changements.
3.2. Planification
Un calendrier détaillé a été élaboré pour chaque action, incluant des jalons et des échéances claires. Voici un exemple de calendrier :

Semaine 1 à 3 : Analyse des processus actuels de gestion des stocks.
Semaine 4 à 8 : Mise en place du système de prévision des demandes.
Semaine 9 à 12 : Optimisation des niveaux de stock.
Semaine 10 à 13 : Formation du personnel.
Semaine 2 et continu : Amélioration de la communication inter-départementale (réunions hebdomadaires).
3.3. Ressources
Les ressources nécessaires pour chaque action ont été identifiées, y compris les ressources humaines, matérielles, et financières.

4. Ressources Nécessaires
   4.1. Ressources Humaines
   Chaque action sera supervisée par un responsable dédié, en collaboration avec des équipes interfonctionnelles :

Chef de projet logistique pour l’analyse des processus.
Responsable IT et Responsable des achats pour la mise en place du système de prévision des demandes.
Responsable des stocks pour l’optimisation des niveaux de stock.
Directeur des opérations pour la coordination des actions inter-départementales.
Responsable RH pour la planification et la mise en œuvre de la formation du personnel.
4.2. Ressources Matérielles et Financières
Budget pour le logiciel de prévision des demandes : Incluant les coûts d’achat, d’installation et de formation.
Coûts de formation : Engagement de formateurs externes et développement de supports de formation.
Outils de gestion de projet : Implémentation d’un logiciel collaboratif pour améliorer la communication inter-départementale. 5. Suivi et Évaluation
5.1. Indicateurs de Performance (KPIs)
Pour évaluer l'efficacité du plan d'actions, les indicateurs suivants seront utilisés :

Réduction des ruptures de stock : Objectif de réduction de 50% en six mois.
Réduction des surstocks : Objectif de diminution de 30% en trois mois.
Satisfaction client : Amélioration de 20% sur les six prochains mois, mesurée via des enquêtes.
Précision des prévisions de demande : Augmentation de la précision à 90% sur les six prochains mois.
5.2. Méthodes de Collecte des Données
Les données seront collectées à partir du système de gestion des stocks, des rapports de vente, et des retours clients. Les résultats seront analysés et présentés lors des réunions hebdomadaires inter-départementales.

5.3. Plan de Gestion des Risques
Une matrice des risques sera établie pour identifier les risques potentiels, les évaluer en fonction de leur probabilité et de leur impact, et définir des plans de contingence. Par exemple :

Résistance au changement : Organiser des séances de sensibilisation et de communication pour expliquer l’importance des nouvelles procédures.
Problèmes techniques avec le nouveau logiciel : Prévoir une équipe de support dédiée pour résoudre rapidement les incidents. 6. Conclusion
Le plan d'actions proposé a pour objectif de restructurer la gestion des stocks chez XYZ, en mettant en œuvre des solutions adaptées et en renforçant la coordination entre les départements. Les actions décrites permettront de réduire les coûts, d’améliorer la satisfaction des clients, et de garantir une gestion des stocks plus efficace. Ce plan est conçu pour être évolutif, avec une évaluation continue des résultats et des ajustements en fonction des besoins.

7. Annexes
   7.1. Annexe 1 : Diagramme des Processus Actuels de Gestion des Stocks
   Inclure un diagramme détaillant les flux de travail actuels pour illustrer les points d'inefficacité identifiés.
   7.2. Annexe 2 : Exemple de Tableau de Bord pour le Suivi des KPIs
   Fournir un exemple de tableau de bord qui sera utilisé pour le suivi des indicateurs de performance.
   Cet exemple développé atteint un niveau de détail qui permet de remplir 10 à 15 pages de texte en approfondissant chaque section avec des explications, des justifications, et des détails opérationnels. Tu pourrais l'adapter à ton propre contexte et ajouter des graphiques, des tableaux, et des annexes pour compléter le rapport.
