# Analyse des Dépenses Gouvernementales - Projet Power BI

## Description du Projet
Ce projet vise à analyser les dépenses effectuées par le gouvernement à travers une étude détaillée des transactions issues du **Government Procurement Card Spend** de novembre 2013. En utilisant **Power BI**, j'ai créé des tableaux de bord interactifs permettant d'explorer les données sous plusieurs angles.

Le but de cette analyse est de fournir des insights visuels et accessibles sur les dépenses gouvernementales, mettant en lumière les catégories d'achats les plus fréquentes, les fournisseurs majeurs, et les tendances en matière de dépenses.

## Objectifs du Projet
- Explorer les données des dépenses gouvernementales.
- Créer des visualisations interactives pour faciliter la compréhension des flux financiers.
- Identifier les fournisseurs récurrents et les catégories d'achats.
- Analyser les tendances dans les dépenses gouvernementales sur une période donnée.

## Étapes du Projet
1. **Nettoyage et préparation des données** : Traitement des données brutes pour corriger les erreurs et incohérences.

   -La colonne date était sous le format MM/DD/YYYY et je devais d'abord la transformer sous le format DD/MM/YYYY en scindant le colonne en 3 avec un délimiteur et en faisant une nouvelle colonne
  
   <img src="https://github.com/user-attachments/assets/e8d918ab-7f77-409f-8bda-3216b1b4c943" alt="Description de l'image" width="300">

   <img src="https://github.com/user-attachments/assets/3da49a46-4fc3-4640-a486-695994331480" alt="Description de l'image" width="300">
   

   -Nous avons renommé la colonne "£" en "montant (£)" et nous avons transformé cette colonne au préalable de type texte en décimal fixe
   <img src="https://github.com/user-attachments/assets/78733526-b5ce-437f-963f-6d526221f81b" alt="Description de l'image" width="300">

   -Nous avons veillé à regarder s'il yavait des doublons(il n'y en avait pas), pas de valeurs manquantes, ni de valeurs erronées

   -Après avoir cherché longuement pourquoi nous avions des nombre négatifs dans la colonnes montants, nous sommes arrivés à la conclusion que ces montants devaient corespondre à des achats non réalisés, ou des remboursements donc qu'ils restaient valable dans notre tableau.

   
3. **Modélisation des données** : Création de relations entre les différentes tables pour structurer l'analyse dans Power BI.
4. **Visualisation** : Conception de tableaux de bord Power BI comprenant des graphiques interactifs, des filtres, et des mesures clé comme les dépenses totales, les dépenses par fournisseur et par catégorie.
5. **Analyse des résultats** : Interprétation des visualisations pour formuler des conclusions pertinentes.

## Fonctionnalités Principales
- **Tableaux de bord dynamiques** : Plusieurs vues interactives permettent de filtrer les données selon différents critères.
- **Filtres personnalisés** : Filtrage par fournisseur, catégorie d’achat, et montant dépensé.
- **KPI (Indicateurs Clés de Performance)** : Indicateurs des dépenses totales, des fournisseurs principaux, et des catégories les plus dépensières.
  
## Outils Utilisés
- **Power BI** : Pour la visualisation et l’analyse des données.
- **Excel** : Pour le prétraitement et le nettoyage des données.
- **GitHub** : Pour la gestion du code et la publication du projet.

## Captures d'écran
Voici quelques exemples des visualisations créées dans Power BI:

![Capture d'écran du tableau de bord](URL_image_tableau_de_bord.png)
*(Insérer des images des tableaux de bord pour rendre le projet plus visuel)*

## Comment Visualiser le Projet
Pour consulter le projet :
1. [[Télécharger le fichier Power BI](lien_vers_le_fichier.pbix)](https://github.com/ryantchuisseu/analyse_depenses_gouvernementales/blob/main/Les%20d%C3%A9penses%20gouvernementales%20en%20Novembre.pbix) et l'ouvrir dans Power BI Desktop.
2. Naviguer à travers les différents tableaux de bord et utiliser les filtres pour explorer les données.

## Conclusion
Ce projet démontre mes compétences en **analyse de données** et en **création de tableaux de bord Power BI** interactifs. Il met en avant ma capacité à structurer des données complexes pour en tirer des insights pertinents, applicables dans un contexte gouvernemental ou dans d'autres secteurs.

## Contact
Pour toute question ou information supplémentaire, n’hésitez pas à me contacter :
- **Email** : donel.tchuisseu@gmail.com
- **LinkedIn** : https://www.linkedin.com/in/ryan-tchuisseu/

