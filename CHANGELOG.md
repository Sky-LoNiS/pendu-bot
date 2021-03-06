# A faire
- Ajouts d'images au lieu de textes (compatibilitée mobile)
- Mise en place d'une base de donnée MySQL
- Modifier commande de lancement pour rediriger les erreurs dans un fichier

# 0.7.0
*(27/10/2018) 19H30*
- Modification de `p!valWord` en `p!mod` pour plus de cohérence
- Modification de `p!mod all` en `p!mod show` pour plus de cohérence
- Modification des informations données par `p!mod show`
- Ajout de `p!mod delete [ID]` pour suprimer un mot proposé
- Commande `p!ping` renvoit maintenant un ping arrondie à l'entier

# 0.6.1
*(25/10/2018) 20H50*
- Correction d'une faille de sécuritée
- Possibilité de Ping, Help et word en MP
- Ajout de la commande `p!shutdown` pour l'administrateur
- Ajout d'un log de fermeture du bot

## Fonctionnalitées
- Ajout de la commande `p!word` pour proposer un mot
- Ajout de la commande `p!valWord [all/modify/valide]` pour valalider ou non les mots
- Ajout du fichier `motEnAttente.json` contenant les mots en attente de validation
- Modification du help en conséquence
- Modification du nom du fichier

## Correction
- Commande ping : utilisation de `client.ping`
- Ajout des lettres déja testés : reset la variable

# 0.5.0
*(25/10/2018) 12H50*
- Ajout de la commande de ping
- Ajout numero de version dans le log
- Liste des lettres et mots déjà essayés

# 0.4.0
*(23/10/2018) 14H30*
- Utilisation d'embeb pour toutes les réponses complexes du bot
- Ajout mode normal/mode difficile (Normal première et dernière lettre/Hard juste -). Utilisation `p!start (NORMAL/HARD) (mot)`
- Ajout du nombre d'erreurs restantes et le nombre d'essais à la fin

# 0.3.0
*(22/10/2018) 21H20*
- Modification de la commande `try` pour essayer de deviner un mot a la place d'une lettre. Nouvelle utilisation `p!try (mot/lettre)`
- Modification du texte pour une meilleure mise en page et prise en compte du préfix
- Modification du `help`

# 0.2.0
- Ajout du fichier `config` pour faciliter la configuration
- Mise en place d'un fichier de log contenant les connexions à Discord, les débuts et les fins de parties
- Ajout de la commande `help`
- Ajout d'un jeu sous le nom du bot
- Ajout des fichiers sur Github

# 0.1.0
- Premiere version du bot
- Commandes p!start, p!try
