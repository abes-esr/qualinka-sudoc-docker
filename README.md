# qualinka-sudoc-docker
Configuration docker 🐳 pour déployer Qualinka-Sudoc

[![Docker Pulls](https://img.shields.io/docker/pulls/abesesr/qualinka-sudoc.svg)](https://hub.docker.com/r/abesesr/qualinka-sudoc/)

Ce dépôt est issu du projet Qualinca (Qualité et interopérabilité de grands catalogues documentaires) :  
C'est un projet de recherche fondamentale labellisé par l'ANR-Contint 2011 qui vise à développer des mécanismes permettant de qualifier le niveau de qualité d’une base documentaire existante, d'améliorer le niveau de qualité d’une base, de maintenir un niveau de qualité donné en contrôlant les opérations de mises à jour de ces bases, et d’exploiter ces bases en prenant en compte leur divers niveaux de qualité.    
Ce travail a été réalisé avec l'équipe GraphIK / BOREAL du LIRMM : https://www.lirmm.fr/qualinca/index7ca7.html?q=fr    
Clément SIPIETER a repris ce travail et l'a développé en Java, objet de ce dépôt.

Ce dépôt contient les scénarios spécifiques aux données Abes/Sudoc : https://github.com/abes-esr/qualinka-sudoc  
Il utilise comme "coeur" ou moteur, le dépôt : https://github.com/abes-esr/sudoqual-framework

Ce dépôt contient la configuration docker 🐳 pour déployer l'application en local sur le poste d'un développeur, ou bien sur les serveurs de dev, test et prod. 

URLs de dev :  
- https://qualinka-dev.idref.fr/predict/info  
- https://qualinka-dev.idref.fr/predict/light  
- diplotaxis1-dev.v212.abes.fr:9419/info  
- diplotaxis1-dev.v212.abes.fr:9419/light  

URLs de test :  
- https://qualinka-test.idref.fr/predict/info  
- https://qualinka-test.idref.fr/predict/light  
- diplotaxis1-test.v202.abes.fr:9419/info  
- diplotaxis1-test.v202.abes.fr:9419/light  

URLs de prod :  
- https://qualinka.idref.fr/predict/info  
- https://qualinka.idref.fr/predict/light  
- diplotaxis1-prod.v102.abes.fr:9419/info  
- diplotaxis1-prod.v102.abes.fr:9419/light  
