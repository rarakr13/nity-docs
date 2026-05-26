## Version 1.2.0 | 24/05/26
**Nity+ pour les serveurs communautaires**
- Nity+ est le nouvel abonnement du bot à 2,99€¹ par mois HT¹. Cet abonnement donne accès à 4 avantages et vous pourrez retrouver tous les détails en accédant à la catégorie Nity+ dans la commande `/aide` !
1. Commandes boostées
2. Commandes en avant-première
3. Limites élargies (dispo. courant 2026)
4. Level+

**Accédez à un historique de l'activité et des actions de vos membres (bêta)**
- Une nouvelle commande `/historique` permettra de suivre (à compter d'aujourd'hui si le bot était déjà présent sur le serveur ou dès que le bot est ajouté à un serveur) ces données :
1. le nombre de messages envoyés dans tous les salons et dans le salon le plus actif sur 1 semaine / mois / an / global
2. Le temps passé en vocal sur 1 semaine / mois / an / global et lors du dernier voc
3. Les actions de modération subies
4. Les changements de pseudos
5. Les changements de rôles
- Bientôt, la commande générera des graphiques pour suivre l'évolution du nombre de messages et d'heures en voc.
- Une option permettant de masquer le suivi de son profil est envisagée.

**Affinez les modules et configurez plus précisement les logs**
- La précédente refonte affichait un grand embed inutilement, une nouvelle interface récupère l'espace pris pour afficher + d'infos (le résumé du menu principal est encore amené à évoluer, mais le reste est fixé).
- Une configuration initiale est désormais proposée quand la commande est effectuée pour la première fois sur un serveur. L'utilisateur ne se retrouve plus devant plein d'options compliquées.
- L'avantage "Commandes en avant-première" de l'abonnement Nity+ permet d'accéder aux deux logs expérimentaux (dans le module "Statut vocal")
- CustomV1 est le début d'une meilleure personnalisation du bot. Bientôt intégré dans d'autres configs !
1. Choisssissez plusieurs salons d'envoi et associez des salons exclus à des logs en particulier.
2. Choississez plus précisément les logs envoyés par le bot.

**Dans le module Level, voici Level+ et CustomV1**
- Level+ est accessible aux serveurs possédant l'abonnement Nity+ et apporte ces avantages :
1. Vos membres ont accès à plus de choix pour personnaliser leur bannière de niveau.
2. L'XP gagné pendant un vocal est mis à jour en temps réel.
- Et pour tout le monde, CustomV1 est accompagné d'un coup de frais donné à la commande `/level` :
1. La bannière de niveau a été modernisée, plus claire et plus lisible. La génération de l'image a été optimisée.
2. Personnalisez votre bannière de niveau via la nouvelle commande `/info-level` !²
3. Les infos ont été déplacées dans cette nouvelle commande.

**Nouveau jeu : Mini Wolf**
- Mini Wolf est le quatrième jeu du bot, en bêta. Il est inspiré du jeu de société "Les Loups-garous de Thiercelieux".
- Ce jeu est pour l'instant réservé aux serveurs membres de Nity+. Lorsque le développement du jeu sera achevé, la commande sera déployée sur tous les serveurs non-abonnés.

