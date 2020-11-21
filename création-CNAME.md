# Créer une instance d'hébergement #

Voici la manip à faire afin de créer un site sous GitHub avec un nom de domaine personnalisé (ainsi de ne plus avoir besoin de passer par un hébergeur type Gandi ou OVH) :

* aller sur le site de son hébergeur et se connecter
* se rendre sur "nom de domaine"
* cliquer sur l'onglet DNS (système de nom de domaines)
* cliquer sur ajouter
* choisir "CNAME" (pour canonical name = un type d’enregistrement DNS qui permet de coupler un alias de nom à un nom de domaine réel ou canonique.)
* se choisir un nom (par exemple : dev) : dev.amzer.bzh
* entrer "violaine-web.github.io." comme "nom d'hôte" afin d'utiliser GitHub comme hébergeur
* cliquer sur créer
* aller sur son compte GitHub, sélectionner le projet pour lequel on veut personnaliser le nom de domaine
* aller dans Settings et descendre sur la partie GitHub pages
* entrer "dev.amzer.bzh" dans la parie "custom domain" et enregistrer
* boire un thé en attendant que le tout se mette à jour !
