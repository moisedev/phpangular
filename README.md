# phpangular
Test pratique PHP/Angular <br/>

# Installation back-end (Symfony pour un microservice, console application API version  5.2 ):  <br/>
1- Ajout fichier environnement ( <b> .env </b> ):  <br/>
Model : phpangular\students_api\ .env.local  <br/>
Modification configuration selon votre serveur avec DATABASE_URL <br/>

Dans le repértoire students_api :  <br/>
exécuter les commandes suivantes 
2 -composer install --prefer-dist  <br/>
3- php bin/console doctrine:database:create  <br/>
4- php bin/console doctrine:migrations:migrate <br/>

# Installation front-end (Angular ):  <br/>
1- Installation node js ( https://nodejs.org/en/download/) <br/>
2- Installation Angular Cli  <br/>
npm install -g @angular/cli <br/>
3- Dans le repértoire students :  <br/>
npm install 

4- Modification API_URL dans le fichier students/src/environments/environment.prod.ts <br/>

ng serve