**Quelques ajustements et autres infos**
- `/effacer-membre` devient une commande boostée (la commande est accessible à tous mais l'abonnement améliore la commande). Ici, Nity+ permet d'accélerer la vitesse d'effacement des messages.
- Rafraîchissement des couleurs du logo de Nity et nouvelle charte graphique !
- Vous pouvez filtrer les commandes affichées dans le `/aide` en fonction de vos perms.
- Correction d'un pb de calcul de l'XP gagné en vocal suite à une mise à jour récente.
- Correction d'une formulation trompeuse dans les logs lorsqu'un serveur perd un boost.
- Correction de la limite du nombre de caractères dans les modals du jeu `/party-quiz`.

**Bugs connus**
- ~~Le `/config Logs` s'auto-supprime 10 minutes après avoir fait la commande, et non après 10 minutes d'inactivité.~~ Corrigé dans la 1.2.1.

*¹Comme l'abonnement Nitro initialement, le paiement n'est pas fait en euros mais en dollars. Par ailleurs, le coût final peut légérement différer selon les frais pris par Discord, le taux de change $ / € en cours et les frais prélevés par la banque. Et à titre indicatif, le prix de l'abonnement comprend les 30% de frais prélevés par Discord au développeur, mais cela n'affecte pas ce que paie l'utilisateur. Bref, si vous faites gaffe à chaque centime dépensé, ci-dessous pour comprendre, un calcul avec différentes données en date du 23/05/2026 :*
1. *Abonnement HT : 2,99$*
2. *Abonnement TTC : 3,59$*
3. *Conversion $ / € : 3,09€*
4. *Exemple, Pierre a une carte Visa classique chez Société Générale = 2,7% de frais : 0,08€*
5. *Voici donc ce que Pierre paie réellement dans l'exemple à la fin : 3,17€/mois*

*²Disponible le 31/05/2026*

# Historique des versions
### Version 0.1.0 | 15/08/24
- Implémentation d'une commande `/config` pour configurer le bot de A à Z
- Ajout de la commande `/config-bienvenue` pour les arrivées et départs de membres sur le serveur
- Ajout de la commande `/config-autorole` pour avoir un rôle dès son arrivée sur le serv

### Version 0.1.1 | 17/08/24
- Correction d'un bug d'affichage avec la commande `/répéter` lorsque beaucoup de messages étaient envoyés
- Correction d'un bug assez rare avec la commande `/snipe`

### Version 0.1.2 | 24/08/24
- Correction d'un problème avec certaines commandes où la perm admin ne donnait pas le droit de les utiliser
- Certaines commandes sont maintenant persistantes (ex /help) pour qu'elles restent utilisables après 60sec

## Version 0.2.0 | 31/08/24
- La commande `/configuration-bienvenue` a été améliorée et n'est plus en bêta
- Implémentation et ajout de la commande `/configuration-logs` (bêta)
- Ajout de `/clear` pour effacer X messages (facultatif d'un membre)
- `/bim` et `/...` ont été améliorés, essayez-les (plusieurs fois)
- Améliorations QoL (par ex réponses du bot) et réécriture du code
- Suite à des pbs pour la config autorole, elle sera maj + tard

### Version 0.2.1 | 06/09/24
- Ajout de premières commandes de modération `/kick` et `/ban`
- Améliorations et correction de multiples bugs liés aux logs
- Correction d'un bug lié aux messages de départ
- Ajout d'une nouvelle commande fun `/amour`

### Version 0.2.2 | 13/09/24
- Ajout de 2 nouveaux logs via `/configuration-logs`

## Version 0.3.0 | 27/09/24
- Finalisation de la structure du code : répond plus rapidement, gère mieux les sauvegardes et les bugs, etc.
- Création en bêta d'une fonctionnalité originale nommée "Réputation" (+ d'infos ci-dessous)
- Ajout d'une commande `/rappel` pour créer des rappels uniques ou ponctuels
- Création d'un système d'avertissement avec `/warn` et `/liste-warns`
- Lancement de `/bombparty`, essayez-le !
- Support des commandes personnalisées pour certains serveurs (dont cyanide) avec le préfixe `*`
- Réputation : ajout des commandes `/configurer-notation`, `/noter`, `/reputation` et `/note-modifier`
- Harmonisation des réponses, des couleurs dans les embeds et rename de certaines commandes
- Ajout de 2 nouveaux logs via `/configuration-logs` et finalisation des logs actuels
→ Il se peut que quelques bugs subsistent mais tout devrait fonctionner comme prévu
- `/répéter` devient `/spam`, diverses modifs, optimisations et correction de bugs
- Ajout de nouvelles commandes de modération `/mute`, `/mute-temp` et `/unmute`
- Amélioration des étapes des commandes de configuration ainsi que du  `/aide`
- Ajout de la commande `/pp` pour afficher la photo de profil d'un membre

### Version 0.3.1 | 04/10/24
- Amélioration de la commande `/config-bienvenue` pour pouvoir donner le nombre de membres sur le serveur
- Dorénavant, retrouvez toute la liste des problèmes connus via la commande `/bot-info`
- Archivage temporaire de la commande `/rappel` du fait de plusieurs bugs rencontrés

### Version 0.3.2 | 11/10/24
- Suppression de la mention des membres dans les embeds, remplacé par le pseudo sans @ pour éviter les bugs
- Ajout d'erreurs lorsque qu'un membre n'ayant pas la perm de faire une commande essaie de la faire
- Correction d'un bug suite au passage à la 0.3.1 qui faisait que les commandes `/warn` et `/liste-warn` ne fonctionnaient plus.
- Les envois de liens ne sont plus considérés dans les logs comme des messages modifiés.
- Les modifs de salon pour les noms des vocs sont maintenant bien pris en compte.
- Le fichier de sauvegarde des mutes est maintenant géré au bon endroit.

### Version 0.3.3 | 18/10/24
- Refonte de la commande `/embed` qui envoie mtn un formulaire permettant de rentrer un titre, une description...
- Nouveau jeu avec `/quiz`, où vous devrez répondre à des questions de culture générale à 2 joueurs ou plus
- Les warns peuvent maintenant retirer des points de réputation selon la configuration du serveur
- Option pour `cancel` les commandes de config (et à venir les commandes de jeux et la future commande `/rappel`)
- Rename de la commande `/noter` en `/note-positive` et `/note-négative` et correction de plusieurs bugs

### Version 0.3.4 | 25/10/24
Dès maintenant, une description sera ajoutée ici à chaque maj. Les majs apporteront désormais + de changements que d'habitude, celle-ci concerne surtout des corrections de bugs.
- Le jeu `/quiz` reçoit les améliorations suivantes : il faut maintenant 10 points au lieu de 5 pour gagner, vous avez 15 secondes pour répondre au lieu de 30 et 50 questions ont été ajoutées. A l'avenir, il se peut que soit implémenté la possibilité de modifier le temps pour répondre et choisir des thèmes pour les questions (bêta - 55 questions au total)
- La commande `/ban` est de nouveau utilisable et la raison du ban est mtn envoyée dans un embed pour ceci et `/kick`
- Possibilité de réinitialiser les notes de tous les membres sur un serveur quand on relance la config-reputation
- Premier ajout d'erreurs lorsqu'il manque des permissions au bot ou que son rôle n'est pas assez haut
- Réécriture du code des commandes de réputation et des événements
- Autres corrections non répertoriées

## Version 0.4.0 | 25/11/24
Reprise du développement du bot après une pause liée aux cours (et à trouver comment faire fonctionner certaines commandes avec la BDD). Mise à jour concentrée sur les améliorations des commandes existantes.
- `/autorole` devient `/config-role`, une commande rassemblant diverses fonctionnalités liées aux rôles. Une nouvelle option dans l'embed affiché permettra d'ajouter un rôle pour une période définie, une deuxième permettra de gérer le rôle attribué à l'arrivée des membres et une 3eme permettra de lister et supprimer les rôles temporaires.
- Première intégration de la BDD PostgreSQL dans le nouveau `/config-role`, ainsi que dans `/config-bienvenue`, `/config-logs` et `/snipe`. Cela rendra le stockage des données beaucoup plus stable et certaines fonctionnalités plus fiables par rapport au JSON. Est visé la gestion intégrale des données d'ici à la 0.5.
- La commande `/écrire` devient une commande avec un préfixe `+dire` et a été améliorée
- Correction de `/note-modifier` pour qu'il ne soit pas compté comme une note négative
- Correction d'un bug critique lorsque certains logs sont actifs et qu'un rôle est modifié
- Amélioration des logs de création et suppression d'un salon / d'une catégorie
- Correction des doublons dans les messages supp de la commmande `/snipe`

### Version 0.4.1 | 02/12/24
L'objectif de cette MàJ est de corriger la majorité des bugs et lacunes existantes.
- Intégration du système de "pagination" dans les commandes `/liste-warn` et `/reputation`
- Les changements de permissions "neutres" sont maintenant pris en compte dans les logs
- Correction d'un bug avec le bouton "supprimer" de la commande `/liste-warn`
- Amélioration de `/aide`, `/bot-info` et BombParty devient `/kword`
- Correction des doublons suite à une màj du code des logs
- Affichage de la pp du membre dans certains embeds
- Ajout de "slowmodes" à toutes les commandes
- Epuration du code

### Version 0.4.2 | 09/12/24
- Réintégration de la commande /rappel maintenant séparée en 2 commandes : `/rappel-unique` et `/rappel-ponctuel`
- Ajout de la possibilité d'exclure un thème dans le jeu `/kquiz` (en bêta)
- Affichage de la pp du membre dans certains embeds
- Passage du `/embed` à la BDD PostGreSQL

### Version 0.4.3 | 15/12/24
- Amélioration du `/config-role`, plus facile à utiliser
- Le rôle auto. peut maintenant bien être supprimé
- Réduction de l'attente entre 2 logs
- Les logs fonctionnent de nouveau

### Version 0.4.4 | 23/12/24
Finalisation du transfert des fonctionnalités dans la BDD avant la 0.5, amélioration majeure d'une commande et correction de tous les bugs restants. Le dév est mis en pause pendant environ un mois.
- Les commandes de rappels ont été retravaillées. Les rappels uniques et périodiques dans un salon se trouvent maintenant au même endroit via `/rappel`, tandis que le type de rappel est mtn mentionné dans la liste. Ceux en privé ont maintenant leur propre commande `/rappel-prive` et sont "confidentiels", c'est à dire que vous verrez seulement vos propres rappels en effectuant la commande. Tous les bugs ont été corrigés et le "parcours" des commandes a été peaufiné.
- Passage de `/warn`, `/liste-warn`, `/config-reputation` et des commandes en `/note-x` et `/mute-x` dans PostGreSQL
- Important - correction de plusieurs bugs critiques empêchant de créer des rôles temporaires et de les afficher
- Important - correction de l'impossibilité de `/warn` un membre si le `/config-reputation` n'est pas activé
- Important - correction de l'impossibilité de `/snipe` certains membres
- Correction d'une erreur à l'utilisation du `/effacer`
- Correction de logs inutiles à la création d'un rôle
- Un bug au niveau des rôles temporaires subsiste, lors de la config. Il n'empêche pas le fonctionnement de la commmande.

## Version 0.5.0 | 03/02/25
La plus grosse màj effectuée jusqu'à présent. Nouveautés, améliorations, corrections... Cela donne des dizaines de types d'ajouts / de changements. Enfin, KR Bot change de nom et devient Nity.

Configuration du bot :
- Refonte du parcours de configuration (`/config-bienvenue`, `/config-logs` et `/config-reputation`)¹
- Fidélisez votre commu via un système de niveaux configurable avec `/config-niveaux`
- Vous pouvez maintenant ignorer des salons dans les logs avec `/config-logs`
- Création de liaisons entre configs pour qu'elles fonctionnent de pair à l'avenir

Fonctionnalités :
- Implémentation des commandes `/level` et `/modifier-level` liées à `/config-level`
- Supprimez tous les messages d'un membre de 1 à 14j avec `/effacer-membre`
- Le contenu du `/embed` est prérempli, l'auteur et date de modif sont loggés
- Nouvelle commande `/roulette` et refonte de la commande `/crush`

Jeux (NT - Games) :
- Lancement du jeu `/nt-wolf` en bêta, basé sur le célèbre jeu des Loups Garous²
- Intégration d'un système de configuration des parties dans tous les jeux
- Amélioration des réponses du jeu `/nt-word`
- Ajout de 50 questions à `/nt-quiz`

 QoL (Quality of Life) :
- Nity est désormais hébergé sur un serveur externe et ne subira plus d'interruptions
- Des infos ont été ajoutées dans les "footers" des embeds (footer = pied de page)
- Il y a + d'erreurs prises en compte par le bot pour informer l'utilisateur du pb
- Les logs suivants bénéficient d'améliorations : "Message modifié", "Vocaux"

Corrections et divers :
- Révision du code : inclut le passsage à mysql par souci de compatibilité avec le serv
- Modif des commandes faisables en privé, elles sont aujourd'hui toutes utilisables³
- Correction de bugs (rôle temp, reputation, logs de perms...)

¹Une meilleure cohérence entre ces commandes est prévue. ²Le jeu est expérimental mais évoluera rapidement. ³Hors `/rappel-prive` qui fonctionnera en PV dans une prochaine mise à jour.

### Version 0.5.1 | 10/02/25
La màj a été avancée d'une semaine et est plus stable que la 0.5 avec la correction de plusieurs bugs dont 1 critique (dû à l'ancienne version). Plusieurs améliorations ont aussi été faites :
- Remaniement du fonctionnement du jeu `/nt-quiz` : les réponses se font à présent via des réactions et un seul embed est utilisé tout au long de la partie (pour rappel, ce jeu se joue de 2 à 6 personnes)
- Il est désormais possible de configurer des rappels privés dans les MPs du bot
- Refonte des embeds de bcp de commandes, plus jolis et avec + d'infos
- Meilleure cohérence avec le reste des logs : pseudos, salons et roles et intégration d'un slowmode plus intelligent (évite une limitation du bot et est plus efficace)
- Ajout de `/top-level` et amélioration de `/level` et `/aide`
- Autres changements non détaillés

