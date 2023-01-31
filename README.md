# Classifier automatiquement des biens de consommation
## Description
Projet OpenClassrooms pour une première étude de faisabilité d'un moteur de classification des biens 
de consommations à partir de leur description et de leur image.
* Les données sont disponibles sur 
[ce lien](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip)

* Le notebook **ElHouri_Marwa_1_notebook_082022** contient le prétraitement de texte et d'images suivant plusieurs méthodes.
* Le fichier pdf **ElHouri_Marwa_2_presentation_08_2022** contient la présentation du projet.
## Notions traitées
### Traitement du texte:
* Préparation du texte, nettoyage et tokenisation
* Lemmatisation et/ou stemming
* Représentation des mots en utilisant **wordcloud**
* Traitement de texte (bag of words, TF-IDF, word2vec, BERT, USE)
### Traitement d'images
* Prétraitement des images (GaussianBlur, Histogram equalization,...)
* Extraction des feature images par SIFT
* extraction des features images par Transfer learning
### Validation des résultats
* Reduction de dimension (PCA, TSNE)
* Clustering (Kmeans)
* Représentation graphiques (catégories réelles vs clusters), 
* Matrice de confusions, rapport de classification
