# Installation des logiciels de développement

## Objectifs

L'objectif de cette partie est d'installer les outils suivants sur votre machine :

- Git
- Node.js
- Dotnet 8.0
- Visual Studio Code
- Visual Studio 2022

Nous supposons ici que votre machine personnelle est/a :

- Un PC tournant sous Windows 10/11
- Un minimum de 8Go de mémoire vive
- Un minimum de 40Go d'espace disque libre
- Les outils ne sont pas pré-installés

## Exercice 1 - Installation de Git

- Naviguez le site [https://git-scm.com](https://git-scm.com)
- Cliquez sur le bouton "Download for Windows"

![Site Git ](img/git_site_01.png)

- Téléchargez le logiciel Git en choisissant la version correspondant à votre machine, normalement la version 64 bits.

![Choix de la version de l'installateur](img/git_site_02.png)

- Lancez le programme d'installation que vous venez de télécharger
- Suivez les instructions et optez pour les valeurs par défaut
- Une fois l'installation terminée, [Ouvrez un invite de commande](LIGNE_COMMANDE.md) et validez qu'en tapant ```git --version``` vous obtenez la version de Git installée (la version peut varier) :

![Validation installation Git](img/git_installation_validation.png)

## Exercice 2 - Installation de Node.js

- Naviguez le site [https://nodejs.org](https://nodejs.org)
- Choisissez le lien qui permet de télécharger la version LTS (Long Term Support) de Node.js.

![Site Node.js et choix de la version LTS](img/node_site_01.png)

- Lancez le programme d'installation que vous venez de télécharger
- Suivez les instructions et optez pour les valeurs par défaut
- Une fois l'installation terminée, [Ouvrez un invite de commande](LIGNE_COMMANDE.md) et validez qu'en tapant ```node --version``` vous obtenez la version de Node.js installée (la version peut varier) :

![Validation installation Node.js](img/node_installation_validation.png)

## Exercice 3 - Installation de Dotnet 6.0

- Naviguez le site [https://dotnet.microsoft.com](https://dotnet.microsoft.com)
- Cliquez sur le bouton "Download"

![Site dotnet](img/dotnet_site_01.png)

- Repérez la version "Long Term Support" 6.0
- Choisissez le lien ".NET SDK x64"

![Choix de la version de l'installateur](img/dotnet_site_02.PNG)

- Lancez le programme d'installation que vous venez de télécharger.
- Suivez les instructions et optez pour les valeurs par défaut
- Une fois l'installation terminée, [Ouvrez un invite de commande](LIGNE_COMMANDE.md) et validez qu'en tapant ```dotnet --version``` vous obtenez la version de dotnet installée (la version peut varier) :

![Validation installation dotnet 6.0](img/dotnet_installation_validation.png)

## Exercice 4 - Installation de Visual Studio Code

- Naviguez le site [https://code.visualstudio.com](https://code.visualstudio.com)
- Cliquez sur le bouton "Download for Windows"

![Site Visual Studio Code](img/vsc_site_01.png)

- Lancez le programme d'installation que vous venez de télécharger
- Suivez les instructions et optez pour les valeurs par défaut
- Une fois l'installation terminée, [Ouvrez un invite de commande](LIGNE_COMMANDE.md) et validez qu'en tapant ```code --version``` vous obtenez la version de Visual Studio Code installée (la version peut varier) :

![Validation installation Visual Studio Code](img/vsc_installation_validation.png)

## Exercice 5 - Installation de Visual Studio 2022

- Naviguez le site [https://visualstudio.microsoft.com](https://visualstudio.microsoft.com)
- Cherchez le bouton "Télécharger Visual Studio" et choisissez l'option "Community 2022".

![Site Visual Studio](img/vs_site_01.png)

- Lancez le programme d'installation que vous venez de télécharger.
- Suivez les instructions jusqu'à arriver à la fenêtre des "Détails de l'installation"
- Dans cette fenêtre, cochez les options suivantes :
  - Développement web et ASP.NET
  - Développement Node.js
  - Développement .NET Desktop

![Choix des modules à installer](img/vs_installation_choix_modules.png)

- Cliquez sur le bouton "Installer"
- N'attendez pas la fin de l'installation (Peut prendre plusieurs dizaines de minutes dépendant de votre configuration matérielle et réseau!) pour continuer les exercices. Appuyez le lien ci-dessous pour retourner à la page principale des exercices.

[Retour à la page principale](README.md)
