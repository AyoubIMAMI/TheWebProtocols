# Header Fields Exploitation

Ce projet est une démonstration de l'exploitation des champs d'en-tête HTTP pour récupérer des informations sur un serveur web. Le projet consiste en une page HTML qui affiche plusieurs boutons, chacun d'eux étant associé à une fonction JavaScript qui récupère et affiche des informations différentes en fonction de l'en-tête HTTP envoyé par le serveur.

## Comment utiliser
Clonez le projet sur votre ordinateur.

Ouvrez la solution avec Visual Studio et cliquez sur Start

Ouvrez votre navigateur et accédez à http://localhost:9000.

## Fonctionnalités
L'application permet d'afficher les statistiques suivantes :

- Types de serveurs :
  - Affiche les différents types de serveurs web utilisés par les sites web visités.
  - Intérêt : utile pour déterminer des vulnérabilités connues ou des problèmes de compatibilité avec certains clients.
- Âges des pages :
  - Affiche les sources des pages, leur âge moyen et l'écart type.
  - Intérêt : peut aider à identifier des pages obsolètes qui doivent être mises à jour ou supprimées.
- Données de connexion :
  - Affiche les différentes informations de connexion.
  - Intérêt : peut aider à diagnostiquer les problèmes de performance.
- Encodage de transfert :
  - Affiche les encodages de transfert pris en charge par les sites visités.
  - Intérêt : peut être utile pour diagnostiquer les problèmes de compatibilité avec les clients.
- Vary :
  - Affiche les différents en-têtes "Vary" utilisés par les sites visités.
  - Intérêt : peut aider à identifier les problèmes de compatibilité avec certains clients.
- Plage acceptée :
  - Affiche les plages de réponses acceptées par les sites visités.
  - Intérêt : peut être utile pour la mise en cache des réponses.
  
## Motivation des scénarios tests
Le choix de ces scénarios tests se justifie par le fait qu'il est important de veiller au confort des clients.
Dans l'ensemble, ces fonctionnalités peuvent aider les administrateurs de serveurs web à diagnostiquer les problèmes de performance, à optimiser la compatibilité avec les clients et à améliorer la sécurité de leurs serveurs web. Toujours dans l'optique de fournir le meilleur service possible aux clients.

## Auteur
[Ayoub Imami](https://github.com/AyoubIMAMI)
