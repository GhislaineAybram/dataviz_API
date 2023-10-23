# Les prédictions de Madame Kymg

Cette application web permet de donner des prédictions sur la nationalité puis sur l'âge de l'utilisateur en fonction de son prénom. 

## Equipe de 4 personnes

Kai LAM - Margot HUET - Yoann LORDINOT - Ghislaine AYBRAM

## Demo

Insert gif or link to demo

## API Reference

#### Pour aller chercher la nationalité à partir du prénom

```http
GET /api.nationalize.io/?name=${nom.value}
```
| Parameter   | Type     | Description                       |
| :---------- | :------- | :-------------------------------- |
| `nom.value` | `string` | **Required**. Prénom to fetch     |

#### Pour aller chercher le nom du pays à partir du code pays

```http
GET /happyapi.fr/api/getLands/result/result/${codePays}
```
| Parameter   | Type     | Description                       |
| :---------- | :------- | :-------------------------------- |
| `codePays`  | `string` | **Required**. Code pays to fetch  |

#### Pour aller chercher le drapeau du pays à partir du code pays

```http
GET /flagsapi.com/${codePays}/shiny/64.png
```
| Parameter   | Type     | Description                       |
| :---------- | :------- | :-------------------------------- |
| `codePays`  | `string` | **Required**. Code pays to fetch  |

#### Pour aller chercher l'âge à partir du prénom et de la nationalité (validée par l'utilisateur)

```http
GET /api.agify.io/?name=${nom.value}&country_id=${countryId}
```
| Parameter   | Type     | Description                       |
| :---------- | :------- | :-------------------------------- |
| `nom.value` | `string` | **Required**. Prénom to fetch     |
| `countryId` | `string` | **Required**. Code pays to fetch  |

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## Tech Stack

**Langages:** Javascript, HTML, CSS
