TOC
- [スキル](#スキル)
- [職務経歴](#職務経歴)
  - [2016/04 - 現在](#2016/04-現在)

## スキル

### 言語

#### Java
- 1.6~1.8を4年ほど経験。
- J2EE, Struts2, Spring BootによるWebアプリケーションを開発。

#### JavaScript
- Webアプリケーションのフロントエンド開発のため3年ほど経験。
- jQuery/React/Vue.jsなどを利用した開発実績がある。

#### Python
- 2.7系を4年、3系を1年ほど経験。
- 主に一括処理やクローリングなどの日常的な業務の自動化など
- DjangoによるWebアプリケーションを開発。
- NumPyやscikit-learnなどのライブラリを用いた簡単な機械学習（自然言語処理）も経験。

#### HTML5/CSS3
- フロントエンド開発のため6年ほど経験。
- 普通に読み書きができ、デザインカンプを元に静的ページを再現できる。

#### Shell
- バックグランドの処理や自動化のために3年ほど経験。

### その他

#### MySQL, PostgreSQL
- Webアプリケーションのデータ管理のため3年ほど経験。
- テーブル作成、テーブル操作、ユーザ権限の変更ができる。

#### Apache/Tomcat
- Tomcatは5.3~8.5。Webアプリケーションのコンテナとして3年ほど運用。Apacheおよびアプリケーション側の連携を設定できる。
- ApacheはWebサーバ、ロードバランサとして使用。リダイレクト、アクセス制限、リバプロ設定ができる。

#### AWS
- CMS管理のためEC2インスタンスでWordPressを運用。
- LightSailインスタンス上でbitnami Nginxサーバ, bitnami WordPressを運用中。

####  Jenkins
- デプロイの自動化のために2年ほど経験。ジョブの作成、運用をすることができる。

## 職務経歴

### 2016/04 - 現在
職務：Webアプリケーションエンジニア
職務概要：日本最大級辞書サイトの開発・運用

#### 職務内容
2020/01- **広告配信CMS開発**
- 広告チームのチューニング作業を効率化するためのCMS構築。現在設計中。
- 役職: 開発責任者

2019/12- **サイトリニューアル**
- 企画チームへの技術的アドバイス、外注先との調整、開発作業のコーチング
- 役職: 開発責任者
- 開発者: 2名

2019/09-2019/10 **増税対応**
- 有料会員の各種決済システムの管理（GMO Payment/PayPal）
- 役職: 開発責任者
- 開発者: 1名

2019/06-2019/12 **サーバ・ネットワーク移行**
- 社内サーバをプライベートクラウドへ移行
- 役職: 開発担当
- 開発者: 4名

2018/09-2019/06 **SEO/広告施策**
- SEO強化のため、metaタグ変更を半自動化、キーワード抽出機能を実装
- 広告レイアウトの実装
- 役職: 開発担当
- 開発者: 2名

2018/07-2018/09 **ランキング機能プロジェクト**
- ユーザ属性のレポート作成、テストの都道府県別ランキング実装
- 役職: 開発担当
- 開発者: 1名

2018/04-2018/07 **音声版語彙力診断テストの実装**
- テキストベースの診断テストを、出題を音声にすることでリスニングテストとして実装
- カテゴリ名で分岐したためテーブル実装は無し
- 役職: 開発担当
- 開発者: 1名

2017/11-2018/04 **キャンペーンプロジェクト**
- LPページの作成、定期購読コンテンツの配信。
- 初期は全て内製していたがWordPressに投稿した外注データをアプリケーションから参照できるシステムを構築した
- 役職: 開発担当
- 開発者: 2名

2017/07-2017/10 **EFO改善プロジェクト**
- アプリケーション上のエントリーフォーム、モーダルの改善
- 役職: 開発担当
- 開発者: 2名

2017/06-2017/07 **翻訳ログ分析**
- 翻訳ログを分析し、ニーズの高い分野の精度向上を目指した。アクセス元別に翻訳ログを分類し、頻度の高い名詞・動詞とその前後の係り受け関係を数値化。この結果を元にデータ作成の外注を行った。
- 役職: 開発担当
- 開発者: 2名

2017/01-2017/06 **音声認識機能付き診断テストプロジェクト**
- テキストベースの診断テストを音声認識機能をつけてスピーキングテストを実装。スコアリングテーブル作成、ランキング機能の実装。
- 役職: 開発担当
- 開発者: 1名

定常的に行う業務
- **seleniumによるUIテストを実装**
  - 機能変更時、デプロイ時のブラウザテストを自動で行うためにSeleniumIDE＋のちにwebdriverを用いた自動テストを実装。Jenkinsと連携することで簡単かつ短時間でテストを実行できるようにした。
- QAサイト開発
- タグ管理システムの開発
- **デプロイスクリプト作成、CI導入・運用**（shell/python/webhook/Jenkins）
  - コスト削減のためアプリケーション、データベースのデプロイの自動化を行った。コマンドのスクリプト化でコマンドミスを減らし、Jenkinsを導入したことでひとつの画面上で各サーバへのデプロイが行えるようにした。
- **コンテンツ作成のためのクローラ作成**（Java/Python）
  - 外部から提供されたデータを社内の辞書システムで読み込むためのクローラを作成。CSV,TSV,インターネット上のHTMLなどからクローリングとスクレイピングを行った。
- **ミドルウェアの管理**（Tomcat/MySql）
