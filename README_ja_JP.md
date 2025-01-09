<h1 align="center">
<img src="https://i.imgur.com/DDkfI9i.png" alt="Beerscoin" width="300"/>
<br/><br/>
Beerscoin Core [BRC, Ᵽ]  
</h1>

言語を選択: [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | [FR](./README_fr_FR.md) | JA | [DE](./README_de_DE.md)

Beerscoinは、2013年のオリジナルのDogecoin shibesの1人によって作成されたコミュニティに焦点を当てた暗号通貨です。これは、オリジナルのDogecoinコミュニティと同じように、新しくて楽しいコミュニティを作成するために作成されました。

以前のすべてのバージョンとは異なり、Beerscoinはレイヤー1のコインです。これは、排水する流動性プールがなく、ブラックリストに登録されたウォレットがなく、混乱するスマートコントラクトがないことを意味します。Beerscoinはシンプルなブロックチェーンです。

Dogecoinと同様に、Beerscoin Coreソフトウェアを使用すると、誰でもBeerscoinブロックチェーンネットワーク内でノードを操作でき、作業証明のためにScryptハッシュメソッドを使用します。これは、Dogecoin Core、Bitcoin Core、およびその他の暗号通貨から適応されています。

Beerscoinネットワークで使用されるデフォルトの料金に関する情報については、[料金の推奨事項](doc/fee-recommendation.md)を参照してください。

**ウェブサイト:** [beerscoin.com](https://beerscoin.com)

## Dogecoinの違い

BeerscoinはDogecoinのフォークです。親しみやすさのために、BeerscoinをDogecoinに似せるように努めます。

変更点：

* アドレスは`D`ではなく`P`で始まります
* BIPS機能はブロック1000から開始されます
* AuxPowはブロック1500から開始されます（チェーンID：63）
* Beerscoin用にテーマ設定されたGUI

## 使用法 💻

Beerscoin Coreの旅を始めるには、[インストールガイド](INSTALL.md)と[入門](doc/getting-started.md)チュートリアルを参照してください。

Beerscoin Coreが提供するJSON-RPC APIは自己文書化されており、`beerscoin-cli help`を使用して参照できます。各コマンドの詳細情報は、`beerscoin-cli help <command>`を使用して表示できます。あるいは、[Bitcoin Coreのドキュメント](https://developer.bitcoin.org/reference/rpc/)を参照してください。これは同様のプロトコルを実装しており、参照可能なバージョンを取得できます。

### ポート

Beerscoin Coreはデフォルトでピアツーピア通信にポート`19618`を使用します。これは、「メインネット」ブロックチェーンを同期し、新しいトランザクションとブロックの情報を取得するために必要です。さらに、JSONRPCポートを開くことができ、デフォルトではメインネットノードのポート`19617`になります。RPCポートをパブリックインターネットに公開しないことを強くお勧めします。

| 機能     | メインネット | テストネット | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   19618 |   44874 |   18444 |
| RPC      |   19617 |   44873 |   18332 |

## 継続的な開発 💻

Beerscoin Coreはオープンソースでコミュニティ主導のソフトウェアです。開発プロセスはオープンで公開されており、誰でもソフトウェアを見て、議論し、作業することができます。

主な開発リソース：

* [GitHubプロジェクト](https://github.com/beerscoinppc/beerscoin/projects)は、今後のリリースのために計画されている作業と進行中の作業を追跡するために使用されます。
* [GitHubディスカッション](https://github.com/beerscoinppc/beerscoin/discussions)は、Beerscoin Coreソフトウェアの開発、基礎となるプロトコル、およびBRC資産に関連する計画されたおよび計画されていない機能について議論するために使用されます。
* [BeerscoinDev subreddit](https://www.reddit.com/r/beerscoindev/)

### バージョン戦略
バージョン番号は```major.minor.patch```のセマンティクスに従います。

### ブランチ
このリポジトリには3種類のブランチがあります：

- **master:** 安定版、最新の*major.minor*リリースの最新バージョンを含みます。
- **maintenance:** 安定版、以前のリリースの最新バージョンを含み、まだアクティブなメンテナンスが行われています。形式：```<version>-maint```
- **development:** 不安定版、計画されたリリースの新しいコードを含みます。形式：```<version>-dev```

*Masterおよびmaintenanceブランチはリリースによってのみ変更可能です。計画された*
*リリースには常に開発ブランチがあり、プルリクエストはそれらに対して送信する必要があります。メンテナンスブランチは**バグ修正のみ**のために存在します。新しい機能は、最も高いバージョンの開発ブランチに対して送信してください。*

## 貢献 🤝

このソフトウェアにバグを見つけたり、問題が発生した場合は、[問題システム](https://github.com/beerscoinppc/beerscoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+)を使用して報告してください。

Beerscoin Coreの開発に参加する方法については、[貢献ガイド](CONTRIBUTING.md)を参照してください。多くの場合、[助けを求めるトピック](https://github.com/beerscoinppc/beerscoin/labels/help%20wanted)があり、あなたの貢献が大きな影響を与え、高く評価されます。

## コミュニティ 🐸

さまざまなソーシャルメディアでコミュニティに参加できます。
何が起こっているのかを確認し、人々と出会い、議論し、最新のミームを見つけ、Beerscoinについて学び、助けを提供したり求めたり、プロジェクトを共有するために。

訪れるべき場所のいくつかを以下に示します：

* [r/Beerscoin](https://www.reddit.com/r/beerscoin/)
* [Discord](https://beerscoin.com/discord)
* [Telegram](https://t.me/BeerscoinGroup)
* [Twitter/X](https://twitter.com/BeerscoinNetwork)

## よくある質問 ❓

Beerscoinに関する質問がありますか？答えはすでに[FAQ](doc/FAQ.md)またはディスカッションボードの[Q&Aセクション](https://github.com/beerscoinppc/beerscoin/discussions/categories/q-a)にあるかもしれません。

## ライセンス ⚖️
Beerscoin CoreはMITライセンスの条件の下でリリースされています。詳細については[COPYING](COPYING)を参照するか、[opensource.org](https://opensource.org/licenses/MIT)を参照してください。
