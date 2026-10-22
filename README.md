# Soutenance Impact Influence

*L’essentiel interactif* : une page de révision pour la soutenance du projet *Impact Influence* (titre professionnel, « Configurez des services réseaux et des équipements d'interconnexion »). Elle suit le document « L’essentiel à travailler », dans l’ordre de ses dix parties, en reprenant ses textes mot pour mot.

Aucune installation : ouvre `index.html` dans un navigateur.

## Les dix onglets

1. **La méthode** : « Sept règles, quatre questions ».
2. **La construction** : « Quinze problèmes, quinze solutions ».
3. **Le film** : « La Finance, du démarrage à la page web », en IPv4 puis en IPv6. Un paquet animé parcourt le schéma, et les tables NAT se remplissent au fil du trajet.
4. **La double panne** : « DISTRI-GAUCHE éteinte, liaison Rouge–Vert coupée ».
5. **Les données** : « Adressage, liaisons, routes, listes, NAT », avec un outil sur les préfixes.
6. **Les commandes** : « Équipement par équipement, chaque mot justifié », avec un outil qui fait juger un paquet par les listes.
7. **Les autres trajets** : « Les autres clients, les refus, les pannes ».
8. **Les pièges** : « Chaque piège, rangé sous sa règle ».
9. **Tes preuves** : « Ce que tu as testé, et ce qu’il reste à vérifier ».
10. **L’entraînement** : « Le retrait, les réflexes, le récit, la frise ».

## Ce qui est enregistré

La page garde, dans le navigateur (`localStorage`, clés `ess:*`), l’onglet ouvert, le trajet et l’étape en cours, le mode devine, l’équipement affiché, les cases « à vérifier » et les réponses du test du retrait. Rien n’est partagé entre deux appareils.

## Historique

Ce dépôt contenait un site de révision en huit onglets (`index.html`) et une page de trajet (`trajet.html`), bâtis sur l’ancienne version de la maquette. Ils contredisaient « L’essentiel à travailler » sur des points centraux : le NAT statique, présenté comme retiré ; les listes 120, présentées comme non appliquées ; le DHCP, placé sur le cœur ; l’adresse IPv6 du serveur web. Ils ont été remplacés par la page actuelle, et l’historique Git les conserve.

## Documents originaux

Ce dépôt est public : le document « L’essentiel à travailler » et les autres supports originaux (PDF, notes, maquette, livrables) n’y sont pas versionnés. Le fichier `.gitignore` les tient à l’écart.
