# Soutenance Impact Influence

Site de révision pour la soutenance du projet *Impact Influence* (titre professionnel, « Configurez des services réseaux et des équipements d'interconnexion »). Maquette Packet Tracer : trois bâtiments, 26 équipements, IPv4 et IPv6.

Aucune installation : ouvre `index.html` dans un navigateur.

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Le site de révision, en huit onglets |
| `trajet.html` | Le trajet de la trame, interactif : trajets pas à pas, soutenance partie par partie, trame à la loupe |

Les onglets de `index.html` :

- **Jour J** : format des 30 minutes, priorités par niveau, listes « la veille » et « dix minutes avant », kit de survie.
- **Chrono** : le script des 15 minutes avec un chronomètre de répétition. Il surligne le passage en cours, fait défiler le texte et signale la fourchette de 10 à 20 minutes.
- **Démos** : les six démonstrations du cahier des charges (commandes à copier, écran attendu, phrase à dire) et les tests que le jury peut improviser.
- **Jury** : les écarts au cahier des charges, puis 54 questions-réponses à réviser, chacune marquée « Je sais » ou « À revoir », avec un tirage au hasard.
- **Checklist** : la checklist de soutenance, avec une barre de progression.
- **Pièges** : les gestes interdits, les phrases fausses et leur correction, les documents dépassés.
- **Maquette** : adressage, interfaces, VLAN, serveurs, postes et configurations clés.
- **Documents** : l'index des supports de cours, du plus récent au plus ancien.

Les cases cochées et les notes des questions sont enregistrées dans le navigateur (`localStorage`), sur l'appareil utilisé.

## Sources

Le contenu suit les versions les plus récentes des supports : le mode Soutenance de `trajet.html`, le *Cours définitif* et le dernier rapport de vérification (guide des 19 équipements). Les affirmations dépassées des anciens documents sont corrigées dans le site et listées dans l'onglet **Pièges**.

## Documents originaux

Ce dépôt est public : les supports originaux (PDF, notes, prompteur, livrable) n'y sont pas versionnés. Pour activer les liens de l'onglet **Documents** en local, copie le contenu de l'archive dans un dossier `documents/` à côté de `index.html`. Ce dossier est ignoré par Git.
