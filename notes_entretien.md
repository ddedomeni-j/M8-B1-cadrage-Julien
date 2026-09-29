# Notes d'entretien — Cas A — Cabinet Devalle

## 1. Avant le rendez-vous — 12 questions + 3 de réserve

| # | Priorité (1-3) | Catégorie | Question |
|---|---:|---|---|
| 1 | 1 | Processus actuel | Pouvez-vous décrire les étapes suivies aujourd’hui pour rédiger un courrier type ? |
| 2 | 1 | Processus actuel | Pouvez-vous décrire les étapes suivies aujourd’hui pour rechercher une jurisprudence pertinente ? |
| 3 | 1 | Critère de succès chiffré | Quel objectif chiffré vous permettrait de considérer le démonstrateur comme réussi ? |
| 4 | 1 | Coût d’une erreur | Quelle erreur produite par l’outil serait la plus dommageable pour le cabinet ? |
| 5 | 1 | Données : volume | Quel volume de documents est disponible pour le projet ? |
| 6 | 2 | Qualité métier | Comment évaluez-vous aujourd’hui la pertinence d’une jurisprudence trouvée ? |
| 7 | 1 | Confidentialité | Les documents contiennent-ils des informations couvertes par le secret professionnel ? |
| 8 | 2 | Hébergement | Un service externe peut-il traiter les documents du cabinet ? |
| 9 | 2 | Données personnelles | Les documents contiennent-ils des données personnelles ? |
| 10 | 1 | Données : extrait | Pouvez-vous transmettre un extrait représentatif de documents, anonymisé si nécessaire ? |
| 11 | 2 | Accès aux données | Dans quelles conditions l’outil peut-il accéder au texte intégral des décisions du cabinet ? |
| 12 | 2 | Délai | À quelle date souhaitez-vous disposer d’un premier démonstrateur ? |
| R1 | réserve | Validation humaine | Quel niveau de validation humaine est requis avant d’utiliser une réponse de l’outil ? |
| R2 | réserve | SI / accès | L’infrastructure actuelle permet-elle déjà à un outil d’accéder aux décisions stockées sur votre serveur ? |
| R3 | réserve | Budget | Quel budget le cabinet envisage-t-il pour le démonstrateur ? |

## 2. Pendant le rendez-vous — dit / interprété

