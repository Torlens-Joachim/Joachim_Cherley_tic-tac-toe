# Tic-Tac-Toe TP

Ce workflow nous permet d'automatiser le processus de construction, test et déploiement.

# Avantages:

Automatisation complète: Le pipeline gère l'ensemble du processus, de la construction à la livraison, ce qui permet d'automatiser les tâches répétitives et de réduire les erreurs humaines.
Intégration continue (CI): Le pipeline est configuré pour exécuter des tests à chaque commit, assurant ainsi que les modifications introduites ne cassent pas le code existant.
Rapports de couverture: Le pipeline génère des rapports de couverture de code à l'aide de Clover, ce qui permet d'évaluer la qualité du code et la couverture des tests.
Déploiement/Délivrance: Une fois les tests réussis, le pipeline déploie l'application en exécutant la commande npm run build et archive les artefacts pour référence future.

Main : Branche principale. On effectue les déploiements en production à partir de cette branche.
Dev : Domaine de développement principal où de nouvelles fonctionnalités sont constamment développées. Cette branche regroupe les fonctionnalités provenant des différentes branches de fonctionnalités.
