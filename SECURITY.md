# Politique de Sécurité de NexusAI-Core

Chez Nexus AI, la sécurité est une priorité absolue. Nous nous engageons à protéger nos utilisateurs et l'intégrité de notre écosystème d'intelligence ambiante sécurisée. Nous apprécions les efforts de la communauté des chercheurs en sécurité et nous nous engageons à travailler avec eux pour résoudre rapidement et efficacement toute vulnérabilité signalée.

## 1. Comment Signaler une Vulnérabilité ?

Si vous découvrez une vulnérabilité de sécurité dans NexusAI-Core ou dans l'un de nos composants associés, nous vous demandons de la signaler de manière responsable et confidentielle.

**Veuillez NE PAS ouvrir une issue publique sur GitHub pour les vulnérabilités.**

Pour signaler une vulnérabilité :

1.  **Contactez-nous directement par email :**
    * Envoyez un email détaillé à : `security@nexus-ai.com` (Utilisez une adresse email dédiée à la sécurité de votre organisation).
    * **Si vous disposez d'une clé PGP/GPG, veuillez l'utiliser pour chiffrer votre message** afin de garantir la confidentialité des informations sensibles. Vous pouvez trouver notre clé publique PGP ici (si disponible, sinon mentionnez que nous pouvons en fournir une sur demande).

2.  **Informations à Inclure :**
    * **Description de la Vulnérabilité :** Expliquez clairement la nature de la vulnérabilité.
    * **Étapes de Reproduction :** Fournissez des étapes détaillées pour reproduire la vulnérabilité.
    * **Impact Potentiel :** Décrivez les conséquences potentielles de l'exploitation de cette vulnérabilité.
    * **Versions Affectées :** Spécifiez les versions de NexusAI-Core (ou du composant) qui sont affectées.
    * **Environnement :** Détails sur l'environnement de test (OS, configuration, dépendances).
    * **Preuve de Concept (PoC) :** Si possible, incluez un PoC minimal qui démontre la vulnérabilité sans causer de dommages.

## 2. Notre Processus de Divulgation Responsable

Une fois qu'une vulnérabilité est signalée, voici comment nous nous engageons à la traiter :

1.  **Accusé de Réception :** Nous accuserons réception de votre rapport dans les **2 jours ouvrables**.
2.  **Investigation :** Notre équipe de sécurité examinera la vulnérabilité et validera sa portée. Nous pourrions vous contacter pour obtenir des informations complémentaires.
3.  **Résolution :** Nous travaillerons à développer un correctif dans les plus brefs délais. Le temps de résolution dépendra de la complexité et de la gravité de la vulnérabilité.
4.  **Notification :** Nous vous tiendrons informé de l'avancement de la résolution.
5.  **Divulgation Publique :** Une fois le correctif déployé et disponible, nous publierons une notification publique (via une GitHub Security Advisory, un changelog ou un blog post) détaillant la vulnérabilité et sa résolution. Nous vous créditerons pour votre découverte, sauf si vous préférez rester anonyme.

## 3. Exclusion de Portée

Les domaines suivants sont généralement hors de portée de notre programme de divulgation de vulnérabilités, sauf s'ils peuvent être liés à une vulnérabilité plus profonde :
* Problèmes de configuration générale des outils tiers ou services non gérés par Nexus AI.
* Attaques par déni de service (DoS) sans démonstration d'une vulnérabilité sous-jacente.
* Problèmes liés à la politique de mot de passe ou d'authentification sans preuve d'exploit.
* Phishing ou ingénierie sociale.
* Vulnérabilités sur des services tiers non directement liés à NexusAI-Core.

## 4. Notre Engagement

Nous nous engageons à :
* Traiter tous les rapports de vulnérabilités avec la plus haute priorité et professionnalisme.
* Ne pas intenter de poursuites judiciaires contre les chercheurs en sécurité qui signalent les vulnérabilités de bonne foi et en suivant cette politique.
* Fournir des crédits et de la reconnaissance pour les contributions significatives à la sécurité.

Merci de nous aider à rendre Nexus AI plus sûr pour tous !
