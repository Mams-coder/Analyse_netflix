# Étude Analytique et Prédictive du Catalogue Netflix

Ce projet est une immersion dans les données de la plateforme Netflix. À travers une approche de Data Science, il explore comment le contenu a évolué au fil des années et comment une intelligence artificielle peut apprendre à distinguer les formats de production.

## Stack Technique
Pour mener à bien cette étude, les technologies suivantes ont été mobilisées :
* **Python :** Langage principal utilisé pour le traitement logique.
* **Pandas :** Manipulation et nettoyage de structures de données complexes.
* **Matplotlib & Seaborn :** Conception de visualisations statistiques et d'un dashboard de synthèse.
* **Scikit-Learn :** Implémentation de l'algorithme de Machine Learning et évaluation des performances.

## Problématique et Démarche
L'enjeu de ce projet était de répondre à deux questions principales :
1. **Quelles sont les grandes tendances du catalogue Netflix ?** (Origines géographiques, formats dominants, pics de production).
2. **Peut-on automatiser la classification du contenu ?** En utilisant uniquement des données numériques comme la durée, est-il possible pour un algorithme de prédire si une œuvre est un film ou une série ?

## Analyse Exploratoire des Données (EDA)
L'étude a permis de mettre en lumière plusieurs faits marquants :
* **Répartition des formats :** Le catalogue reste majoritairement cinématographique, bien que l'offre de séries TV soit en croissance constante.
* **Dynamique Temporelle :** Une accélération majeure de la mise en ligne de contenus a été identifiée, marquant le passage de Netflix d'un distributeur à un producteur massif.
* **Géographie de la Production :** L'analyse confirme la prédominance des États-Unis, tout en révélant l'importance cruciale de l'Inde et du Royaume-Uni.

## Modélisation par Intelligence Artificielle
Le projet utilise un modèle de **Machine Learning (Arbre de Décision)** pour comprendre la structure des données.



### Le processus d'apprentissage :
* **Ingénierie des données :** Transformation des étiquettes textuelles en données numériques exploitables par l'IA.
* **Identification de règles :** L'IA a réussi à identifier seule le "seuil critique" qui sépare une saison d'une durée de film.
* **Performance :** Le modèle a démontré une capacité de prédiction quasi-parfaite, validant ainsi la corrélation directe entre la durée d'une œuvre et son format.

## Visualisations Finales
Le projet se conclut par la génération d'un tableau de bord synthétique regroupant les indicateurs clés de performance (KPIs) du catalogue, offrant une vision panoramique de l'offre Netflix à un instant T.