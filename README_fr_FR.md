<h1 align="center">
<img src="https://i.imgur.com/DDkfI9i.png" alt="Beerscoin" width="300"/>
<br/><br/>
Beerscoin Core [BRC, Ᵽ]  
</h1>

Choisir la langue : [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | FR | [JA](./README_ja_JP.md) | [DE](./README_de_DE.md)

Contrairement à toutes les itérations précédentes, Beerscoin est une monnaie dite « layer 1 ». Cela signifie qu'il n'y a pas de pools de liquidités à drainer, pas de portefeuilles blacklistés, et pas de contrats intelligents obscurs. Le Beerscoin est une blockchain simple.

Le logiciel Beerscoin Core permet à quiconque d'opérer un nœud au sein des réseaux de la blockchain Beerscoin et utilise la méthode de hachage Scrypt pour la preuve de travail (Proof of Work). Ce logiciel est adapté du Dogecoin Core, du Bitcoin Core et d'autres crypto-monnaies.

Pour plus d'informations sur les frais par défaut utilisés sur le réseau Beerscoin, veuillez vous référer à [recommandation de frais](doc/fee-recommendation.md).

**Site web:** [beerscoin.com](https://beerscoin.com)

## Différences avec le Dogecoin

Beerscoin est un fork du Dogecoin, conçu pour offrir une expérience similaire et familière.

Changements :

* Les adresses commencent par `P` au lieu de `D`
* Les fonctionnalités BIPS commenceront au bloc 1000
* AuxPow commence au bloc 100 000 (ID de chaîne : 63)
* L'interface graphique a été adaptée pour Beerscoin

## Usage 💻

Pour commencer votre voyage avec Beerscoin Core, consultez le [guide d'installation](INSTALL.md) et l'[introduction](doc/getting-started.md).

L'API JSON-RPC fournie par Beerscoin Core est auto-documentée et peut être consultée avec `beerscoin-cli help`, tandis que des informations détaillées pour chaque commande peuvent être consultées avec `beerscoin-cli help <commande>`. Vous pouvez également consulter la [documentation Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - qui met en œuvre un protocole similaire - pour obtenir une version consultable.

### Ports

Beerscoin Core utilise par défaut le port `19618` pour la communication peer-to-peer 
qui est nécessaire pour synchroniser la blockchain du « mainnet » et rester informé 
des nouvelles transactions et des nouveaux blocs. De plus, un port JSONRPC peut être ouvert, 
qui est par défaut le port `19617` pour les nœuds du réseau principal. 
Il est fortement recommandé de ne pas exposer les ports RPC à l'internet public.

| Fonction | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   19618 |   44874 |   18444 |
| RPC      |   19617 |   44873 |   18332 |

## Développement en cours 💻

Beerscoin Core est un logiciel libre et communautaire. 
Le processus de développement est ouvert et visible publiquement ; 
tout le monde peut voir, discuter et travailler sur le logiciel

Principales ressources de développement :

* [GitHub Projects](https://github.com/beerscoinppc/beerscoin/projects) est utilisé pour
  suivre les travaux planifiés et en cours pour les prochaines versions.
* [GitHub Discussion](https://github.com/beerscoinppc/beerscoin/discussions) est utilisé pour discuter des fonctionnalités, des projets et des projets en cours.
  pour discuter des fonctionnalités, planifiées et non planifiées, liées à la fois au développement du
  développement du logiciel Beerscoin Core, des protocoles sous-jacents et de l'actif BRC.  
* [BeerscoinDev subreddit](https://www.reddit.com/r/beerscoindev/)

### Stratégie de version
Les numéros de version suivent la sémantique ```major.minor.patch```.

### Branches
Il y a 3 types de branches sur ce dépôt :

- **master:** Stable, contient la dernière version de la dernière version *major.minor*.
- **maintenance:** Stable, contient la dernière version des versions précédentes, qui sont toujours en maintenance active. Format : ```<version>-maint```
- **development:** Unstable, contient le nouveau code pour les versions planifiées. Format : ``<version>-maint`` : ``<version>-dev```

*Les branches Master et maintenance sont exclusivement mutables par version.*
*Les versions planifiées auront toujours une branche de développement *
*et les pull requests doivent être soumises sur celles-ci. Les branches de maintenance sont là pour **les corrections de bugs uniquement,***
*Veuillez soumettre les nouvelles fonctionnalités sur la branche de développement avec la version la plus élevée.*

## Contribuer 🤝

Si vous trouvez un bug ou si vous rencontrez des problèmes avec ce logiciel, 
veuillez le signaler [ici](https://github.com/beerscoinppc/beerscoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Veuillez consulter [le guide de contribution](CONTRIBUTING.md) pour savoir comment vous pouvez participer au développement de Beerscoin Core. Il y a souvent des
[topics seeking help](https://github.com/beerscoinppc/beerscoin/labels/help%20wanted) où vos contributions auront un impact important et seront très appréciées.

## Communautés 🐸

Vous pouvez rejoindre les communautés sur différents médias sociaux pour voir ce qui se passe, 
rencontrer des gens et discuter, trouver le dernier mème, en savoir plus sur Beerscoin, 
donner ou demander de l'aide, partager votre projet.

Voici quelques espaces à visiter :

* [r/Beerscoin](https://www.reddit.com/r/beerscoin/)
* [Discord](https://beerscoin.com/discord)
* [Telegram](https://t.me/BeerscoinGroup)
* [Twitter/X](https://twitter.com/BeerscoinNetwork)

## Foire aux question ❓

Vous avez une question concernant Beerscoin ? Une réponse se trouve peut-être déjà dans la [FAQ](doc/FAQ.md) ou dans la [section Q&A](https://github.com/beerscoinppc/beerscoin/discussions/categories/q-a) du forum de discussion !

## Licence ⚖️
Beerscoin Core est publié sous les termes de la licence MIT. Voir
[COPYING](COPYING) pour plus d'informations ou voir
[opensource.org](https://opensource.org/licenses/MIT)
