# 🚀 PatateNova

**PatateNova** est un mini-jeu mobile Android dans lequel le joueur pilote un vaisseau spatial à travers un parcours semé d'embûches. Son objectif : atteindre la ligne d'arrivée sans subir trop de dégâts !

Le jeu exploite les capteurs du smartphone pour proposer une expérience interactive basée sur le tactile, les mouvements et la voix.

## 🎮 Concept du jeu

Le joueur doit guider son vaisseau d'un point A à un point B en évitant différents obstacles qui apparaissent sur son trajet.

Il doit gérer sa progression, réagir rapidement aux dangers et préserver l'intégrité de son vaisseau. Chaque obstacle évité ou subi influence le score final.

## 🕹️ Gameplay

Une partie se déroule en trois grandes étapes :

### 1. Avant la partie
- Saisir son pseudo.
- Démarrer une nouvelle partie.
- Configurer les options (son et vibration).

### 2. Pendant la partie
- **Accélérer :** maintenir ou appuyer sur le bouton « Avancer » pour augmenter la vitesse du vaisseau.
- **Éviter les astéroïdes :** secouer le smartphone pour esquiver les obstacles.
- **Éviter les trous noirs :** crier dans le microphone pour échapper à leur attraction.
- **Suivre sa progression :** consulter la barre d'avancement et le score en temps réel.
- **Gérer la partie :** mettre en pause, reprendre, redémarrer ou abandonner.

### 3. Après la partie
- Consulter son score final.
- Découvrir son classement.
- Consulter le nombre d'obstacles évités.
- Rejouer ou retourner à l'écran d'accueil.

## 📱 Interactions et capteurs

Le gameplay repose sur l'utilisation de plusieurs fonctionnalités du smartphone :

| Interaction | Fonction |
|---|---|
| Écran tactile | Accélérer le vaisseau |
| Accéléromètre | Détecter les secousses pour éviter les astéroïdes |
| Microphone | Détecter les cris pour éviter les trous noirs |
| Vibreur | Signaler les dégâts subis par le vaisseau |

### Gestion des capteurs

Une attention particulière est portée à la fiabilité des interactions :

- **Accéléromètre :** utilisation d'un seuil d'intensité et d'une durée minimale pour éviter les déclenchements involontaires.
- **Microphone :** calibrage du bruit ambiant au début de la partie, puis détection sonore uniquement lors des séquences impliquant un trou noir.
- **Confidentialité :** aucun enregistrement audio n'est conservé.

## 🎨 Principes de conception

Le design de l'application repose sur plusieurs principes d'ergonomie et d'interaction homme-machine :

- **Simplicité tactile :** un unique bouton de grande taille, positionné en bas de l'écran, permet de contrôler l'accélération.
- **Découvrabilité des gestes :** des alertes visuelles indiquent au joueur les actions à effectuer face aux obstacles.
- **Utilisation à une main :** les actions principales sont accessibles sans avoir à changer la prise en main du téléphone.
- **Saisie limitée :** seul le pseudo est demandé avant le lancement d'une partie.
- **Feedback utilisateur :** le score, les dégâts et les vibrations permettent au joueur de comprendre les conséquences de ses actions.

## 🛠️ Technologies

- **Plateforme :** Android
- **Langage :** Java
- **Environnement de développement :** Android Studio
- **Capteurs :** accéléromètre et microphone
- **Fonctionnalités natives :** écran tactile et moteur de vibration

## ⚙️ Installation et lancement

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/VOTRE-PSEUDO/SpaceEscape.git
   ```
2. Ouvrir le projet dans Android Studio.
3. Attendre la synchronisation Gradle.
4. Connecter un smartphone Android ou démarrer un émulateur.
5. Lancer l'application depuis Android Studio.

**Remarque :** l'utilisation d'un véritable smartphone est recommandée pour profiter pleinement des interactions avec l'accéléromètre, le microphone et le vibreur.

## 👥 Équipe projet

Projet universitaire réalisé en groupe dans le cadre du Master 2 IHM.
Groupe: Veronika Radionova, Lilian Refour.
