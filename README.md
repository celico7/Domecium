# Jeu sur Unreal Engine
# Domecium

> *Première partie du jeu (à la troisime personne) grâce à la formation de Gamedev Teacher sur Youtube*

---

## Sommaire
- [🎮 Résumé du jeu](#-résumé-du-jeu)
- [🧠 Compétences développées](#-compétences-développées)
- [⚙️ Fonctionnalités principales](#️-fonctionnalités-principales)
- [🧩 Aperçu du code et Blueprints](#-aperçu-du-code-et-blueprints)
- [🖼️ Illustrations du jeu](#️-illustrations-du-jeu)
- [📦 Technologies utilisées](#-technologies-utilisées)
- [🎥 Vidéo gameplay](#-vidéo-du-gameplay-à-la-troisième-personne)
---

## 🎮 Résumé du jeu

**Domecium** est un **shooter narratif** développé sous **Unreal Engine 5**, mêlant **vue à la troisième personne** et **séquences immersives à la première personne**.


Le joueur débute dans un environnement sombre et inquiétant, équipé d'une arme et d’une lampe torche pour se repérer.  
Progressivement, il découvre un complexe scientifique composé de **zones futuristes** et de **laboratoires anciens**, où il doit :
- Explorer pour trouver des **codes d’accès** et **débloquer des salles** ;
- Survivre face à des **ennemis qui apparaissent dynamiquement** ;
- Dans la salle finale, affronter des **monstres** dans un dôme.

L’objectif : **s’échapper du complexe** en surmontant les pièges, énigmes et vagues d'ennemies.

---

## 🧠 Compétences développées

Au cours du développement du projet, plusieurs domaines d’Unreal Engine ont été explorés :

### 🔹 Programmation & Blueprints
- Création de **Blueprints modulaires** (ennemis, projectiles, IA, portes, triggers)
- Utilisation des **Event Graphs**, **fonctions personnalisées** et **variables dynamiques**
- Gestion des **interactions joueur / environnement**

### 🔹 Gameplay & IA
- Systèmes de **détection et poursuite ennemie**
- **Spawner** dynamique gérant les vagues d’ennemis
- Gestion du **Health System** (ennemis et joueur)

### 🔹 Interface & UX
- Création de **HUD dynamiques**
- **Système d’inventaire** et **affichage des codes d’accès**
- **Menus interactifs** (pause, mort, victoire, etc.)

### 🔹 Level Design & Ambiance
- Conception d’environnements sombres et immersifs
- Mise en scène d’un **passage de la 3ᵉ à la 1ʳᵉ personne**
- Travail sur la **lumière, brouillard, post-processing, les textures et matériaux**

### 🔹 VFX & Audio
- Implémentation de **particules (Cascade / Niagara)**
- Gestion des **matériaux dynamiques** et **effets lumineux**
- Ajout d’**ambiances sonores** et **SFX d’armes / ennemis**

---

## ⚙️ Fonctionnalités principales

- Vue à la **troisième personne** + transition vers la **première personne**
- Une **arme** pour se défendre contre les ennemis
- **Lampe torche dynamique** dans un environnement sombre
- **IA d’ennemis** avec détection et attaque
- **Système de tourelle automatisée** qui détecte le joueur comme cible
- **Système de codes d’accès** et de portes verrouillées
- **Niveaux multiples** : laboratoire ancien → zones futuristes → dôme naturel final
- **Effets de particules**, impacts de tirs, destruction d’objets

---

## 🧩 Aperçu du code et Blueprints

Voici quelques exemples visuels de logique Blueprint utilisée dans le projet :

### Exemple : Système de l'ennemy
🔗 [Voir le Blueprint sur blueprintue.com](https://blueprintue.com/blueprint/lw1-h4yw/)
> Gestion de l'ia des ennemis.

### Exemple : Système de spawn
🔗 [Voir le Blueprint sur blueprintue.com](https://blueprintue.com/blueprint/k0z3d6dg/)
> Apparition progressive d’ennemis.

### Exemple : Système de tourelle automatisée
🔗 [Voir le Blueprint sur blueprintue.com](https://blueprintue.com/blueprint/kbg9lw80/)
> Blueprint gérant la détection du joueur, rotation automatique, tir de projectiles et mise à jour du système de santé.

---

## 🖼️ Illustrations du jeu

### Exploration à la lampe torche
![Dark Lab Environment](images/torch.png)

### Première salle
![Third Person Gameplay](images/first_room.png)

### La salle finale : le dôme
![Final Dome](images/dome_battle.png)

---

## 📦 Technologies utilisées
- Unreal Engine 5
- Blueprint Visual Scripting
- Niagara / Cascade
- Quixel Megascans

---

## 🎥 Vidéo du gameplay à la troisième personne

[![Game](https://img.youtube.com/vi/TJ2mi7FuY3A/0.jpg)](https://www.youtube.com/watch?v=TJ2mi7FuY3A)
