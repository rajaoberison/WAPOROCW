# Carnets Jupyter pour le didacticiel ouvert "Productivité de l'eau et comptabilité de l'eau à l'aide de WaPOR"
![](http://www.fao.org/typo3temp/pics/93f49ce381.jpg)
## [Voir le cours complet sur IHE Delft OpenCourseWare](https://ocw.un-ihe.org/course/view.php?id=117&section=0)

Auteurs: Bich Tran, Abebe Chukalla, Solomon Seyoum

<html>
  <head>
    <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>
  </head>
</html>

## Contenu

### Module 1: Introduction et Usage

- Unité 4 Analyse de données spatiales de WaPOR à l’aide de Python 
    * Télécharger les données raster WaPOR
    * Couper et rééchantillonner
    * Calcul raster
- Unité 5 WaPOR API
    * Obtenir le catalogue et le tableau de données disponibles
    * Obtenir des séries chronologiques de points et de zones
    * Obtenir raster et couper raster
    * Obtenir raster de productivité de l'eau 

### Exécuter des carnets 

**Étape 1**: Téléchargez le fichier zip du référentiel et décompressez 

OU

Cloner dans Git Bash ([Git](https://git-scm.com/) doit être installé)

    >>> git clone https://github.com/wateraccounting/WAPOROCW.git


**Étape 2**: Ouvrez Anaconda Prompt, changez de répertoire en dossier **..\WAPOROCW\notebooks**

    >>> cd ..PATH..\WAPOROCW\notebooks
    
**Étape 3**: Créer un nouvel environnement à partir du fichier environment.yml

    >>> conda env create
    
![](./create_env.PNG)

**Étape 4**: Ensuite, activez l'environnement avec les packages requis

    >>> conda activate waporocw
  
**Étape 5**: Commencer jupyter notebook

    >>> jupyter notebook
    
![](./activate_env.PNG)
