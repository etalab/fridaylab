# fridaylab

Le *fridaylab*, c'est un moment ouvert à tous le vendredi après-midi pour travailler ensemble en atelier.

On peut imaginer : 

- Tester un nouvel outil (par exemple, la machine à données du ministère de l'enseignement sup et de la recherche 
- Apprendre à utiliser un nouvel outil (par exemple, se former à la ligne de commande, à git, etc)
- Rédiger du contenu (par exemple, une page d'onboarding pour Etalab, le formulaire des saisines AGD, etc) 
- Faire une réutilisation d'un jeu de données ouvert dans la semaine
- Remettre en forme un jeu de données ouvert sur datagouv
- Préparer un hackathon
- Atelier dataviz : tester des outils libres et faciles à prendre en main de dataviz (raw, kepler.gl, umap, datawrapper, etc)

On peut aussi inviter des personnes d'autres administrations.

## 22 juin 2018 

- Atelier explication de l'algorithme de la taxe d'habitation

## 15 juin 2018 

- Pas de fridaylab : tous à [Datafin](https://datafin.fr/) !

## 08 juin 2018 

* Machine à données : On a testé la [Machine à données](http://51.15.221.77/index.php/Home), un service web développé dans le cadre du programme [entrepreneur d'intérêt général](https://github.com/entrepreneur-interet-general) qui permet d'apparier des données avec des référentiels. Initialement, on voulait apparier l'annuaire de l'éducation et le fichier SIRENE mais le ministère de l'Education nationale nous a devancé. Depuis juin, l'[annuaire de l'éducation](https://data.education.gouv.fr/explore/dataset/fr-en-annuaire-education/?disjunctive.type_etablissement) contient les code SIRET associés :).

## 01 juin 2018

* [Openfisca] : reboot du [simulateur openfisca](https://github.com/openfisca/demonstrator) @taniki et @maukoquiroga
  - UI ok
    - Fix documentation : ne pas faire `elm make src/Main.elm` car cela écrase le fichie `index.html`
  - Problème d'identification de la version de l'[API](https://github.com/openfisca/openfisca-web-api) adaptée à l'UI : test avec la version ~1.3.4
    - Fix documentation : installser en utilisation la commande `pip install --editable .[paster] OpenFisca-France==16.0.0` pour contourner les problèmes de rétro-compatibilité
  - Next step : modifier l'UI pour utiliser la dernière version de l'api
* [Editorial datagouv] : En préparation de la coupe du monde, on a préparé une [petite dataviz](https://github.com/pachevalier/coupedumonde) à publier sur datagouv
* [Blog AGD] : En attendant de passer le blog AGD sous Jekyll, on a réparé le [Wordpress](https://agd.data.gouv.fr/)

## 25 mai 2018 

* [Wiki-data-gouv](https://github.com/etalab/wiki-data-gouv) : On a préparé le déroulé du garagethon du 12 juin autour des collaborations entre Wikidata et Datagouv.
* [Datafin] : Pour préparer le hackathon #datafin, on a converti la nomenclature comptable commentée (NCC) d'un fichier Excel à 60 onglets à un fichier [CSV simple](https://github.com/pachevalier/tidycge/blob/master/data-raw/tidy_ncc.csv)

## 18 mai 2018

* [Blog AGD] : En une après-midi, on a relu les articles du blog AGD pour migrer le blog de Wordpress à Jekyll ! Le résultat est dispo sur la branche `content-only` du repo [agd.data.gouv.fr](https://github.com/etalab/agd.data.gouv.fr/tree/content-only).
