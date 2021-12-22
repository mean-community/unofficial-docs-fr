---
description: >-
  Mean Protocol intègre les flux de prix Chainlink pour aider à sécuriser les
  DCA et les flux d'argent à Solana.
---

# Mean Protocol intègre les flux de prix Chainlink pour aider à sécuriser les DCA et les flux d'argent

![](https://miro.medium.com/max/1000/0\*vqDsx7itCCQ9cwYs)

Nous sommes ravis d'annoncer que Mean Protocol, la première plateforme de streaming et d'automatisation de transferts d'actifs sur Solana, intègre les flux de prix de l'oracle Chainlink dans ses smart contracts. Grâce à cette intégration dans le réseau oracle leader du secteur, Mean Protocol et MeanFi auront accès à des données de prix inviolables et précises qui agiront comme un disjoncteur pour empêcher l'exécution automatique des flux de travail dans des conditions de marché extrêmes. Par conséquent, les utilisateurs, les trésoriers et les bénéficiaires de flux d'argent pourront configurer les besoins précis dans lesquels leur DCA sera exécuté.

Nous avons choisi Chainlink comme première solution oracle en raison de son approche de tolérance zéro en matière de sécurité et de fiabilité. Ils sont la référence en matière de précision et de résilience en cas de volatilité extrême du marché, de temps d'arrêt de la bourse ou de l'API, et d'attaques de manipulation de données comme les attaques de prêts flash. De plus, les flux de prix Chainlink sur Solana peuvent publier des mises à jour d'oracle sur la chaîne à des fréquences inférieures à la seconde, ce qui permet de garantir que les données de prix reflètent les conditions du marché en temps réel.

### Sécuriser le protocole moyen avec Chainlink

Notre pain et notre beurre à Mean DAO est l'automatisation de la DeFi. Depuis le tout début, nous avons entrepris de construire le pont entre la Finance Traditionnelle et la DeFi pour embarquer le prochain milliard d'utilisateurs des crypto-monnaies. Dans le cadre de ce voyage, nous avons créé des outils pour rendre les actifs plus liquides, plus efficaces en termes de capital et plus composables. Nous le faisons par le biais du Money Streaming et des DCA, et tous deux seront en mesure de tirer parti de cette intégration avec Chainlink.

### Flux d'argent

Les flux d'argent permettent une distribution de valeur en temps réel avec une efficacité maximale du capital. Ils sont un lego monétaire essentiel pour rendre le flux de valeur dans DeFi, aussi liquide, transparent et efficace qu'il peut l'être. Des flux de travail tels que "**Consacrer 20% de mon flux monétaire salarial, l'acheminer vers un protocole de prêt, en emprunter 50 % en USDC, l'échanger en SOL et en placer 100%**" sont désormais possibles dans Solana grâce aux Mean Money Streams.&#x20;

Cependant, vous pouvez voir que les conditions entourant le "piping" d'un flux d'argent pourraient être exploitées si un oracle de prix ne supporte pas un sous-ensemble de ces conditions.

![](https://miro.medium.com/max/700/1\*m5txAIRlRLPZqidJXEy\_oQ.jpeg)

Disons, par exemple, que vous voulez envoyer 20 % de votre salaire à un DEX pour effectuer des swaps de USDC → SOL, car je veux diversifier mon flux de revenus ; mais je ne veux le faire que lorsque le prix de SOL est stable, disons à moins de 20 % de la moyenne mobile quotidienne. Nous arrêterions automatiquement le flux d'argent vers le DEX si la condition ne parvient pas à être validée par Mean Protocol en utilisant les flux de prix Chainlink et le reprendrions automatiquement une fois que la condition passe à nouveau la validation. La magie!

### DCA Décentralisés

Mean Protocol offre le premier DCA décentralisé sur Solana. Nos utilisateurs profitent de l'interface familière et de la commodité de flux de travail tels que "**Acheter 15 dollars de SOL chaque semaine**" de manière autonome, sans permission et sans tiers de confiance.

![](https://miro.medium.com/max/700/0\*OXF0BWwfKE6FScXX)

Toutefois, dans des conditions de marché extrêmes, l'exécution d'un PPE déjà prévu peut être préjudiciable à l'investisseur. Si le prix d'un actif connaît une hausse soudaine, il peut être avantageux d'attendre un peu plus longtemps avant d'effectuer le prochain achat dans le cadre du PPE. Inversement, si le prix d'un actif connaît une baisse soudaine et que l'investisseur est convaincu de ses fondamentaux, il peut s'agir d'une occasion d'" acheter la baisse ".

## Pourquoi Chainlink

Ces scénarios exceptionnels sont possibles grâce à cette intégration entre Mean et Chainlink. Nos utilisateurs pourront configurer la façon dont ils souhaitent que leur DCA se comporte dans certaines conditions de marché, grâce aux flux de prix de Chainlink. Voici quelques-unes des raisons pour lesquelles nous avons décidé de faire appel à eux :

* **Rapide et de haute qualité** : Le réseau Chainlink s'approvisionne en données auprès d'un réseau d'agrégateurs de nœuds de premier ordre qui collectent des données auprès de nombreuses bourses, puis nettoie les résultats et supprime les valeurs aberrantes, tant en termes de prix que de volume. Le résultat est un histogramme de prix lisse qui fonctionne parfaitement pour les DCA moyens.
* **Réseau décentralisé** : La décentralisation apporte de nombreux avantages à un Oracle, comme la redondance, la précision, l'évolutivité, la vitesse, la reprise après sinistre, etc. Les flux de prix Chainlink bénéficient de nombreuses couches de décentralisation depuis leurs sources de données, les nœuds d'oracle et les niveaux de distribution du réseau.
* **Agnostique à la blockchain** : Chainlink est un réseau oracle agnostique aux blockchains qui fonctionne nativement à la vitesse de chaque réseau sur lequel il opère. C'est un avantage énorme pour les produits Mean DAO, avec un avenir multichaîne. Cela signifie que nous serons en mesure de réutiliser nos connexions, notre savoir-faire et nos relations avec Chainlink lorsque nous nous étendrons à d'autres réseaux.
* **Sécurité** : Les flux de prix sont sécurisés par des nœuds oracles indépendants, évalués par des pairs, validés par le réseau et résistants à la sybille, gérés par des équipes DevOps blockchain de premier plan, des fournisseurs de données et des entreprises traditionnelles ayant de solides antécédents de fiabilité, même en cas de congestion extrême du réseau. Chainlink a été créé en 2017 et fonctionne depuis 2019 sur plusieurs réseaux. C'est l'un des réseaux d'oracles les plus utilisés, les plus stables et les plus révisés en matière de sécurité dans le monde.

> “En intégrant Chainlink Price Feeds, Mean Protocol contribue à apporter le DCA décentralisé et le streaming monétaire à l'écosystème Solana pour alimenter des services DeFi sécurisés et automatisés. Les réseaux d'oracle de prix inviolables de Chainlink contribueront à garantir aux nouveaux utilisateurs qui s'initient à la crypto-monnaie par le biais de la plateforme de Mean une expérience DeFi hyper-fiable et transparente."

\- Tomasz Wojewoda, chef des ventes mondiales chez Chainlink Labs

Vous pouvez en savoir plus sur Chainlink en visitant [chain.link](https://chain.link) ou en lisant la documentation à l'adresse [docs.chain.link](https://docs.chain.link).

### Participez

Nous sommes très heureux de cette intégration avec Chainlink qui apporte des fonctions de sécurité supplémentaires à Mean Protocol et MeanFi. Elle renforcera encore notre position de meilleure expérience DeFi à travers Solana.

Restez au courant de nos progrès chaque semaine et rejoignez la révolution DeFi en consultant notre site Internet [website](https://meanfi.com), rejoindre la Mean DAO [Discord](https://discord.meanfi.com), et en suivant [@MeanFinance on Twitter](https://twitter.com/meanfinance).
