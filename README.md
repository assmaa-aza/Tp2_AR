# Projet AR avec Unity + Vuforia + Interaction IA

## Description

Ce projet est une application de **Réalité Augmentée (AR)** développée avec **Unity et Vuforia**.  
Elle permet de détecter une image réelle (Image Target) et d’afficher un modèle 3D interactif dessus.

Le projet intègre également une **fonctionnalité d’intelligence artificielle simulée**, permettant de générer des réponses dynamiques en fonction des interactions de l’utilisateur.

---

## Fonctionnalités

- Détection d’un Image Target (marker)
- Affichage d’un objet 3D sur le marker
- Interaction utilisateur (clic / tap)
- Simulation d’intelligence artificielle (réponses dynamiques)
- Texte interactif qui change selon les actions de l’utilisateur
- Suivi du marker en temps réel (tracking AR)

---

## Technologies utilisées

- Unity Engine
- Vuforia Engine (AR SDK)
- C# (scripts)
- TextMeshPro (affichage texte)

---

## Structure du projet
TP2_AR
├── ARCamera
├── ImageTarget
│ ├── Foxy (modèle 3D)
│ ├── Text (TextMeshPro)
├── AI_Manager (logique IA)
├── Scripts
│ ├── FollowMouse.cs
│ ├── TapInteraction1.cs
│ ├── AITextManager.cs

----

## Fonctionnement

1. L’application détecte une image cible (marker)
2. Un modèle 3D est affiché sur cette image
3. L’utilisateur peut interagir avec l’objet (clic)
4. Une réponse “IA” est générée et affichée dynamiquement
5. Le modèle peut suivre le mouvement de la souris (optionnel)

---

## Fonctionnalité IA

L’IA est simulée via un système de réponses prédéfinies qui changent aléatoirement à chaque interaction utilisateur.

Exemple :
- "Hello, I'm Foxy 🦊"
- "Nice to meet you!"
- "Let's rotate!"
- "You found me!"

---

## Utilisation

1. Lancer le projet dans Unity
2. Activer la caméra AR (Vuforia)
3. Placer le marker devant la caméra
4. Interagir avec le modèle 3D

---

## Prérequis

- Unity installé
- Vuforia Engine configuré
- Webcam ou smartphone pour tester l’AR

---

## Objectif du projet

Ce projet a été réalisé dans le cadre d’un TP visant à :
- Comprendre la réalité augmentée
- Utiliser la détection d’images
- Ajouter des interactions utilisateur
- Intégrer une logique d’intelligence artificielle simple
