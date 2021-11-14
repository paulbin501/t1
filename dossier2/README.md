ModOAP_Classification_automatique_de_textes

Ce script permet la classification automatique de blocs de texte issus de documents Gallica, à partir de modèles de classification préalablement entraînés.

Les modèles entraînés doivent être importés : ils peuvent être obtenus via le script ModOAP - Classification automatique de textes (Entrainement)

Trois types de classifications possibles :

   1 Classification binaire : associer un texte à une étiquette ou 0 (une seule étiquette possible)
   2 Classification multiclass : associer un texte à une étiquette parmi un jeu d'étiquettes
   3 Classification multilabel : associer un texte à une ou plusieurs étiquettes parmi un jeu d'étiquettes

Le script implémente la bibliothèque Simple Transformers : https://simpletransformers.ai/
