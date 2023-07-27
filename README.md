# ChatGPT-SentimentAnalysis
@Proflemay's SCI1402 Projet en science des données

## Introduction
S’il y a un phénomène récent qui retient l’attention dans les médias, les réseaux sociaux et la sphère professionnelle, c’est bien ChatGPT. C’est un agent conversationnel développé par la société d’intelligence artificielle OpenAI. Il est basé sur les large language models (LLM). Il s’agit du service web qui a connu la plus grande croissance en termes du nombre d’utilisateurs, atteignant 100 millions d’utilisateurs en 2 mois seulement (Radio-Canada, 2023). Cette fulgurante croissance a dépassé celle d’autres phénomènes populaires comme Facebook, TikTok, Instagram et autres.

Mon projet de fin d’études visait à comprendre les émotions ressenties par les internautes envers cet agent, exprimés via le réseaux social Twitter. L’analyse s'est effecutée avec des outils des sciences des données, soit les analyses de sentiments. L'analyse des sentiments permet de comprendre l'opinion générale, les attitudes et les émotions des internautes envers un phénomène, comme une application ou un service. Dans ce projet, nous avons utilisé une banque de données de centaines de milliers de tweets obtenue sur Kaggle et extrait des informations sur les sentiments ressentis.

## Définition des objectifs
Il s’avèrait intéressant, voire essentiel de comprendre comment les internautes (utilisateurs et non-utilisateurs) perçoivent ChatGPT et comment ces perceptions évoluent avec le temps. L'analyse visait à déterminer d’abord la valence des émotions des internautes (positive, négative ou neutre), de détailler les émotions envers cet outil et ensuite comment ces sentiments ont évolué avec le temps.

Plus spécifiquement, les objectifs de ce projet sont de :
-	déterminer si les internautes expriment des opinions positives, négatives ou neutres envers ChatGPT ;
-	déterminer les émotions sous-jacentes, telles que la joie, le plaisir, la peur ou l’anxiété, basé sur le modèle des 8 émotions primaires de Plutchik (Plutchik 2023);
-	déterminer si les émotions ont évolué au cours du temps, au fur et à mesure que ChatGPT était connu du public ;
-	présenter les résultats obtenus à l’aide de visualisations claires, afin de faciliter l'interprétation et les conclusions.

## Présentation des outils
Des techniques d’analyses de texte ont été utilisées où les éléments textuels (ici les tweets) ont été décomposés en tokens, puis passés dans les librairies spécialisées d’analyses de sentiments et d’émotions.

Le principal outil est le logiciel de statistiques R, avec les librairies tidytext, qdap, bing, nrc et ggplot pour les graphiques. 

Un notebook Jupyter dans Visual Studio Code a été développé afin de travailler de manière itérative.

Une version en français et une version en anglaise sont disponibles ici.

## Étapes d'analyses
- Installation des outils - libraires spécialisées de R
- Importation des données
- Comprendre le jeu de données
- Traitement préliminaires des données
- Analyse des données
    * Analyse de la polarité
    * Analyse du contenu des tweets
    * Analyse des sentiments avec le lexique Bing
    * Analyse des émotions avec le modèle de Plutchik
    * Analyses de l'évolution de la polarité
    * Analyses de l'évolution des sentiments


## Références
Ansari, K. (2023). Comprehensive Analysis of 500K Tweets on ChatGPT. https://www.kaggle.com/code/khalidryder777/comprehensive-analysis-of-500k-tweets-on- chatgpt#6.-Data-Preprocessing
Ansari, K. (2023). 500k ChatGPT-related Tweets Jan-Mar 2023 https://www.kaggle.com/datasets/khalidryder777/500k-chatgpt-tweets-jan-mar-2023
Chang, W. Multiple graphs on one page (ggplot2). Cookbook for R. Retrieved 2023-06-05 from http://www.cookbook-r.com/Graphs/Multiple_graphs_on_one_page_(ggplot2)/
Khalid, I. A. (2020). Text Mining with R: Gathering and Cleaning Data. Retrieved 2023-05-24 from https://towardsdatascience.com/text-mining-with-r-gathering-and-cleaning-data- 8f8b0d65e67c
Wikipedia. (2023). Robert Plutchik. Wikipedia. Retrieved 2023-06-06 from http://fr.wikipedia.org/w/index.php?title=Robert_Plutchik&oldid=203320799
