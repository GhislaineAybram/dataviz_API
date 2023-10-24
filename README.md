# Les prédictions de Madame Kymg

Cette application web permet de donner des prédictions sur la nationalité puis sur l'âge de l'utilisateur en fonction de son prénom. 
Ce projet a pour objectif de développer une application web qui permette de visualiser des données de façon dynamique.

## Equipe de 4 personnes - 6 jours

Kai LAM - Margot HUET - Yoann LORDINOT - Ghislaine AYBRAM

## Aperçu du projet

*Page d'accueil du site de prédictions de Madame Kymg*
![App Screenshot](/screen/predictions_accueil.jpg)

*Après avoir saisi son prénom l'utilisateur se voit prédire sa nationalité*
![App Screenshot](/screen/predictions_nationalite.jpg)

*Une fois la nationalité validée, Madame Kymg prédit l'âge de l'utilisateur*
![App Screenshot](/screen/predictions_age.jpg)

*Element de notation sur 5 étoiles en fin de prédiction*
![App Screenshot](/screen/predictions_notation%20finale.jpg)

## Tech Stack

**Langages:** Javascript, HTML, CSS

## API références

**Pour aller chercher la nationalité à partir du prénom**
api.nationalize.io/?name=${nom.value}

**Pour aller chercher le nom du pays à partir du code pays**
happyapi.fr/api/getLands/result/result/${codePays}

**Pour aller chercher le drapeau du pays à partir du code pays**
flagsapi.com/${codePays}/shiny/64.png

**Pour aller chercher l'âge à partir du prénom et de la nationalité (validée par l'utilisateur)**
api.agify.io/?name=${nom.value}&country_id=${countryId}

## Fonctionnalités
- [x] utilisation de fonctions asynchrones pour envoyer des requêtes API,
- [x] connections à plusieurs API,
- [x] manipulation du CSS et du HTML,
- [x] mise en place d'un site web responsive design,
- [x] création d'événements (déclenchement d'animations, de transitions visuelles...).
  
## Reste à implémenter
- [ ] créer une visualisation des données différente (pour les nationalités possibles en fonction du prénom de l'utilisateur) par exemple sous forme de camembert ou d'histogramme.



