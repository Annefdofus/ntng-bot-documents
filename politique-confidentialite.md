# Politique de confidentialité — NTNG Bot

Dernière mise à jour — 10 octobre 2026

## Contact et finalités

NTNG Bot est utilisé pour l’organisation de la guilde DOFUS No Try No Gain : suivi des recrues, points d’intégration, recherche dans les discussions autorisées et bilans textuels.

Pour toute question, correction ou demande concernant les données, contactez **blackstarastral** sur Discord, nom affiché **Blackstars Astral**, depuis le serveur de la guilde. Si les messages privés sont fermés, demandez aux responsables du serveur un moyen de contact confidentiel sans publier les données concernées dans un salon public.

## Données traitées

- **Discussions autorisées** : texte du message, identifiants Discord du message, de son auteur, du salon et du serveur, et date de publication. Le bot peut importer les messages disponibles des 90 derniers jours et collecter les nouveaux messages pendant sa connexion.
- **Fiches renseignées par les responsables** : pseudo en jeu, identifiant Discord, arrivée, objectifs, autonomie, participation, intégration, progression, référent, statut et points de suivi.
- **Notes internes** : texte saisi par les responsables, auteur, date et joueur concerné.
- **Données techniques** : salons activés, position de reprise des imports et identifiants nécessaires pour respecter les exclusions individuelles. Les journaux techniques sont limités en taille et n’incluent pas volontairement les textes de messages, arguments des commandes ou jetons secrets.

La dernière activité affichée est déduite des messages archivés accessibles. Elle ne mesure pas l’activité DOFUS ou vocale.

Les MP ne sont pas lus. Les fils de discussion, forums, messages de bots et webhooks sont exclus de l’archivage. Les pièces jointes ne sont pas téléchargées. Le texte d’un message peut cependant contenir des liens ou informations que son auteur y a écrits : évitez d’y publier des données sensibles.

## Salons et personnes autorisées

Aucun salon n’est archivé par défaut. Un administrateur sélectionne les salons autorisés, individuellement ou après confirmation d’une liste par catégorie. Le choix d’une catégorie n’active pas automatiquement ses futurs salons.

Les fiches et notes sont consultables par les responsables autorisés. Les résultats issus des discussions sont limités aux salons que l’utilisateur et le bot peuvent voir et dont ils peuvent lire l’historique. Les réponses des commandes sont éphémères sur Discord.

La personne exploitant le bot et toute personne disposant d’un accès administratif à son stockage peuvent techniquement accéder à sa base et à ses sauvegardes. Les fichiers ne sont pas chiffrés par le bot lui-même. Discord traite les échanges selon ses propres règles. Cette version n’envoie pas le contenu à un fournisseur d’IA et ne comporte aucune fonction de vente de données ou de ciblage publicitaire.

## Conservation

Le bot et sa base sont hébergés sur le PC personnel de son exploitant, **blackstarastral**. Les archives et sauvegardes restent sur ce PC ; elles ne doivent pas être publiées dans le dépôt GitHub, qui sert à partager le code et la documentation.

Les messages sont conservés jusqu’à **90 jours après leur publication**, ou moins si une durée plus courte est configurée. L’import ne remet pas ce délai à zéro. La purge s’exécute au démarrage puis chaque heure tant que le bot fonctionne ; lorsque le bot est arrêté, elle attend le redémarrage. Les recherches excluent les messages hors période même avant la purge physique.

Les fiches, notes et points ne disposent pas d’une expiration automatique dans cette version : ils restent jusqu’à suppression manuelle ou demande d’effacement. Le départ du serveur ne déclenche pas leur suppression. Les responsables doivent retirer les informations devenues inutiles.

L’identifiant d’exclusion est conservé pour empêcher la collecte de vos messages jusqu’à votre demande de reprise. Désactiver un salon efface son archive locale et sa position d’import. Les copies de sauvegarde éventuelles sont gérées séparément par l’exploitant.

## Sauvegardes locales

La règle retenue est une sauvegarde locale hebdomadaire, conservée au maximum **30 jours après sa création**. La création des copies et la suppression de celles arrivées à expiration sont effectuées manuellement par l’exploitant : cette version ne les automatise pas. Une sauvegarde sur le même PC ne protège pas contre la perte de cet ordinateur ou de son disque.

Une copie peut contenir des messages effacés depuis de la base active, jusqu’à son expiration. La limite de 90 jours concerne donc la base active ; une copie peut en conserver certains jusqu’à 30 jours supplémentaires. Les sauvegardes ne sont pas utilisées pour la recherche courante.

Lors du traitement d’une demande d’effacement, l’exploitant supprime aussi les sauvegardes contenant les données concernées. La commande d’effacement du bot n’agit pas automatiquement sur ces copies : contactez **blackstarastral** pour cette intervention. Avant toute restauration, l’exploitant doit préserver les exclusions et réappliquer les effacements intervenus depuis la copie, puis purger les messages hors délai avant de remettre le bot en service.

## Effacement, exclusion et correction

`/confidentialite oublier confirmer:True` efface votre fiche, les notes et points rattachés à cette fiche, ainsi que les messages archivés dont vous êtes l’auteur. Votre identifiant est ensuite conservé pour exclure vos messages des imports et de la collecte future.

Cette commande ne supprime pas les messages de Discord, les sauvegardes, les mentions de vous dans les messages d’autres personnes, ni les notes que vous avez rédigées sur une autre fiche. Elle n’interdit pas techniquement à un responsable de recréer une fiche. Pour ces situations ou une opposition plus large, contactez **blackstarastral**.

`/confidentialite reprendre` retire l’exclusion : vos nouveaux messages, et les anciens messages encore dans la fenêtre de conservation lors d’un import applicable, peuvent à nouveau être archivés.

Les éditions et suppressions de messages reçues pendant la connexion sont répercutées. Celles intervenues pendant une déconnexion peuvent être manquées ; un import ultérieur ne constitue pas une synchronisation complète des anciennes suppressions. Contactez le responsable pour signaler un message restant dans l’archive.

Vous pouvez également demander l’accès aux données vous concernant, leur correction, leur effacement ou faire connaître votre opposition au contact indiqué. La commande automatique ne remplace pas le traitement humain des demandes et des droits applicables.

## Mise à jour de cette politique

Les membres concernés doivent être informés des modifications importantes avant leur application. La version publiée doit refléter l’hébergement, les pratiques de sauvegarde et l’utilisation effective du bot.
