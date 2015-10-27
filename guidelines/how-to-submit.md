# 製品開発・提出方法
JPHACKSでは参加者の方々がより開発に時間を費やし、質の高い製品開発をサポートするために、GitHub、DEVPOSTという外部サービスを活用しております。

## 前提条件
GitHub、DEVPOSTの登録が完了、ログインしている状態であることを前提として、開発から提出方法を記載いたします。

## 開発から提出の流れ

1. リポジトリの作成
2. サンプルプロジェクトからREADME.mdの複製
3. 開発製品の登録・README.mdの完成
4. DEVPOSTへの登録
5. フォーム提出

## 製品開発・提出方法の選択
JPHACKSではGitHubを活用した開発と作品の提出を必須としております。
参加者は製品ライセンスの異なる以下の2つの開発手法を選択することが出来ます。
オープンソースの開発のメリットとしては、共同編集者による支援が獲得出来る可能性がある点、DEVPOSTへの提出が安易になる等がございますが、反面「製品情報を公開する」という点がございます。[開発ルール](rule.md)にも記載のある通り、JPHACKS運営事務局では、もし著作権や知的財産権その他の権利を侵害する行為があった場合においても、一切の責任は負いかねますので、製品情報を良くお確かめの上、公開非公開の選択をしていただきますようお願い致します。

