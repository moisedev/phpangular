# phpangular
Test pratique PHP/Angular

# Installation back-end (Symfony pour un microservice, console application API version  5.2 ): 
1- Copie fichier : 
phpangular\students_api\.env.local par .env 
Modification configuration selon votre serveur avec DATABASE_URL

Dans le repértoire students_api : 
exécuter les commandes suivantes 
composer install --prefer-dist

2- php bin/console doctrine:database:create
3- php bin/console doctrine:migrations:migrate

# Installation front-end (Angular ):  
1- Installation node js ( https://nodejs.org/en/download/)
2- Installation Angular Cli 
npm install -g @angular/cli
3- Dans le repértoire students : 
npm install 

4- Modification API_URL dans le fichier students/src/environments/environment.prod.ts

ng serve
