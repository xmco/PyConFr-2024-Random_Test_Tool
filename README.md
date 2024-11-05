# PyConFR 2024

Ce dépôt rassemble les ressources présentées par Antoine R. lors de la PyConFR 2024, à Strasbourg.

## Dédé ! Des dés aux données : analyse de tirages aléatoires avec l’outil Random Test Tool

Jeux en ligne, transactions sécurisées ou encore génération de mots de passe, les nombres aléatoires sont partout. Face à ces cas d’usage sur des fonctionnalités souvent considérées comme critiques, comment s’assurer que les données aléatoires générées sont de qualité suffisante ?

Cette conférence sera articulée autour de l’audit sécurité d’un jeu (fictif) de poker en ligne.

Dans un premier temps, nous rappellerons brièvement ce qu’est une donnée aléatoire.

Dans un second temps, nous effectuerons une analyse statistique des tirages de cartes sur cette application. Vous découvrirez ainsi un outil Python permettant d’évaluer les sorties de générateurs aléatoires : Random Test Tool (RTT).

Suite à cette revue de données générées, nous vous présenterons une brève analyse du code de l’application vulnérable.

Enfin, nous listerons les écueils à éviter et les bonnes pratiques à mettre en œuvre lors de l’utilisation de générateurs aléatoires au sein des applications.


## Ressources 

* Lien du Talk : [https://www.pycon.fr/2024/fr/talks/short-talk.html#talk-NR88BG](https://www.pycon.fr/2024/fr/talks/short-talk.html#talk-NR88BG)
* Outil Random Test Tool (RTT) : [https://github.com/xmco/random_test_tool](https://github.com/xmco/random_test_tool)
* Support de présentation : [XMCO-PYCONFR2024-RANDOM_TEST_TOOL-0-2024-10-V1.0-DP.pdf](XMCO-PYCONFR2024-RANDOM_TEST_TOOL-0-2024-10-V1.0-DP.pdf)
* Vidéo 1 - Jeu du Poker : 
![XMCO-PYCONFR2024-RANDOM_TEST_TOOL-1-POKER-2024-10-V1.0-DP.gif](XMCO-PYCONFR2024-RANDOM_TEST_TOOL-1-POKER-2024-10-V1.0-DP.gif)
* Vidéo 2 - Lancement RTT  : 
![XMCO-PYCONFR2024-RANDOM_TEST_TOOL-2-RTT_LANCEMENT-2024-10-V1.0-DP.gif](XMCO-PYCONFR2024-RANDOM_TEST_TOOL-2-RTT_LANCEMENT-2024-10-V1.0-DP.gif)
* Vidéo 3 - Résultats RTT : 
![XMCO-PYCONFR2024-RANDOM_TEST_TOOL-3-RTT_RESULTATS-2024-10-V1.0-DP.gif](XMCO-PYCONFR2024-RANDOM_TEST_TOOL-3-RTT_RESULTATS-2024-10-V1.0-DP.gif)
* Vidéo 4 - Prédiction cartes : 
![XMCO-PYCONFR2024-RANDOM_TEST_TOOL-4-RTT_PREDICTION-2024-10-V1.0-DP.gif](XMCO-PYCONFR2024-RANDOM_TEST_TOOL-4-RTT_PREDICTION-2024-10-V1.0-DP.gif)