| # | Question posée (telle quelle) | Ce que le client a dit | Ce que j'en interprète |
|-|---|---|---|
|1| Pouvez-vous décrire les étapes suivies aujourd’hui pour rédiger un courrier type ? | « Chaque avocat a ses vieux courriers sur son poste, et on copie-colle. [...] le dossier “modèles” partagé [...] date de 2019 et personne ne le met à jour. Les assistantes préparent, l’avocat relit et signe. » | Les modèles sont dispersés et obsolètes. La génération de courriers ne doit pas être prioritaire sans travail préalable de sélection, validation et mise à jour. La validation par un avocat fait déjà partie du processus. |
|2| Pouvez-vous décrire les étapes suivies aujourd’hui pour rechercher une jurisprudence pertinente ? | « Notre vraie richesse, ce sont nos propres dossiers : les décisions qu’on a obtenues ici, à Bordeaux. [...] on cherche par nom de fichier… ou on demande au collègue qui s’en souvient. » | Le fonds documentaire interne est la source prioritaire. La recherche actuelle dépend des noms de fichiers et de la mémoire des personnes. |
|3| Quel objectif chiffré vous permettrait de considérer le démonstrateur comme réussi ? | « Si chaque avocat gagne une heure par jour [...] Et pour la recherche : retrouver la bonne décision en moins d’une minute. » | Les objectifs sont un gain d’une heure par avocat et par jour, et une recherche en moins d’une minute. Il manque le volume quotidien de recherches pour mesurer le gain de temps. |
|4| Quelle erreur produite par l’outil serait la plus dommageable pour le cabinet ? | « Une erreur dans un courrier ou une jurisprudence qui n’existe pas, c’est ma responsabilité professionnelle engagée. [...] Tout doit être vérifiable. » | Aucun résultat sans source consultable. La validation humaine est indispensable avant tout usage professionnel. |
|5| Quel volume de documents est disponible pour le projet ? | « Environ 2 000 décisions sur les quinze dernières années, en PDF ou en Word, plus des milliers de courriers archivés. [...] les plus anciennes décisions sont des scans papier, pas toujours très lisibles. » | Le volume est compatible avec un pilote. La qualité des formats et des scans devra être évaluée avant indexation. |
|6| Comment évaluez-vous aujourd’hui la pertinence d’une jurisprudence trouvée ? | La réponse reçue décrit à nouveau les sources utilisées: abonnement à une base juridique et décisions internes du cabinet recherchées par nom de fichier ou mémoire d’un collègue. | Le critère précis de pertinence n’a pas été obtenu. Il faut le définir avec les avocats à partir de cas réels. A ajouter dans les questions ouvertes |
|7| Les documents contiennent-ils des informations couvertes par le secret professionnel ? | « Absolument. Tout ce qui est dans nos dossiers est couvert par le secret professionnel. [...] si ça fuit, c’est ma responsabilité personnelle devant le Barreau. » | Risque critique. Le corpus exige chiffrement, accès limité, journalisation et hébergement français contractuellement sécurisé. |
|8| Un service externe peut-il traiter les documents du cabinet ? | « Je ne veux pas que mes dossiers partent dans un cloud américain. Un hébergeur français avec un contrat sérieux, pourquoi pas. » | Un prestataire français est acceptable sous conditions contractuelles. Un cloud américain est exclu. |
|9| Les documents contiennent-ils des données personnelles ? | La cliente réaffirme que tous les dossiers sont couverts par le secret professionnel. | La présence de données personnelles est très probable, mais elle n’est pas confirmée explicitement. Point à instruire pour le RGPD. |
|10| Pouvez-vous transmettre un extrait représentatif de documents, anonymisé si nécessaire ? | Une assistante tient un registre avec « numéro, date, matière, juridiction, issue, et le nom du fichier ». Seul le registre est transmis, pas les décisions. | Les métadonnées permettent de localiser et filtrer les décisions. Le texte intégral reste nécessaire pour une recherche dans le raisonnement juridique. |
|11| Dans quelles conditions l’outil peut-il accéder au texte intégral des décisions du cabinet ? | La cliente répond à nouveau que tout dossier est couvert par le secret professionnel. | Les conditions techniques d’accès ne sont pas précisées. L’accès doit être limité au corpus autorisé et respecter les droits définis par le cabinet. |
|12| À quelle date souhaitez-vous disposer d’un premier démonstrateur ? | « Pas d’urgence absolue. Je préfère quelque chose de fiable dans six mois que quelque chose de risqué dans un mois. » | Horizon cible: environ six mois. La fiabilité est prioritaire sur la rapidité de livraison. |
|13| Quel niveau de validation humaine est requis avant d’utiliser une réponse de l’outil ? | « Rien ne part sans qu’un avocat ait relu et signé. [...] l’outil peut préparer, proposer, retrouver, mais c’est nous qui décidons. » | Toute sortie doit être relue et validée par un avocat. L’outil assiste; il ne décide ni n’envoie de document. |
|14| L’infrastructure actuelle permet-elle déjà à un outil d’accéder aux décisions stockées sur votre serveur ? | « Aujourd’hui, tout le monde a accès à tout le serveur, avocats et assistantes. [...] il ne lit que ce qu’on l’autorise à lire, et rien ne sort du cabinet. » | Les droits actuels sont trop larges pour la nouvelle solution. Il faut mettre en place des accès par rôle et limiter le corpus accessible à l’outil. |
|15| Quel budget le cabinet envisage-t-il pour le démonstrateur ? | « Nous sommes douze avocats à Bordeaux, plus quatre assistantes. » | Le budget n’a pas été communiqué. La réponse précise la taille de l’organisation: 12 avocats et 4 assistantes. Elle suggère un nombre d’utilisateurs limité pour le démonstrateur; le besoin de connexions simultanées reste toutefois à confirmer. |

