## Objectif

Notre équipe a développé un algorithme de Market Basket Analysis (MBA) afin de révéler les motifs sous-jacents dans des ensembles de données volumineux. Nous appliquons maintenant cet algorithme au domaine médical pour identifier les symptômes qui apparaissent fréquemment ensemble. Cette approche nous permettra d’anticiper certaines affections et de proposer des traitements préventifs adaptés.

## Technologie utilisée

Pour ce projet, nous utilisons PySpark, une interface Python pour Apache Spark, afin de tirer parti du paradigme de parallélisation avec MapReduce. Nous testons et développons notre algorithme sur Google Colab en utilisant un extrait du jeu de données, puis nous le déployons sur Google Cloud Platform (GCP) pour analyser l’ensemble des données complètes avec la puissance de calcul nécessaire.

## Algorithme utilisé

Nous avons basé notre implémentation sur l’algorithme d’analyse du panier de marché présenté par Jongwook Woo et Yuhang Xu (2012). Ce modèle nous permet d’extraire des règles d’association à partir de grandes quantités de données, révélant ainsi des tendances et corrélations intéressantes. L’image workflow.pdf illustre le processus global et les différentes étapes d’analyse que nous avons mises en place.

## Environnement du notebook

Nos développements s’exécutent dans un notebook utilisant Java 17, garantissant ainsi la compatibilité avec Apache Spark et PySpark. Cet environnement nous permet d’optimiser l’exécution de notre algorithme sur des clusters distribués.

## Application au domaine médical

Nous travaillons avec le dataset [*VAERS*](https://vaers.hhs.gov/index.html), une base de données agrégée et normalisée issue du programme états-unien de surveillance Vaccine Adverse Event Reporting System, couvrant une période de 1990 à 2024. 