### Version 0.5.2 | 17/02/25
- Correction des messages vides dans `\snipe` et reformatage
- La commande `+dire` fonctionne de nouveau

## Version 0.6.0 | 27/02/25
Apporte une harmonisation entre les diverses commandes de config, une amélioration de l'expérience utilisateur et de nouvelles commandes. *Note : `/config-role` n'a pas encore été adapté sur le même schéma que le reste des commandes de config.*

Configuration :
- Le code `/config-level` a été entièrement rework pour en faciliter la lisibilité, nécessaire pour l'arrivée prochaine du gain d'XP en voc
- Ajout d'un bouton "Boosters" à la commande ci-dessus pour configurer le boost d'XP sur les rôles
- La commande `/config-bienvenue` a été retravaillée pour être plus simple à utiliser
- Beaucoup de variables pour les messages d'accueil y ont été ajoutées
- Amélioration du parcours de `config-role` et correction d'un bug
- Les embeds d'arrivée et départ contiennent des infos + utiles
- Implémentation de logs pour les boosts du serveur
- Améliorations des boutons de config

Autre :
- Vous pouvez effacer un salon entier avec `/effacer-salon` (un message de confirmation sera envoyé pour être sûr)
- Il est désormais possible de régler rapidement le temps d'attente entre chaque message d'un salon via `/slowmode`
- Le préfixe du bot est maintenant modifiable avec `/prefixe` (pour les commandes personnalisables et `+dire`)
- Lancement d'une commande `/joke`, propulsée par Blagues API (les blagues du bot Draftbot) !
- Ajout de la commande `/unban` et retour de `/changelog`
- Gestion d'une grosse partie des erreurs retravaillée

### Version 0.6.1 | 17/03/25
Petit patch.

- Poursuite de l'amélioration du gestionnaire d'erreurs sur la même base que précedemment
- Refonte de la commande `/aide` : abandon de la classification par perm et ajout de détails
- Correction d'un bug critique dans la configuration des salons sans XP
- Correction d'un bug critique lorsqu'un salon de logs est supprimé
- Corrections mineures sur les embeds d'arrivée et départ

### Version 0.6.2 | 20/03/25
Dernier correctif avant la màj majeure. Toutes les commandes hors futurs ajouts dans celles-ci et exceptées `/nt-wolf` et `/config-role` sont désormais stables.

- Création d'un `/config` qui rassemble et est amené à remplacer les commandes de config
- Remplacement de la mention et affichage optimisé de `/snipe`
- Des nouvelles variables sont utilisables dans `/config-level`
- Corrections dans la nouvelle gestion d'erreurs
- Correction d'un bug dans `/effacer-membre`
- Autres ajustements

## Version 0.7.0 | 31/03/25
Beaucoup de nouveautés sont apportées par cette màj. D'ailleurs, de celle-ci à la 0.9.0, vous pourrez accéder de + en + simplement à la config. Découvrez aussi le nouveau module Economie, encore plus poussé que sur certains bots grâce aux tâches (sans même être finalisé !). Changement de dernière minute : la fonctionnalité "réactions automatiques" du module Role ne sera mis en place que plus tard par manque de temps.

Nouveau module : Economie (bêta)
- Améliorez toujours plus l'engagement de vos membres via gain de pièces et tâches à compléter
- Nouvelles commandes `/monnaie` pour voir le nb de pièces / tâches et `/modifier-monnaie`
- 2 types de tâches au lancement : X Messages en X jours et X Boosts sur le serveur
- Nouvelle commmande `/donner` pour faire don de ses sous (si activé et possible)
- Nouvelle commande `/boutique` permettant d'y acheter des rôles et articles

