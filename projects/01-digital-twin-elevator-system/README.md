# 🏭 Jumeau Numérique - Système d'Ascenseurs Industriels

> **Simulation complète d'un système de manutention multi-niveaux avec alternance automatique de voies**

## 📋 Vue d'ensemble

Ce projet implémente un **jumeau numérique** d'un système industriel de convoyage multi-niveaux composé de :
- **2 ascenseurs** (gauche et droit) à 3 niveaux (0, 1, 2)
- **5 convoyeurs** (entrée, sortie, intermédiaires 0/1/2)
- **Alternance automatique** des niveaux pour optimiser le flux
- **Gestion de sécurité** complète (arrêt d'urgence, modes auto/manuel)

### Contexte industriel
Système typique de distribution automatisée dans :
- Entrepôts logistiques (tri colis multi-étages)
- Industrie automobile (distribution pièces vers lignes d'assemblage)
- Agroalimentaire (palettisation multi-niveaux)

## 🎯 Objectifs techniques

✅ **Automatisation complète** : Machine à états robuste avec gestion des transitions  
✅ **Optimisation flux** : Alternance intelligente niveau 1 ↔ niveau 2  
✅ **Sécurité industrielle** : Arrêt d'urgence, retour sécurisé, fail-safe  
✅ **Synchronisation** : Coordination 2 ascenseurs + 5 convoyeurs  
✅ **Simulation réaliste** : Jumeau virtuel avec Factory I/O (OPC UA)

## 🛠️ Technologies utilisées

| Composant | Technologie | Version |
|-----------|------------|---------|
| **Automate** | Siemens S7-1500 (simulé PLCSim Advanced) | V17 |
| **Programmation** | SCL (Structured Control Language) + Ladder | - |
| **Simulation 3D** | Factory I/O | 2.5+ |
| **Communication** | OPC UA | - |
| **Environnement** | TIA Portal | V17/V18 |


## 🚀 Installation & Exécution

### Prérequis
- **TIA Portal V17** ou supérieur
- **Factory I/O 2.5+** (licence éducation acceptée)
- **PLCSim Advanced** (ou automate S7-1500 réel)

## 🎬 Démonstration vidéo

[Démo YouTube] https://youtu.be/Jlsbx5ovsZU

## 👤 Auteur

**DIA Mor Talla** - Étudiant Ingénieur GII (Polytech Marseille)  
📧 Contact : mor-talla.DIA@etu.univ-amu.fr
💼 LinkedIn : https://www.linkedin.com/in/mor-talla-dia-505662206/

