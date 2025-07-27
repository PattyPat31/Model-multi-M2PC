# Modelisation multi echelle en physique et en chimie
# 🧠 Détection automatique d’anomalies vasculaires sur IRM cérébrales

## 🎯 Objectif du projet

Ce projet interdisciplinaire vise à développer un outil simple de détection ou de segmentation d’anomalies vasculaires visibles sur IRM cérébrales, en particulier des **thromboses veineuses**. L’objectif est de combiner des outils de traitement d’image, d’apprentissage automatique, et des connaissances biomédicales.

Le projet est réalisé par une équipe d’étudiants issus de différents masters, avec une répartition collaborative des tâches.

---

## 📁 Organisation du dépôt


---

## 🧪 Données IRM utilisées

Nous utilisons des IRM publiques, téléchargeables librement. Ces données sont strictement anonymisées.

### Datasets recommandés :
- [OpenNeuro.org](https://openneuro.org): IRM cérébrales en format BIDS, nombreuses études disponibles.
- [ISLES 2022 dataset](https://www.isles-challenge.org/ISLES2022): IRM multimodales avec lésions annotées (AVC), utiles pour la segmentation.
- [TCIA - The Cancer Imaging Archive](https://www.cancerimagingarchive.net): DICOM d’IRM cliniques avec certaines annotations.

> **NB** : Les jeux ne contiennent pas forcément de thromboses veineuses, mais permettent de développer un pipeline générique de détection d’anomalies.

---

## ⚙️ Installation & Environnement

### 1. Cloner ce dépôt :
```bash
git clone https://github.com/votre-utilisateur/nom-du-depot.git
cd nom-du-depot
