# Denver Crimes Visualization

## Présentation
Une application web interactive permettant de visualiser les crimes et délits à Denver (Colorado, USA) de 2010 à 2021. Ce projet offre diverses visualisations cartographiques et graphiques pour analyser les tendances criminelles par quartier, district, et precinct.

## Démo en ligne
[https://denver-crimes.vercel.app/index.html](https://denver-crimes.vercel.app/index.html)

**Remarque importante:** En raison des limitations de Vercel, certaines fonctionnalités sont restreintes dans la démo en ligne:
- Utilisez uniquement les onglets Quartiers, Districts et Precincts
- Limitez vos requêtes aux années 2010, 2011 et 2012
- Les requêtes volumineuses peuvent échouer ou s'exécuter lentement

## Fonctionnalités
- Visualisation des crimes sur carte interactive (Leaflet)
- Cartes de chaleur montrant la densité des incidents
- Filtrage par catégorie de crime et par année
- Analyse par quartiers, districts et precincts
- Graphiques statistiques (répartition par catégorie, évolution mensuelle)
- Interface adaptée aux appareils mobiles

## Technologies utilisées
- **Frontend**: HTML, CSS, JavaScript, Leaflet.js, Chart.js
- **Backend**: Node.js, Express
- **Base de données**: MySQL
- **Hébergement**: Vercel

## Installation locale

### Prérequis
- Node.js (v18.x recommandé)
- MySQL

### Étapes d'installation
1. Clonez ce dépôt
2. Installez les dépendances: `npm install`
3. Créez une base de données MySQL
4. Importez les données à partir des fichiers SQL dans `/data_files/sql_files/`
5. Créez un fichier `.env` avec vos identifiants de base de données:
   ```
   DB_HOST=votre_host
   DB_USER=votre_utilisateur
   DB_PASSWORD=votre_mot_de_passe
   DB_NAME=votre_base_de_donnees
   ```
6. Démarrez l'application: `npm start`
7. Accédez à l'application via `http://localhost:3000`

## Captures d'écran

![Screenshot](./public/img/screen7.png)
![Screenshot](./public/img/screen6.png)
![Screenshot](./public/img/screen5.png)

*Plus de captures d'écran disponibles dans le dossier `/public/img/`*

## Structure du projet
- `/public`: Fichiers frontend (HTML, CSS, JS)
- `/data_files`: Scripts de conversion et fichiers SQL pour la base de données
- `index.js`: Serveur Express et connexion à la base de données

## Licence
ISC

les fichiers .sql sont dans /data_files/ pour créer la base de données 


![Screenshot](./public/img/screen7.png)
![Screenshot](./public/img/screen6.png)
![Screenshot](./public/img/screen5.png)
![Screenshot](./public/img/screen4.png)
![Screenshot](./public/img/screen3.png)
![Screenshot](./public/img/screen2.png)
![Screenshot](./public/img/screen1.png)
![Screenshot](./public/img/screenshot.png)
![Screenshot](./public/img/quartiers.png)
![Screenshot](./public/img/mobile1.png)
![Screenshot](./public/img/mobile2.png)
![Screenshot](./public/img/mobile3.png)