**Relance imprévue - changement d'infrastructure.** :
- La cliente annonce que le prestataire informatique arrête son contrat le 31 décembre et qu’aucun administrateur ne maintiendra le serveur du cabinet dans l’intervalle. 
- Cette information modifie une contrainte d’architecture: la solution ne doit pas dépendre d’une administration interne non disponible. L’hébergement français doit être infogéré, avec responsabilités contractuelles claires pour les sauvegardes, mises à jour de sécurité, supervision et gestion des incidents.
- Cette relance a entraîné la mise à jour des sections données, risques et architecture du cadrage.

### Boussole — ce que j'ai déjà obtenu

| Information | Statut | Réponse n° |
|---|---|---|
| Besoin réel (≠ demande exprimée) | 🟢 | 2, 3, 4 |
| Processus actuel | 🟢 | 1, 2 |
| Données : existence | 🟢 | 2, 5, 10 |
| Données : volume | 🟢 | 5 |
| Données : qualité | 🟠 | 1, 5, 10 |
| Données : extrait obtenu | 🟢 | 10 |
| Données personnelles / confidentialité | 🟠 | 7, 9, 11 |
| Critère de succès chiffré | 🟢 | 3 |
| Coût d'une erreur | 🟢 | 4 |
| Erreurs tolérées (chiffre : fausses alertes, mauvais routage…) | 🟠 | 4 |
| Utilisateurs | 🟢 | 15 |
| Validation humaine / qui décide | 🟢 | 13 |
| SI / hébergement | 🟢 | 8, 14, relance imprévue |
| Budget | 🔴 | — |
| Délai | 🟢 | 12 |
| Ce qui a déjà été essayé | 🟢 | 1, 2 |

## 3. Après — ce que je n'ai pas pu demander → questions ouvertes

| Je n'ai pas pu demander / pas eu de réponse claire | Pourquoi c'est important | → §6 du cadrage |
|---|---|---|
| Quel budget est prévu pour le démonstrateur ? | Arbitrer le périmètre, l’hébergement infogéré et les prestations nécessaires. | Budget à confirmer |
| Quels critères permettent aux avocats de juger une décision pertinente ? | Constituer un jeu de cas de test et mesurer la qualité de la recherche. | Critères de pertinence à définir avec les avocats |
| Quelles catégories de données personnelles figurent dans les décisions et courriers ? | Déterminer les obligations RGPD, la minimisation et les mesures de protection adaptées. | Cartographie des données personnelles à réaliser |
| Quel volume quotidien de recherches est réalisé par avocat ? | Mesurer le gain de temps réel et évaluer la cible d’une heure gagnée par jour. | Mesure initiale du temps et du volume de recherches |
| Qui utilisera effectivement l’outil, parmi les 12 avocats et 4 assistantes ? | Définir les rôles, les droits d’accès et le volume d’utilisateurs du pilote. | Liste des utilisateurs et droits par rôle |
| Combien d’utilisateurs doivent pouvoir effectuer une recherche simultanément ? | Dimensionner l’accès au démonstrateur. | Capacité simultanée à confirmer |
| Quels droits techniques permettront à l’outil d’accéder aux décisions du serveur ? | Organiser un import sécurisé sans exposer l’ensemble des dossiers. | Modalités d’accès sécurisé à définir |
| Les conditions de l’abonnement juridique autorisent-elles l’indexation de son contenu ? | Éviter une réutilisation non autorisée de la base externe. | Vérification contractuelle avant indexation |
| Quelle durée de conservation doit être appliquée aux requêtes et aux journaux ? | Définir la politique de conservation et respecter le principe de minimisation. | Durée à valider avec le responsable de traitement |
| Qui assurera l’administration, les sauvegardes et les mises à jour après le 31 décembre ? | Garantir la continuité et la sécurité après le départ du prestataire informatique. | Hébergement infogéré ou futur prestataire à désigner |
