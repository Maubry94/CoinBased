# CoinBASED

Une application C permettant la simulation d'investissements dans des crypto-monnaies.

## Fonctioinnalités

- Connexion / Inscription
- Regarder le cours en temps en reel des cryptos (via api request et lib CURL)
- Affichage graphique des courbes sur 1H, 4H, 1D, 7D, 1M, 1Y, 5Y, ALL (via lib graphique)
- Simulation d'investissement de cryptos
- Pouvoir modifier son profil et inspecter ses cryptos dans son portefeuille (via BDD)
- Barre de recherche permettant de selctionner la cryptomonnaie voulue (expl BTC - ETH)
- Achat "réel" de crypto + injection dans le wallet
- historique d'achat

## Bibliothèques utilisées

- curl pour les requêtes api
- GtK, SDL, Allegro, SFML pour les graphismes (à déterminer)
- coinmarketcap api pour les données relatives aux cryptos monnaies