Nouvelle fonctionnalité : Profil (bêta)
- Suivez de façon inédite le statut de connexion d'un membre (par ex, connecté il y a 2 min)
- Le statut de connexion peut être masqué pour respecter la confidentialité
- Intégration de stats de jeux avec Brawl Stars au commencement
- Consultez un résumé d'infos du membre sur le serveur

Refonte du module Role
- Ajout de la fonctionnalité "réactions automatiques" au module de Role
- Alignement du fonctionnement du module au reste des configs
- Amélioration de la gestion des rôles auto et temporaires

Autres nouveautés majeures
- Bouton XP Vocal au module level permettant d'y config l'XP gagné
- Suivez le nb total d'invits d'un membre via `/invitations`
- Pré-intégration d'une meilleure confidentialité

Améliorations et autres
- Dépréciation des commandes de configs pour `/config`
- Logs : ajustements dans le bas de page des embeds
- Barre d'XP de `/level` adaptée à la màj Discord

### Version 0.7.1 | 04/04/25
Hotfix et repassage à un rythme de déploiement des mises à jour plus rapide jusqu'à la 0.8.0
- Les pièces sont désormais correctement retirées après achat d'un article de `/boutique`
- Correction d'un bug lors de la première utilisation de la commande `/profil`
- Correction d'un bug rendant impossible le suivi de connexion d'un membre
- Correction d'un bug empêchant de configurer des tâches d'économie
- Correction du message de suivi d'invitations dans `/invitations`
- Correction de plusieurs bugs d'affichage dans la boutique
- Meilleure gestion des réductions dans `/config-economie`
- Les jeux NT deviennent `/quick-word` et `/quiz-party`
- Corrections de textes dans les modaux
- *Note : le bouton "Retour" de "Réductions" fonctionne mais est temporairement à la mauvaise place (volontairement). Par ailleurs, de nouveaux types de tâches ont été ajoutés mais uniquement à titre indicatif. Ils pourront donc s'afficher dans les tâches à effectuer sans fonctionner comme prévu si vous les ajoutez.*

### Version 0.7.2 | 07/04/25
Meilleure expérience utilisateur en particulier sur les commandes récentes
- Amélioration de l'agencement des différentes sections du `/config-economie` et ajout d'infos
- Simplification des suppressions d'articles, boosters et réductions de `/config-economie`
- Désormais, désactiver la config désactive aussi la commande `/boutique`
- Amélioration du parcours d'ajout d'un booster dans `/config-economie`
- Meilleur résumé d'un utilisateur dans la commande `/profil`
- Ajustement de la gestion des dates (dans logs et snipe)
- Correction du bouton "Retour" des "Réductions"

### Version 0.7.3 | 14/04/25
- Suppression de l'obligation d'entrer un lien Spotify pour modifier le profil
- Les réductions sont désormais chargées sur les articles instantanément
- Correction d'un bug rare empêchant d'accéder à `/boutique`
- Correction d'un bug occasionnel sur la commande `/pp`
- Limitation à 5 `/rappel-prive` par utilisateur
- Limitation à 10 `/rappel-serv` par serveur
- Modif de la numérotation des versions
- Autres corrections mineures

### Version 0.7.4 | 17/04/25
- Les `/invitations` d'un membre sont maintenant comptées de 2 façons : le nombre de membres sur le serveur invités par quelqu'un et le nombre d'invitations au total (inclut donc les membres qui ont quitté le serveur)
- Nouvelle fonctionnalité : à la création d'un article, on peut rentrer une quantité d'articles disponibles à l'achat
- Nouveau bouton "Preuve d'achat" dans `/config-economie` : envoie une copie d'achat en MP / dans un salon
- Un membre concerné par l'enregistrement d'un message supprimé dans `/snipe` peut désormais l'enlever
- Le résumé du `/profil` est désormais intelligent : il s'adapte à la configuration du bot sur le serveur
- Regroupement de la boutique et des réductions en une seule catégorie sur `/config-economie`
- De même pour les boosters qui passent dans l'onglet de gestion de la monnaie
- Amélioration du parcours d'achat d'un article dans la boutique
- Modernisation de l'affichage de la commande `/snipe`
- Autres corrections mineures

### Version 0.7.5-rc | 18/04/25
Une panne est en cours au niveau du serveur externe. En conséquence, une version non finalisée provenant du bot de dév a été déployée jusqu'à retour du serveur.
- Redéploiement du bot, données conservées et adaptation du code en conséquence
- Amélioration de l'expérience utilisateur dans l'entiéreté du module Level
- Regroupement de différentes sections du `/config-level`

### Version 0.7.6 | 23/04/25
Le fournisseur du serveur a rétabli les services. Le développement du site a commencé en parallèle, ainsi que le dév de la 0.8.0.
- Les fonctionnalités de `/config-role` sont désormais séparées en 2 commandes distinctes : `/role-auto` et `/role-temp`
- Supp des messages dans `/snipe` est désormais réservé aux perms "Admin" ou "Gérer les messages"
- Multiples ajustements sur la commande `/spam` avec une meilleure intégration
- Correction d'erreurs dans la BDD sur `/config-logs` et `/config-level`
- Correction d'un bug empêchant l'affichage d'un gif avec `/bim`
- Correction d'un message d'erreur dans `/snipe`
- Version V1 du système de protection de Nity :
- → Regroupement des embeds de logs
- → File d'attente via `/spam`
- → Et bcp + non dévoilé

### Version 0.7.7 | 05/05/25
Hotifx / amélioration de quelques logs.
- Ajout des auteurs dans certains types de logs
- Amélioration du log de pseudo modifié
- Correction du log de rôle modifié
- Autres corrections de bugs

## Version 0.8.0 | 19/05/25
Cette màj est celle ayant pris le plus de temps à développer depuis la création du bot. En résumé, elle apporte la version finale du module d'économie, achève la cohérence entre les commandes de config et propose plusieurs grosses nouveautés.

Refonte de la gestion des configurations :
- Désormais, toutes les commandes de config sont centralisées sur la commande `/config`
- Le module de configuration de l'économie a été entièrement revu et n'est plus en bêta, étant grandement simplifié
- Refonte du module de Reputation et nouvelle commande `/note` permettant de donner, retirer (ou aucun des deux) le nombre de points voulu dans les limites de la config du serveur
- La commande de configuration de l'économie a servi de base aux autres modules de configuration pour proposer une logique et une expérience similaire
- `/role-auto` et `/role-temp` disposent désormais d'un parcours similaire aux commandes de configuration

Nouveau module : Anniversaire (bêta) !
- Configurez l'annonce et un rôle offert temporairement via le `/config`, Module Anniversaire
- Accédez aux 25 prochains anniversaires via la commande `/anniversaire`
- Un tout nouveau système de navigation est utilisée dans cette commande et sera progressivement deployée dans d'autres commandes
- Modifiez votre anniversaire partout ou sur un serveur et entrez votre date d'anniv avec ou sans l'année avec `/anniversaire-modif`

