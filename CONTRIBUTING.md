# Guide de Contribution pour NexusAI-Core

Nous sommes ravis que vous envisagiez de contribuer à NexusAI-Core ! Votre expertise est précieuse pour nous aider à construire un futur connecté, intelligent et sécurisé. Ce guide vous aidera à démarrer et à comprendre nos processus de contribution.

## Table des Matières

1.  [Code de Conduite](#1-code-de-conduite)
2.  [Comment Contribuer ?](#2-comment-contribuer-)
    * [Signaler un Bug](#signaler-un-bug)
    * [Suggérer une Fonctionnalité](#suggerer-une-fonctionnalite)
    * [Contribuer du Code](#contribuer-du-code)
    * [Contribuer à la Documentation](#contribuer-a-la-documentation)
3.  [Configuration de Votre Environnement de Développement](#3-configuration-de-votre-environnement-de-developpement)
4.  [Processus de Soumission](#4-processus-de-soumission)
5.  [Questions ?](#5-questions-)

---

## 1. Code de Conduite

Nexus AI s'engage à créer un environnement accueillant et inclusif. En contribuant à ce projet, vous vous engagez à respecter notre [Code de Conduite](./CODE_OF_CONDUCT.md) (à créer si vous le souhaitez, sinon cette section peut être supprimée ou intégrée ici). Nous attendons de tous les contributeurs qu'ils fassent preuve de respect et de professionnalisme.

## 2. Comment Contribuer ?

Il existe de nombreuses façons de contribuer à NexusAI-Core, quel que soit votre niveau d'expérience.

### Signaler un Bug

Si vous trouvez un bug (une erreur ou un comportement inattendu), veuillez :
1.  Vérifier les [Issues existantes](https://github.com/NexusOccitech/NexusAI-Core/issues) pour voir si le bug a déjà été signalé.
2.  Si ce n'est pas le cas, ouvrez une [nouvelle Issue](https://github.com/NexusOccitech/NexusAI-Core/issues/new/choose) en utilisant le modèle "Bug Report".
3.  Fournissez autant de détails que possible :
    * Étapes pour reproduire le bug.
    * Comportement attendu et comportement observé.
    * Version du code et de votre environnement.
    * Captures d'écran ou logs pertinents.

### Suggérer une Fonctionnalité

Nous sommes toujours ouverts aux nouvelles idées pour améliorer Nexus AI ! Pour suggérer une fonctionnalité :
1.  Vérifiez les [Issues existantes](https://github.com/NexusOccitech/NexusAI-Core/issues) pour éviter les doublons.
2.  Ouvrez une [nouvelle Issue](https://github.com/NexusOccitech/NexusAI-Core/issues/new/choose) en utilisant le modèle "Feature Request".
3.  Décrivez clairement la fonctionnalité, pourquoi elle serait utile et comment elle s'aligne avec la vision de Nexus AI.

### Contribuer du Code

Nous accueillons les contributions de code pour des corrections de bugs, de nouvelles fonctionnalités, des améliorations de performance, etc.
1.  **Choisissez une Issue :** Identifiez une issue existante ou ouvrez-en une nouvelle pour votre contribution. Commentez l'issue pour indiquer que vous travaillez dessus.
2.  **Clonez le Dépôt :** `git clone https://github.com/NexusOccitech/NexusAI-Core.git`
3.  **Créez une Branche :** `git checkout -b feature/nom-de-votre-fonctionnalite` ou `bugfix/description-du-bug`.
4.  **Effectuez vos Modifications :** Développez votre code en suivant nos standards de codage (à définir si besoin, ex: PEP 8 pour Python).
5.  **Testez votre Code :** Assurez-vous que vos modifications n'introduisent pas de régressions et que les tests existants passent. Ajoutez de nouveaux tests si nécessaire.
6.  **Commettez vos Changements :** Rédigez des messages de commit clairs et concis.
    * `git commit -m "feat: Ajouter une nouvelle fonctionnalité X"`
    * `git commit -m "fix: Corriger un bug Y"`
7.  **Poussez votre Branche :** `git push origin feature/nom-de-votre-fonctionnalite`
8.  **Ouvrez une Pull Request (PR) :**
    * Ciblez la branche `main`.
    * Décrivez vos modifications, les problèmes qu'elles résolvent et les nouvelles fonctionnalités qu'elles ajoutent.
    * Référencez l'Issue correspondante (ex: `Closes #123`).

### Contribuer à la Documentation

Une bonne documentation est essentielle ! Si vous trouvez des erreurs ou des imprécisions dans nos documents, ou si vous pouvez les améliorer :
1.  Suivez les étapes de "Contribuer du Code" ci-dessus.
2.  Les fichiers de documentation se trouvent principalement dans le dossier `docs/`.
3.  Assurez-vous que vos modifications sont claires, concises et faciles à comprendre.

## 3. Configuration de Votre Environnement de Développement

Pour commencer à développer sur NexusAI-Core :

1.  **Prérequis :**
    * Python 3.x
    * Node.js et npm/yarn (pour les composants frontend et certains outils)
    * Un environnement de développement C/C++ (pour les parties embarquées, ex: GCC, make, PlatformIO ou un IDE comme VS Code avec les extensions appropriées).
    * Git

2.  **Clonez le Dépôt :**
    ```bash
    git clone [https://github.com/NexusOccitech/NexusAI-Core.git](https://github.com/NexusOccitech/NexusAI-Core.git)
    cd NexusAI-Core
    ```

3.  **Configuration Python :**
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate  # Sur Windows: .venv\Scripts\activate
    pip install -r requirements.txt # Si un requirements.txt existe, sinon installer les dépendances manuellement
    ```

4.  **Configuration Node.js (si applicable) :**
    ```bash
    npm install # ou yarn install
    ```

5.  **Configuration Embarquée (si vous travaillez sur cette partie) :**
    * Installez votre chaîne d'outils (toolchain) C/C++ pour les microcontrôleurs ciblés.
    * Consultez le dossier `src/embedded/` (ou un nom similaire) pour des instructions spécifiques.

## 4. Processus de Soumission (Pull Request)

Toutes les Pull Requests seront examinées par les mainteneurs du projet. Nous nous efforçons de répondre rapidement. Les révisions peuvent inclure :
* Demandes de modifications mineures ou majeures.
* Suggestions d'amélioration de la qualité du code ou des tests.
* Discussions sur l'alignement avec la vision du projet.

Une fois approuvée, votre contribution sera fusionnée dans la branche `main`.

## 5. Questions ?

Si vous avez des questions, n'hésitez pas à :
* Ouvrir une [Issue](https://github.com/NexusOccitech/NexusAI-Core/issues) avec votre question (utilisez le modèle "Question" si disponible).
* Nous contacter via les informations disponibles sur notre [site web](./assets/presentations/NexusWebsite5.html).

Merci pour votre intérêt et votre contribution à Nexus AI !