1. [オープンソースプロジェクトとして開発する](#section1)  
オープンソースプロジェクトとして開発をする場合、ソースコードはOSSとして一般に公開されます。
またJPHACKSではMTIライセンスの適用を推奨しております。

2. [プライベートリポジトリを活用して開発する](#section2)  
プロジェクトのソースコードを非公開にしたい場合は、GitHubのプライベートリポジトリを活用します。
プライベートリポジトリの取得方法につきましては、[事前準備物](tools.md)をご確認ください。

## <a name="section1">1. オープンソースプロジェクトでの開発・提出方法
### 1-1. プロジェクトリポジトリの作成
* GitHubにアクセスし、新しいプロジェクトリポジトリを作成してください。
  * [公式ガイド](https://guides.github.com/activities/hello-world/)が参考になります
  * LICENSEはMTI LICENSEを選択することを推奨します。（ライセンスについては[コチラ](https://help.github.com/articles/open-source-licensing/)をご参照下さい）

### 1-2. README.mdの複製
* サンプルリポジトリの[README.md](https://github.com/jphacks/sample/blame/master/README.md)にアクセスし、コピーをしてください。
* こちらのテンプレートを、作成したリポジトリのディレクトリ直下に、README.mdとして保存をしてください。
* Initial Commit で既にREADME.mdを作成している場合は、テンプレートを上書きしてください。

### forkによるリポジトリの作成
jphacksの公式アカウントのサンプルリポジトリ（[sample](https://github.com/jphacks/sample)）からリポジトリをforkすると、これらのステップを省くことが出来ます。

### 1-3. 開発製品の登録・README.mdの完成
* Gitリポジトリとして製品のバージョン管理を実施してください。
* リポジトリの設定（リポジトリページ > settings > Collaborators & teams > Collabrater）にて、開発メンバーを追加して開発することを推奨します。
* GitHub、Gitによる製品のバージョン管理がわからないチームは、ハッカソン前に外部サイトなどで使い方を習得するようお願いいたします。
  * 運営側でもGitHubの使い方については、Slackのチャンネル上でフォローいたします。
* README.mdの空欄を埋めて、内容を完成させてください。

* 完成形のイメージとして、[サンプル](https://github.com/jphacks/sample/tree/tum-music)をご参照ください。

### 1-4. DEVPOSTへの登録
* [プロジェクトの登録ページ](http://devpost.com/software/)にアクセスしてください。
* GitHubリポジトリのインポートを選択し、今回作成した製品のリポジトリを指定し、インポートをしてください。
* 登録の詳細ページに、入力事項を埋めて、登録を完了してください。
* **[必須]GitHubのURLは提出が必須となります。URLが記入されているかどうか、必ずお確かめ下さい。**
* **[必須]デモ動画など、作品のUI/UXがわかるものを登録してください。**

* 完成形のイメージとして、[サンプル](http://devpost.com/software/tum-music)をご参照ください。

### 1-5. フォームによる作品の提出
* [製品提出フォーム](https://docs.google.com/forms/d/1NmH8tDSldl1b_q5QyhVPEB-rnnedVGIHF-5upFwe7Dc/viewform)にアクセスし、必要事項を記入します。
* チーム決定時に配布されている、会場ID・チームIDを入力してください。
* 1-4で登録をしたDEVPOSTのプロジェクトURLを記入してください。
  * DEVPOST以外のURLは受け付けておりませんので、ご注意ください。
* エントリ部門を第一希望から第三希望まで選択してください。

## <a name="section2">2. プライベートリポジトリでの開発・提出方法
### 2-1. プロジェクトリポジトリの作成
* GitHubにアクセスし、新しいプロジェクトリポジトリを作成してください。
  * [公式ガイド](https://guides.github.com/activities/hello-world/)が参考になります
  * 作成ページ上でPrivateの設定を選択するようにしてください。

### forkによるリポジトリの作成
公式アカウントのサンプルリポジトリのforkの場合、Privateにすることは出来ません。

### 2-2. 開発製品の登録
* Gitリポジトリとして製品のバージョン管理を実施してください。
* リポジトリの設定（リポジトリページ > settings > Collaborators & teams > Collabrater）にて、開発メンバーを追加して開発することを推奨します。
* **[必須]メンバー同様（リポジトリページ > settings > Collaborators & teams > Collabrater）から、かならず公式アカウント[jphacks-official](https://github.com/jphacks-official)をCollaboratorに追加してください。**
* GitHub、Gitによる製品のバージョン管理がわからないチームは、ハッカソン前に外部サイトなどで使い方を習得するようお願いいたします。
  * 運営側でもGitHubの使い方については、Slackのチャンネル上でフォローいたします。

* 完成形のイメージとして、[サンプル](https://github.com/jphacks/sample/tree/tum-music)をご参照ください。

### 2-3. DEVPOSTへの登録
* [プロジェクトの登録ページ](http://devpost.com/software/)にアクセスしてください。
* 今回作成したプロジェクトの情報を登録してください。
* サンプルリポジトリの[README.md](https://github.com/jphacks/sample/blame/master/README.md)にアクセスし、コピーをしてください。
* "Here's the whole story"の部分には、かならずREADME.mdと同じ内容のフォーマットにて、製品情報を登録してください。
* 登録の詳細ページに、入力事項を埋めて、登録を完了してください。
* **[必須]GitHubのURLは提出が必須となります。URLが記入されているかどうか、かならずお確かめ下さい。**
* **[必須]デモ動画など、作品のUI/UXがわかるものを登録してください。**

* 完成形のイメージとして、[サンプル](http://devpost.com/software/tum-music)をご参照ください。

### 2-4. フォームによる作品の提出
* [製品提出フォーム](https://docs.google.com/forms/d/1NmH8tDSldl1b_q5QyhVPEB-rnnedVGIHF-5upFwe7Dc/viewform)にアクセスし、必要事項を記入します。
* チーム決定時に配布されている、会場ID・チームIDを入力してください。
* 1-4で登録をしたDEVPOSTのプロジェクトURLを記入してください。
  * DEVPOST以外のURLは受け付けておりませんので、ご注意ください。
* エントリ部門を第一希望から第三希望まで選択してください。

## 注意事項
* 一度提出された製品情報の取り消し、及び修正は出来ませんのでご注意下さい。
* ハッカソン終了時刻までに、不慮の事態を除き提出が遅れた場合は、提出が認められない場合がございますの予めご了承下さい。

## 提出必須物の確認表
フォーム提出前に、DEVPOST上のプロジェクト内容に、以下の項目が全て当てはまっているか、必ずご確認ください。
- GitHubリポジトリのURLが記入されている
 - プライベートリポジトリの場合は、そのリポジトリのCollaboratorにjphacks-officialが加わっている
- 製品概要が、運営が提供するフォーマット[README.md](https://github.com/jphacks/sample/blame/master/README.md)と同様である
- DEMO動画が正しく再生することができている

--------------
[[目次へ戻る](../README.md)] [[審査基準へ](criteria.md)]
