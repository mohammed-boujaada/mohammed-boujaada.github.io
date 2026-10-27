---
title: "OCR sur image fortement dégradée"
excerpt: "OpenCV, PyTesseract et Tesseract OCR.<br/>[Code sur GitHub](https://github.com/mohammed-boujaada/ocr_image_degradee)"
collection: portfolio
order: 9
---

Pipeline expérimental de reconnaissance d'un mot isolé dans une image fortement bruitée, avec une chaîne de prétraitement OpenCV et le moteur Tesseract OCR.

- Conversion en niveaux de gris et réduction du bruit par filtre médian.
- Binarisation automatique par seuillage d'Otsu, inversion et opérations morphologiques.
- Agrandissement de l'image, ajout d'une bordure et configuration de Tesseract avec une liste blanche de lettres majuscules et de chiffres.
- Visualisation des étapes de traitement et du résultat détecté dans un notebook Jupyter.

Le pipeline a produit la sortie brute `EXAMB` sur l'image étudiée. Les paramètres sont calibrés pour cette image et constituent une base pour expérimenter la gestion des confusions de caractères et l'évaluation quantitative de l'OCR.

[Code sur GitHub](https://github.com/mohammed-boujaada/ocr_image_degradee)
