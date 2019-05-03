# The Gossip Project in Rails

Projet avec Rails

This applicaiton is made with full love by **Alexandre Labonne (@Lab's)** and **Brice Jones (@brice)** from Toulouse.

## Ruby/rails version
  - version ruby:

``` $ ruby --version ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-darwin17] ```

  - version rails:

```$ rails --version Rails 5.2.3 ```

  - version PostGreSQL:
 
``` $ psql --version psql (PostgreSQL) 11.2 ```

## System dependencies
- base de données PostGreSQL

## Configuration
- faire un ```git clone git@github.com:notmoebius/sem5j1.git```
- faire un ```bundle install```
- faire un ```rails db:create``` pour la BDD
- faire un ```rails db:migrate```pour créer les tables de la BDD
- faire un ```rails db:seed```pour alimenter la BDD avec un jeu d'essai.

## How to run the test suite
- Lancer le serveur avec ```$ rails server```
- Dans le navigateur, == http://localhost:3000 ==

## Les fonctionnalités
L'application permet de :

- créer un utilisateur avec tout ce qui en incombe (profil, potin, commentaires...)

- ajouter un nouveau potin, l'éditer, le supprimer...

- accéder à une page cachée : en saisissant l'URI suivante: http://localhost:3000/welcome/votre_nom

- jouer avec le site, découvre le donc !