Refonte de la commande `/profil` :
- Des statistiques sont désormais disponibles pour le jeu Valorant !
- Le statut de connexion est désormais activé sur un utilisateur dès que quelqu'un effectue la commande sur ce dernier
- Le résumé personnalisé a été amélioré avec plus d'infos et une meilleure logique
- La description a été supprimée du profil, jugée inutile

Plus de nouveautés majeures :
- Ajoutez des rôles réactions ou proposez ces rôles via une liste avec le tout nouveau `/role-react` !
- Nouveau module de log "Modération" (pour l'instant, seules les commandes d'effacement sont concernées)
- 2 nouveaux types de tâches sont disponibles à l'ajout sur `/config-economie`
- Une nouvelle commande `/emoji` permet d'envoyer une image de l'émoji mentionné

Autres améliorations et corrections :
- Passage à 3 rôles max. attribués automatiquement à l'arrivée d'un membre via `/role-auto` (au lieu d'1)
- Correction d'un bug critique dans `/config-reputation` apporté par une récente màj
- Correction de la pagination dans les commandes `/boutique` et `/reputation`
- Correction d'un bug dans le log de modif. de message
- Améliorations QoL dans `/snipe` et `/spam`
- Suppression de `/note-positive` et `/note-negative` → remplacés par `/note`
- Suppression de `/crush` → astuce : utilisez `/roulette` avec la raison "mon crush est"

### Version 0.8.2 | 26/05/25
Améliorations dans le module de Réputation, dans la commande `/effacer-membre` et hotfix.

Simplification de l'interface du module de Réputation :
- Réduction du nombre de boutons et ajout de parcours similaires aux autres commandes de configurations
- L'utilisateur est mieux informé sur l'usage de cette configuration et le bot gère mieux la configuration
- Possibilité de diversifier à l'avenir les sanctions pour la perte de points

Optimisation de la commande `/effacer-membre` :
- Traitement plus efficace de la suppression des messages avec une vitesse multipliée par deux sur les gros serveurs
- Un suivi de la progression s'affiche permettant de savoir quand est-ce que le bot aura fini d'effacer
- Le log a été ajusté en conséquence

Correction de bugs et ajustements :
- Amélioration du parcours d'ajout d'un rôle dans le module Level et correction d'infos
- Correction d'un doublon dans le parcours de création de la tâche d'économie "Envoyer des messages dans un salon"
- Correction d'un bug se produisant lorsque le slowmode de la commande `/config` était atteint

### Version 0.8.3 | 31/05/25
Améliorations internes et hotfix. Les màjs risquent désormais sortir de façon plus espacée, de façon à limiter le nombre de bugs sur les futures fonctionnalités développées.
- Réagencements assez lourds du code, malgré plusieurs tests il se peut que des bugs se soient glissés
- Correction de la vitesse de traitement des salons dans `/effacer-membre` : 2 > 3 salons / chaque seconde > 3 secondes
- Autres corrections mineures et ajustements
- Report : ajout des stats pour Valorant dans la commande `/profil`

### Version 0.8.4 | 23/06/25
**Amélioration de la gestion des rôles temporaires**
- Intégration d'une pagination à la commande (5 rôles temporaires actifs par page)
- Il est maintenant possible d'ajouter plusieurs rôles temporaires à un membre
- L'entrée d'une date et la suppression d'un rôle temporaire sont désormais plus pratiques !

**Role react n'est plus en bêta !**
- Il n'est plus possible de configurer des menus déroulants pour choisir des rôles
- L'entièreté de l'embed créé par la configuration d'un role react est désormais personnalisable

**Corrections**
- Stabilisation de diverses fonctions utilisées dans la commande `/role-temp` et ajout d'infos
- Améliorations QoL dans les commandes de modération

### Version 0.8.5 | 30/06/25
**Suivi des messages supprimés dans /snipe**
- On peut maintenant voir les messages supprimés sur tout le serveur, peu importe le salon et le membre sans utiliser de variable. Les variables utilisables ont été revues : vous pouvez choisir de voir les messages supprimés d'un seul membre (peu importe le salon), d'un seul salon (peu importe le membre), et les messages supps d'un seul membre dans un seul salon.
- La commande utilise désormais le nouveau système de navigation dans les pages et 50 messages supprimés sont affichés au total, au lieu de 20 actuellement (ce qui équivaut à 10 pages au lieu de 4).
- Une prochaine mise à jour changera la façon dont les messages supprimés seront conservés et la façon dont ils pourront être retirés de la base de données. Une commande à part est à l'étude, permettant de les retirer de façon plus précise.

**Module de logs**
- Des nouveaux logs dans le sous module de logs vocaux ont été ajoutés de façon expérimentale, permettant de savoir qui a déplacé un membre dans un autre salon vocal, et qui a déconnecté un membre d'un salon vocal. Bien que ce soit en test, cela n'affectera pas le fonctionnement habituel des logs. Il se peut simplement que ces nouveaux logs n'aparaissent pas toujours dû à des limitations de Discord.
- Les couleurs des embeds suivent désormais un schéma plus logique et compréhensible pour l'utilisateur. Les délais de regroupement des embeds ont été rallongés et l'embed du message modifié est plus clair.

**Commande /level du module de Level**
- Grosse refonte visuelle : l'embed affiche désormais une image générant toutes les infos du membre en plus de la barre de progression, remplaçant l'ancienne barre de progression !

**Améliorations QoL**
- Dans le module de Bienvenue, le nombre de fois qu'un membre a rejoint le serveur devient désormais une variable facultative qui pourra être utilisée dans la description d'un message d'arrivée et de départ. L'ID du membre remplace cette donnée dans le bas de page de l'embed d'arrivée.
- Les couleurs des boutons de navigation ont été ajustées pour mieux les distinguer. Par ailleurs, l'expansion du nouveau système de navigation dans les commandes récentes est prévu dès la 0.8.6.

**Corrections de bugs**
- Correction d'une incohérence dans la commande /bim.

### Version 0.8.7 | 22/02/26
Reprise du dév avec environ 2 MàJs par mois. Améliorations apportées aux modules les plus importants : Level, Logs et Bienvenue. Ce ne sera pas précisé ici mais un gros nombre de bugs a été corrigé et il y a eu pas mal d'ajustements !

- Pour le module Level, ajout de la possibilité d'ajuster la fréquence de notification du passage d'un niveau. Tous les niveaux, tous les x niveaux ou tous les paliers
- Redesign des logs pour qu'on comprenne plus facilement l'importance d'un log sur un coup d'oeil et pour qu'ils soient plus cohérents entre eux
- Il est désormais possible d'utiliser Nity pour répondre directement à un message via les "applications"
- Intégration d'une file d'attente similaire à celle des logs pour le module de Bienvenue
- Le bot s'adapte mieux aux salons supprimés dans divers modules

## Version 0.9.0 | 08/03/26
C'est la dernière grosse màj avant le passage à une version stable. Beaucoup de changements ont été faits pour avoir une expérience plus cohérente à travers le bot. Y a aussi pas mal de nouveautés, les fonctionnalités essentielles sont donc au complet !

**Modérer devient plus simple avec Nity**
- Nouveau `/config Modération`, avec une toute nouvelle interface plus facile à prendre en main. Les autres commandes de configs bénéficieront d'une refonte dans les prochains mois basée sur cette interface.
- Cette config sert à :
1. Laisser le bot avertir automatiquement des membres lorsqu'il détecte une infraction (Nity AutoMod)
2. Créer des paliers à partir desquels des sanctions lourdes sont appliquées (mute / kick / ban)
3. Ajouter des rôles protégés des commandes de modération ainsi que de Nity
- AutoMod inclut au lancement 5 types de protection : "Mentions", "Invitations", "Majuscules", "Emojis" et "Mots interdits"

**Vos membres peuvent désormais signaler un membre sans attendre un modérateur**
- Nouveau `/config Signalement`, permettant de :
1. Activer / désactiver la possibilité de signaler un membre
2. Choisir un salon où seront analysés les signalements
3. Rendre anonyme les signalements
- Il est possible de signaler un message en faisant un clic droit (PC) / en restant appuyé dessus (mobile) puis en allant dans "Applications". Vous y trouverez le bouton `Signaler ce message à un admin` avec le logo de Nity.
- Il est aussi possible d'utiliser la commande `/signaler` pour signaler un membre avec un motif

**La fonctionnalité Snipe devient moins intrusive**
- Nouveau `/config Snipe` , il permet :
1. D'activer ou désactiver la commande `/snipe` (elle est désormais désactivée par défaut)
2. De laisser gérer qui peut supprimer des messages enregistrés dans la commande¹
3. D'effacer tous les messages supps actuellement enregistrés¹
4. D'exclure des rôles et des salons de l'enregistrement
- Il est désormais plus pratique de supprimer des messages dans la commande `/snipe`.
- ¹Disponible dans la 0.9.1

**Organisez des concours pour votre serveur**
- Avec `/giveaway`, vous pouvez créer des concours entièrement personnalisables !
1. Entrez la récompense à gagner et une description de celle-ci
2. Choississez un large nombre de gagnants possibles (max 50)
3. Vous avez 30 jours pour reroll (relancer) un concours

**Découvrez des nouvelles commandes funs**
- Nouveau jeu `/mot-mystère`, trouvez un mot en 6 essais et jouable en solo.
- Nouvelle commande fun `/boule-mystère` pour avoir la réponse à une question.
- Ajout de 50 questions à `/quiz-party`

**Et plusieurs fonctionnalités revues**
- `/config Economie` se dote de nouveaux types d'articles à utiliser :
1. Article auto : le message contenant le cadeau est directement envoyé en MP
2. Article item : l'article est stocké dans l'inventaire de la personne
- L'interface de gestion de la boutique a aussi été amélioré pour qu'elle soit moins chargée !
- Il est plus simple de modifier son `/profil`. L'anniversaire y est désormais affiché, l'agencement des infos du profil a été revu pour que ce soit mieux présenté et vous pouvez consulter les items que vous avez acheté dans la boutique de votre serveur.
- Vous pouvez (enfin) activer ou désactiver tous les modules de logs d'un coup.

Bugs corrigés
- L'alignement était incorrect dans la commande `/snipe` depuis la restauration du bot
- Le gain d'XP pendant un voc n'est plus affecté par un redémarrage du bot
- Le niveau n'était pas correctement mis à jour dans un cas précis
- Autres améliorations QoL (`/liste-anniv`, `/nouvel-anniv`, `/aide`)

### Version 0.9.1 | 15/03/26
Diverses améliorations QoL ont été apportées et `/role-auto` dispose d'une nouvelle fonctionnalité.

**Commandes de gestion de rôles**
- Vous pouvez choisir entre deux conditions pour que le bot attribue un rôle automatiquement via `/role-auto`. Selon le nombre de messages envoyés sur une période donnée, et comme avant si la personne vient de rejoindre le serveur.
- L'interface entre `/role-auto`, `/role-temp` et `/role-react` est désormais bcp plus cohérente
- Le parcours d'ajout de roles react a été revu, il est beaucoup plus simple
- La présentation de l'embed d'un rôle react a été améliorée

**Config de Snipe**
- Vous pouvez gérer qui peut supprimer des messages enregistrés dans la commande `/snipe`
- Vous pouvez vider en deux clics tous les messages enregistrés dans la commande `/snipe`

**Correction de bugs**
- Correction du système anti-spam de Nity pour les logs (le système ne s'activait pas comme il devait dans certains cas). Il est par contre maintenant plus "sévère" en cas d'abus du nombre de logs créés.
- Allègement du code et réduction des temps de chargement dans différentes sections de `/config Modération`
- Correction du log de membre déplacé d'un salon vocal pour qu'il soit plus clair
- Ajustement des limites de rôles et salons ignorés dans `/config Modération`
- Correction d'une donnée incorrecte affichée dans `/effacer-membre`
- Correction d'un log de rôle redondant

## Version 1.0.0 | 29/03/26
La première version stable de Nity est disponible et le bot est officiellement vérifié par Discord !! Retrouvez-y la refonte des commandes de config, avec une tonne de modifs dans `/config Level` et `/config Economie`, ainsi que pas mal d'opti et de changements QoL. Bref, tout a été repensé pour que le bot soit le plus "user-friendly" possible (+ que certains bots très populaires...). Enfin, beaucoup d'ajustements et de bugs corrigés ne sont pas notés ici.

### Nouveauté : le module de configuration Captcha (en bêta) !
Protégez votre serveur contre les bots grâce à la nouvelle commande `/config Captcha`. Cette commande permet de configurer la façon dont le message de vérification agira. Ce message sera envoyé avec un captcha (comme le nom de la config l'indique) dans un embed éphémère (ça veut dire qu'il sera vu uniquement par la personne qui se fait vérifier) avec une série de chiffres à retaper pour obtenir un rôle donnant accès au reste du serveur.
- Ajoutez un rôle obstensible en validant le captcha (à l'avenir, ce rôle se configurera automatiquement sur le serveur, limitant 
l'intervention de l'utilisateur).
- Ajustez le "niveau" de sécurité du captcha :
1. Captcha systématique, peu importe l'ancienneté du compte.
2. Captcha uniquement pour les comptes de moins d'un an (par défaut).
3. Captcha uniquement pour les comptes très récents (de moins d'un mois).
- Il sera possible de définir un nombre maximum de tentatives et un délai avant expulsion dans une prochaine mise à jour (qui arrivera très vite).

### Refonte et amélioration de différents modules de configuration
**- Personnalisez de fond en comble le gain d'XP et obtenez plus d'infos utiles.**
1. L'XP textuel peut être fixé à 0 pour que les membres ne puissent pas gagner d'XP via les messages. Aussi, vous pouvez fixer une limite de messages par jour avant que le bot ne prenne plus en compte les messages jusqu'au lendemain. Enfin, vous pouvez modifier le nombre de secondes qu'il faut pour que le prochain message soit pris en compte par le gain d'XP (minimum 5 secondes, par défaut ça reste 15 secondes).
2. Vous pouvez réinitialiser les récompenses plutôt que de devoir les supprimer 1 par 1 si nécessaire et la date de dernière réinitialisation s'affiche dans le sous menu "Plus d'options".
3. L'XP vocal est maintenant activé par défaut. Il peut être fixé à 0 pour que les membres ne puissent pas gagner d'XP en voc.
4. Plus de données sont présentées dans le bouton "Plus d'infos" de la commande `/level` et l'affichage a été revu.
5. Vous pouvez ajouter des récompenses d'argent lié au `/config Economie` si ce dernier est activé !

**- Une boutique mieux agencée et des jeux pour vos membres.**
1. La commande `/boutique` a été revue : chaque article est mieux mis en avant, avec 5 articles par page et une navigation sur le même schéma que d'autres commandes. Vous pouvez consulter les réductions auxquelles vous avez le droit et il faut naviguer dans les pages pour acheter des articles.
2. Deux commandes de hasard liés à l'économie sont disponibles ! Le premier s'appelle `/pari`. Chaque membre a 1 chance sur 3 de gagner. S'il gagne, il remporte le double de sa mise. S'il perd, sa mise se volatilise...
3. La deuxième commande s'appelle `/voler`. Le membre peut essayer de voler les pièces de qlqn d'autre. Si la personne volée se situe dans le top 50 des membres avec le plus de pièces, alors le voleur pourra tenter de récupérer 5% des pièces avec une chance sur deux. Si ça rate, le voleur donnera 15% de ses pièces à la personne qu'il a tenté de voler. Si la personne volée se situe en-dessous du top 50, alors le voleur pourra tenter de récupérer 10% des pièces avec une chance sur deux. Si ça rate, le voleur donnera 10% de ses pièces à la personne qu'il a tenté de voler. Ce jeu pourra être ajusté à l'avenir et tout comme le premier, il sera bientôt personnalisable.
4. Le sous menu des tâches dans la config est donc renommé et accueille les jeux ! Pour l'instant, il est simplement possible d'activer / désactiver chaque jeu.
5. Vous pouvez réinitialiser tous les articles et les tâches d'un coup sans avoir à les supprimer 1 par 1.
6. Vous pouvez modifier des articles plutôt que de les supprimer pour les refaire.

### N'importe qui peut réussir à configurer Nity avec ConfigV3
- Le fonctionnement même des commandes a été revu en profondeur. Passer d'une config à l'autre paraît beaucoup plus logique puisqu'elles sont présentées pratiquement de la même façon !
- Les boutons ont été remplacés par des listes de choix, c'est beaucoup plus propre.
- Les parcours de configurations (ajout de salons, rôles, choix à faire, etc) ont été simplifiés.
1.  Des "modals" (qu'on peut traduire par formulaire) ont remplacé ces parcours. C'est facile à utiliser et rapide à modifier. Utile par exemple pour changer un message d'annonce.
2. Des listes de choix permettent de naviguer ou taper directement dans une barre de recherche le salon / rôle / membre à trouver.
- Les commandes expirent désormais toutes au bout de 10 minutes d'inactivité. Elles s'auto suppriment donc à la fin.
- Les embeds des différentes configs sont cohérents et sont plus compacts, permettant de retrouver d'un coup d'oeil pas mal d'infos.
- D'autres améliorations ont été apportées et des bugs ont été corrigés. Les mêmes limites sont aussi fixées un peu partout pour éviter de surcharger la BDD et en prévision du futur abonnement. Elles sont cependant très larges et ne limiteront pas 99% des serveurs sur un usage classique.

**Et du renouveau un peu partout finalement**
- Intégration de Discord AutoMod au sein de Nity ! La première fonctionnalité de `/config Modération` à en profiter est la détection des mentions excessives. Le message contenant les mentions en trop sera instantanément bloqué avant même qu'il soit envoyé !
- Nouveau module de logs : "Effacement des messages" (pour les commandes en `/effacer-x`) auparavant intégré au module de logs de Modération. D'autres modules sont renommés pour l'occasion, facilitant leur compréhension.
- Vous pouvez modifier le délai entre chaque note sur un membre dans la `/config Reputation`. Les commandes associées à ce module ont été revues pour donner plus d'infos.
- Ajout de nouveaux logs vocaux (expérimental) : Mise en sourdine / membre rendu muet dans un salon vocal.
- Les stats Valorant de la commande `/profil` ont été amélioré et ne sont plus en bêta.
- Il est plus simple d'enregistrer son anniversaire et la logique a été revue.

**Renforcement du code du bot et optimisation des commandes**
- Dès le déploiement de cette mise à jour, il ne sera plus possible de suivre le statut de connexion des membres depuis la commande `/profil`. Même s'il était possible de masquer son statut, les options étaient de désactiver le suivi de connexion par défaut (perd tout son intérêt) ou de l'activer par défaut (assez limite comme pratique). De plus, cela demandait entre 2 à 3 fois plus de ressources pour le bot, uniquement pour cette fonctionnalité. Par contre y a bcp de choses de prévu à l'inverse prochainement...
- Bcp plus de commandes n'expirent plus après un redémarrage de Nity, en voici les nouvelles : `/level`, `/monnaie`, `/boutique`, `/snipe`, `/reputation`, `/profil`, `/liste-anniv`, `/liste-warn`, `/top-level` et `/top-reputation` !
- Le système de navigation a été standardisé à travers l'entièreté des commandes pour s'adapter plus facilement à celui-ci.
- Réduction assez conséquente de la charge du bot + optimisation avec la BDD, adaptation du code aux changements de l'API Discord et allègement des fichiers du bot.

Correction de bugs
- Ajout d'une erreur lorsque le nombre entré pour le prix ou la quantité d'un article est trop grand.
- Il n'est plus possible d'acheter un article rôle si le membre possède déjà le rôle associé.
- Correction d'un bug d'affichage dans le log de modifs générales d'un salon (textuel).
- Correction d'un doublon dans la commande `/reputation`.

## Version 1.1.0 | 02/04/26
- Nouveauté de cette màj, les soundboards par message ! En bêta, cette fonctionnalité permet d'ajouter jusqu'à 10 sons (et 20 sons avec le futur abonnement Nity+) sur un serveur pour les utiliser quand vous voulez dans un salon textuel.
- Divers ajustements sont apportés à la commande `/effacer-membre`, le plus important étant qu'elle voit son temps de traitement ralenti pour supporter + d'utilisateurs du bot. L'abonnement permettra de garder sa vitesse actuelle.
- Nity+ permettra d'ici cet été d'accéder à des commandes améliorées, sans jamais pour autant trop limiter les utilisateurs gratuits (aucune commande exclusive en dehors de celles en développement, des fonctionnalités complètes sans payer et des limites assez larges pour 99% des petites ou moyennes communautés sur une utilisation normale de Nity !).
- Enfin, divers ajustements ont été apporté aux commandes. Plus de détails ci-dessous ↓

**➕ Les ajouts**
- Nouvelles commandes `/ajouter-son` et `/retirer-son` (bêta). Ces deux commandes permettent d'ajouter (et retirer) des fichiers de max 10sec réutilisables par message, comme mentionné plus haut.
- Dans la même lignée, une nouvelle commande `/soundboard` (bêta) fait son apparition. C'est cette commande qui permettra d'envoyer un son par message ! Elle se met à jour automatiquement à chaque ajout ou retrait d'un fichier.

**ℹ️ Les changements**
- Dans `/effacer-membre` :
1. 1000 messages sont désormais traités par salon au lieu de 500 et une file d'attente permettra de faire plusieurs commandes via l'abo. Sans abonnement, la durée de fin estimée est précisée lorsqu'un utilisateur essaie de refaire la commande alors qu'une opération est déjà en cours.
2. Ajout d'un bouton permettant d'annuler la suppression des messages pas encore effacés
3. Correction de la donnée "durée totale" incorrecte.
- Correction d'une occurence inutile du footer "modif le..." lorsqu'un `/embed` est effectué.
- Nouvelle icône de chargement dans les différents embeds utilisant ce système.
- Et j'ai ajouté pas mal d'infos dans le `/aide` (notamment sur Nity+...) !

**👋 Et on dit au revoir à... :(**
- La commande `/spam` est désormais limitée à un usage très restreint sur le serveur support et sera supprimée d'ici peu de temps conformément aux conditions d'utilisation de Discord (dsl !!).

### Version 1.1.1 | 05/04/26
La commande de config du captcha n'est plus en bêta et d'autres modifs utiles ont été faites.
- Un parcours d'ajout du rôle obtenu via le captcha a été ajouté, c'est plus simple à gérer dans le code du bot comme pour l'utilisateur de la commande.
- Il est maintenant possible de laisser le bot configurer le rôle sur le serveur pour qu'il ne soit plus possible de voir ou d'écrire dans les salons tant que le captcha n'a pas été validé.
- Vous pouvez dire au bot d'ignorer des catégories / salons dans la config du rôle de captcha pour ne pas casser vos perms déjà config.
- Définissez un nombre max de tentatives et un délai avant expulsion du membre par le bot (pas obligatoire).
- Vous pouvez changer la description du panel, utile pour un usage différent du rôle attribué par le captcha.
- Amélioration de la fonctionnalité "Mots interdits" au sein du module de `/config Modération`. Cette dernière pourra regarder si l'utilisateur a essayé d'envoyer un mot interdit sur le serveur en plusieurs messages au lieu d'un seul.

Exemple : un des mots interdits sur le serveur est "tg". Le 1er message envoyé par un membre est "t", le 2ème message est "g". Avant cette màj, il fallait que le membre envoie tout dans un message pour se faire sanctionner, désormais il n'est plus possible de contourner cela !
- La commande `/mute-temp` est supprimée. A la place, la commande `/mute` permet désormais via une intégration native d'exclure quelqu'un (ça rend muet, ça expulse pas le membre) pendant max 28 jours. En conséquence, le rôle "Nity - Mute" n'existe plus et les logs de mute / unmute ont été ajustés.
- Suite à la refonte des configs, il n'était plus possible dans le message d'arrivée du module de Bienvenue de mentionner des salons et rôles. C'est de nouveau le cas.
- Les logs de modification d'un salon / d'une catégorie ainsi que les modifications de perms reprennent bien en compte le type de salon / catégorie.
- La date de fin d'un mute est affichée plus explicitement.

### Version 1.1.2 | 12/04/26
**🔨 Nity AutoMod**
- Deux nouvelles détections d'infractions sont ajoutées !
1. Anti-raid : protégez votre serveur contre les afflux de membres malveillants. En cas de spam coordonné, le bot sanctionnera et mettra automatiquement en place des mesures de protection configurables. Cette fonctionnalité, bien que stable, est amenée à évoluer pour plus de sécurité.
2. Liens frauduleux : tout lien considéré comme suspicieux sera modéré par le bot selon sa propre base de données.
- Correction critique de la détection des mots interdits dans un cas permettant d'éviter de modérer un message sûr.
- La présentation des sous menus a été revue (les boutons sont remplacés par une liste de choix).
- L'agencement des détections d'infractions a été revu pour être plus compact et plus lisible.

**📰 Module de logs**
- Nity prend dorénavant en charge toutes les actions de modération natives (exclusion, expulsion, ban) effectués via l'interface de Discord.
- L'agencement des modules de logs dans le sous menu dédié a été revu sur la même base que le sous menu de détection d'infractions.

**Autres changements**
- Le bouton des commandes `/top-level` et `/top-reputation` qui permettait de voir son positionnement VS le 1er du classement est remplacé par un bouton permettant d'accéder directement à la page où se trouve le membre qui a cliqué sur le bouton.
- Changement de nom des commandes : le `/warn` devient `/avertir` et `/liste-warn` devient `/avertissements`.
- La description de certains logs a encore été améliorée pour rendre le tout plus "aéré" (plus facile à lire).

### Version 1.1.3 | 19/04/26
Les mises à jour sont désormais ralenties jusqu'à début juin et toute correction de bug ne se fera qu'au rythme habituel des màjs.

**🔔 Refonte des commandes de rappel**
- Elles utilisent la nouvelle logique du bot déjà adoptée à partir de la 1.0.0 dans beaucoup de commandes : elles expirent, utilisent le nouveau système de pagination du bot et les boutons ont été remplacés par des sélecteurs.
- Il est possible de choisir entre deux nouvelles options : un rappel via un message simple ou bien un rappel dans un embed.
- Un tout nouveau parcours pour créer des rappels est disponible. Pour que ce soit plus rapide à configurer, plus simple à utiliser et ça facilite l'ajout d'un rappel long.
- Vous pouvez maintenant modifier des rappels et plus d'infos sont affichées.
- Il est possible de supprimer n'importe quel rappel, plutôt que le rappel le plus proche.
- Les limites ont été mises à jour, vous pouvez avoir 50 rappels privés ainsi que 50 rappels par serveur !

**🎭 Mise à jour des commandes de rôle et toute nouvelle gestion des rôles temporaires**
- Dans `/role-temp`, le nouveau système de suppression permet de mieux voir les rôles temporaires pour les supprimer plus efficacement.
- Dans `/role-temp` le menu principal est plus compact, permettant une meilleure lisibilité de la config.
- Une meilleure gestion de l'expiration (après 2 à 10 minutes d'inactivité) des commandes a été intégré dans tous les `/role-...`. 
- Les annulations de "suppression de rôle" / "parcours d'ajout de rôle" amènent désormais au menu précédent, comme c'était déjà le cas partout où un parcours de config est en place. Un bouton (à la place du mot `cancel`) et toute inactivité détectée permet d'annuler l'ajout /suppression.

**👋 Ajustement du module de Bienvenue, renommé "Arrivée & Départ"**
- Révision des infos affichées dans le menu principal.
- Révision des variables affichées dans les sous menus.

### Version 1.1.4 | 26/04/26
🐞 Correction de bugs
- Critique : les rappels serveur n'étaient modifiables / supprimables que par l'auteur du rappel. Tous les membres ayant la permission de le faire pourront donc désormais faire de même pour des rappels qu'ils n'ont pas créé.
- Corrextion de texte pour les réductions d'articles.
