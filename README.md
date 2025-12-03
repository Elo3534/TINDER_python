# TINDER
# **Prédire le départ des salariés d'IBM par Machine Learning**
Analyse des facteurs déterminants dans l’acceptation d’un second rendez-vous en speed dating.

## *A. Méthodologie*  

L’analyse comprend la préparation des données, l’exploration et la visualisation.

Les outils et librairies utilisés sont les suivants :
- *Données :*
  - `Speed_Dating_Data.csv`
  - `Speed+Dating+Data+Key.pdf`

- *Environnement de développement :*
  
    - VSCode pour l’écriture du code Python et la gestion du projet.
  
- *Prétraitement et Nettoyage des données :*
  
    - `Pandas` pour la manipulation de données tabulaires,
  
    - `NumPy` pour les opérations numériques,
  
    - `Statsmodels`, `SciPy` pour les tests statistiques et les analyses complémentaires.
  
- *Visualisations :* 
    - `Matplotlib`, `Seaborn` et `Plotly` pour l’analyse exploratoire et la visualisation des distributions et relations entre variables.

  
- *Présentation des résultats :*  
    - Microsoft Power Point pour la synthèse et la communication des conclusions de l’étude.  


## *B. Problématique*  

L'équipe marketing Tinder analyse les données d'une expérience de speed dating (2002-2004) pour comprendre ce qui motive un second rendez-vous dans un contexte hétérosexuel.

Objectif : **Identifier pourquoi les gens acceptent un deuxième rendez-vous.**

Questions clés :

- *Attributs les moins désirables selon le genre ?*

- *Importance réelle de l'attractivité vs perception ?*

- *Intérêts communs priment-ils sur l'origine raciale ?*

- *Les personnes évaluent-elles correctement leur propre valeur sur le marché des rencontres ?*

- *L'ordre du speed dating influence-t-il les chances ?*

Données : Évaluations sur 6 critères (attractivité, sincérité, intelligence, amusant, ambition, intérêts communs) + données démographiques et questionnaire.  

Pour plus de détails, se référer au fichier `SpeedDating_Part1_nettoyage_EH.ipynb`.  

## *C. Résultats*

La décision d'un deuxième rendez-vous repose sur une hiérarchie stable : intelligence et sincérité dominent, l'attractivité physique arrive après. Les intérêts communs ou l'origine ethnique sont négligeables.

Des écarts genrés existent : les femmes valorisent plus l'intelligence, les hommes l'attractivité. Les participants surestiment l'importance de l'apparence dans leurs déclarations.

La décision est aussi affectée par le contexte :

- L'ordre de passage favorise les premiers rendez-vous.

- L'expérience affine la perception de sa propre valeur, sauf pour l'intelligence.

En résumé, les choix privilégient des qualités relationnelles durables (intelligence, sincérité) plutôt que des critères superficiels, mais restent influencés par des biais cognitifs et contextuels.

Pour plus de détails, se référer aux fichiers `SpeedDating_Part1_nettoyage_EH.ipynb` et `SpeedDating_Part2_analyses_EH.ipynb`.
## *D. Aperçus des visualisations*  


![Texte alternatif](/images_notebook/repartition_par_genre.png)
![Texte alternatif](/images_notebook/repartition_par_ethnie.png)
![Texte alternatif](/images_notebook/repartition_par_genre_par_ethnie.png)
![Texte alternatif](/images_notebook/distri_moyennes_par_attribut.png)
![Texte alternatif](/images_notebook/importance_attractivite_par_genre.png)
![Texte alternatif](/images_notebook/moy_attractivite_par_objectif_et_genre.png)
![Texte alternatif](/images_notebook/decision_revoir_meme_ethnie.png)
![Texte alternatif](/images_notebook/comparaison_effets_observes_effets_theoriques.png)
![Texte alternatif](/images_notebook/precision_autoeval.png)
![Texte alternatif](/images_notebook/taux_match_selon_ordre.png)

Pour plus de détails, se référer aux fichiers `SpeedDating_Part1_nettoyage_EH.ipynb` et `SpeedDating_Part2_analyses_EH.ipynb`.
