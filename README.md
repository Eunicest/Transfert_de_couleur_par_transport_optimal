# 🎨 Transfert de Couleur par Transport Optimal

## 🎯 Résultats (Avant / Après)
L'algorithme capture la palette de couleurs de l'image "Cible" et l'applique à la géométrie de l'image "Source".

| Image Source | Image Cible (Palette) | Résultat (Transfert) |
| :---: | :---: | :---: |
| ![Source](Images\parcfloral.png) | ![Cible](Images\parrot.png) | **![Résultat](Images\3.png)** |

*(Remplacez les chemins ci-dessus par les liens vers vos propres images pour illustrer le résultat !)*

---

## 📝 Contexte et Objectif
Ce projet d'apprentissage a été réalisé pour explorer le domaine du traitement d'images en implémentant une méthode algorithmique de "Transfert de couleur". 
L'objectif est d'extraire la distribution des couleurs d'une image de référence et de l'appliquer sur le contenu structurel d'une autre image, tout en conservant les détails de cette dernière.

Pour y parvenir, ce travail s'appuie sur les concepts et le cadre mathématique du **Transport Optimal**.

### 🛠️ Outils et Technologies
* **Langage & Environnement :** Python, Jupyter Notebook
* **Domaines d'application :** Traitement d'images (Computer Vision), Mathématiques appliquées
* **Bibliothèques principales :** `NumPy` (calcul matriciel), `OpenCV` (traitement d'images), `Matplotlib` (visualisations 2D et 3D)

### 📂 Contenu du dépôt
* 📓 `transfert_couleur_transport_optimal.ipynb` : Le notebook Jupyter principal documentant l'implémentation de l'algorithme, les étapes de traitement (extraction des canaux RGB) et les visualisations des résultats.

> 💡 **Note :** Le notebook contient les sorties (outputs) pré-calculées pour vous permettre de visualiser directement le fonctionnement de l'algorithme sans avoir à exécuter le code.

---
<br>

<details>
<summary>🇬🇧 <b>English version (Click to expand)</b></summary>

## 🎯 Results (Before / After)
The algorithm captures the color palette from the "Target" image and applies it to the geometry of the "Source" image.

| Source Image | Target Image (Palette) | Result (Transfer) |
| :---: | :---: | :---: |
| ![Source](Images\parcfloral.png) | ![Target](Images\parrot.png) | **![Result](Images\3.png)** |

---

## 📝 Context and Objective
This learning project was developed to explore the field of image processing by implementing a "Color Transfer" algorithm. 
The goal is to capture the color distribution of a reference image and apply it to the structural content of another image, while preserving the latter's details and geometry.

To achieve this, the work relies on the concepts and mathematical framework of **Optimal Transport**.

### 🛠️ Tools & Technologies
* **Language & Environment:** Python, Jupyter Notebook
* **Application Domains:** Image Processing (Computer Vision), Applied Mathematics
* **Core Libraries:** `NumPy` (matrix computation), `OpenCV` (image processing), `Matplotlib` (2D and 3D visualizations)

### 📂 Repository Content
* 📓 `transfert_couleur_transport_optimal.ipynb`: The main Jupyter notebook documenting the algorithm implementation, processing steps (RGB channel extraction), and result visualizations.
</details>