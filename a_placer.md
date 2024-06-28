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
