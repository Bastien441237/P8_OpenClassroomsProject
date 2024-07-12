# 🍏 Traitement des Données dans un Environnement Big Data sur le Cloud

Bienvenue dans le repository du projet **Traitement des Données dans un Environnement Big Data sur le Cloud**. Ce projet fait partie de la formation OpenClassrooms en Data Science et a été réalisé en collaboration avec CentraleSupélec. 

## 📚 Contexte du Projet

Vous êtes Data Scientist dans une start-up de l'AgriTech, nommée "Fruits!", qui propose des solutions innovantes pour la récolte des fruits. La mission principale est de développer une architecture Big Data sur le cloud pour traiter et analyser des images de fruits afin de sensibiliser le public à la biodiversité.

## 🎯 Objectifs du Projet

1. **Mettre en place une architecture Big Data sur AWS EMR pour traiter les images de fruits.**
2. **Développer des scripts PySpark pour le preprocessing des données et la réduction de dimension avec ACP.**
3. **Démontrer la mise en place d'une instance EMR opérationnelle et expliquer les scripts PySpark utilisés.**
4. **Assurer la conformité au RGPD en utilisant des serveurs situés en Europe.**
5. **Optimiser les coûts en ne maintenant l'instance EMR opérationnelle que pour les tests et les démonstrations.**

## 📦 Livrables

1. **Un notebook sur le cloud** contenant les scripts en PySpark exécutables (le preprocessing et une étape de réduction de dimension de type PCA) à exécuter sur une machine virtuelle Linux afin de se rapprocher de l'environnement de l'EMR.
2. **Les images du jeu de données initial** ainsi que la sortie de la réduction de dimension disponible dans un espace de stockage sur le cloud.
3. **Un support de présentation** pour la soutenance, présentant :
   - Les différentes briques d'architecture choisies sur le cloud et leur rôle.
   - La démarche de mise en oeuvre de l’environnement - EMR - Big Data.
   - Les étapes de la chaîne de traitement PySpark.

## 📂 Structure du Repository

```plaintext
├── Moreno_Bastien_2_images_052024/
│   ├── dossiers des images de fruits pour le test du script/   # Contient les images brutes de 15 des fruits du fruits-360_dataset
│   ├── export.csv/                                             # Contient les données traitées et réduites
├── fruits-360_dataset/fruits-360/
│   ├── dossiers du dataset de base/                            # Contient les images de fruits brutes disponibles sur https://www.kaggle.com/datasets/moltean/fruits
├── Moreno_Bastien_1_notebook_052024.ipynb                      # Notebook pour le preprocessing des données et la réduction de dimension PCA
├── Moreno_Bastien_3_presentation_052024.pdf                    # Support de présentation pour la soutenance
├── README.md                                                   # Ce fichier
```

## 👨‍💻 Auteur
Bastien Moreno - Data Scientist et passionné par l'analyse de données et le développement de modèles intelligents.