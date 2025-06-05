---
layout: doc
---


# 職務経歴書

## 基本情報

|          |                                                              |
| -------- | ------------------------------------------------------------ |
| 氏名     | 萩原誠人                                                     |
| 生年月日 | 1993/5/19                                                    |
| 居住地 | 東京都杉並区 |
| 最終学歴 | 早稲田大学社会科学部卒 |
| Github   | [https://github.com/hagiohagi](https://github.com/hagiohagi) |

---

## 保有スキル

- Web アプリケーションの設計・開発・運用（フロントエンド、バックエンド）
- AWS を用いた web アプリケーションインフラの環境構築・運用
- CloudFormation による AWS 構成のコード定義化
- 6〜10 人規模チームのサブ PM 経験（スケジュール策定、顧客対応、運用ルール策定）

## 保有資格

- AWS Developer Associate（2023 年 2 月）
- GC Cloud Digital Leader（2022 年 11 月）
- 基本情報技術者（2021 年 11 月）
- AWS Solutions Architect Associate（2021 年 5 月 → 2024 年 6 月 再取得）
- IT パスポート（2020 年 11 月）

## 技術スタック

### 言語

- JavaScript
- Ruby
- Python
- PHP

### ライブラリ・フレームワーク

- Vue
- Node.js
- Ruby-on-Rails
- Laravel

### クラウド

- AWS (実務経験あり）
  - コンピューティング： EC2, セッション Manager
  - ストレージ： S3
  - データベース： RDS, Aurora, DynamoDB
  - ネットワーク： VPC, Route53, ALB, CloudFront
  - セキュリティ： Cognito, GuardDuty
  - 監視・運用： CloudWatch, EventBridge, CloudTrail
  - IaC: CloudFormation
  - サーバーレス： API Gateway, Lambda
  - その他： Amazon Connect, Transcribe
- Google Cloud (実務経験なし）
- Azure (技術調査経験あり）

### データベース

- PostgreSQL
- MySQL (MariaDB)

### その他

- LAMP 環境構築
- Slack API 連携
- WordPress
- Moodle OSS の利用
- GitHub Actions

## 職務経歴詳細

### 株式会社エクストリーム (2024 年 1 月〜2025 年 3 月）

|          |                                                                                                                                                                    |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 事業内容 | 顧客常駐型でのスマホアプリ、IT、Web 系ソフトウェア開発など |
| 従業員数 | 727 名                                                                                                                                                            |
| 雇用形態 | 契約社員                                                                                                                                                             |
| 職種     | アプリケーション開発エンジニア・クラウド構築エンジニア                                                                                                                                     |

- **プロジェクト：** BtoB 向け地図検索 web アプリの機能実装・AWS 環境構築

  - **プロジェクト詳細：**
    - マップ情報に連動した住宅データの検索・編集・登録
  - **使用した技術：**
    - JavaScript (フロントエンド ES5 の記法）
    - PHP (バックエンド）
    - PostgreSQL (データベース postGIS・pgcrypto をモジュールとして使用）
    - AWS (Route53・ALB・EC2・S3・CloudFormation)
  - **担当：**
    - 開発
      - JavaScript を用いた独自 web フレームワークの設計・構築
    - 保守
      - Amazon Linux 2 から Amazon Linux 2023 への OS 切り替えに伴う調査及び移行作業
      - CloudWatch・EventBridge・CloudTrail・GuardDuty などによる運用・監視
      - ALB トラストストア機能によるクライアント証明書と連動したアプリケーションの導入
      - AWS CloudFormation 導入による案件ごとの環境構築手順の簡略化（2 日→3 時間 )
      - Azure の Virtual Machine でのアプリ動作検証及び Azure における環境構築

### アイレット株式会社 (2022 年 1 月〜2022 年 6 月）

|          |                                                                                                                                                                    |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 事業内容 | Web システム開発、スマホアプリ（iOS/Android）開発・運用、クラウドを活用したインフラ設計・構築・運用のフルマネージドサービス「cloudpack」の提供、UI/UX デザイン制作 |
| 従業員数 | 1215 名                                                                                                                                                            |
| 雇用形態 | 正社員                                                                                                                                                             |
| 職種     | アプリケーション開発エンジニア                                                                                                                                     |

- **プロジェクト（1）：** 6〜10 人規模でのブラウザ・iOS・Android 対応の Web アプリの開発

  - **プロジェクト詳細：**
    - 2 時間程度の長尺動画のストリーミング再生機能
    - 動画視聴進捗度の数値化
    - ユーザーアカウント登録・ログイン・招待機能
    - プッシュ通知機能
    - 他サービスとのシングルサインオン機能
  - **使用した技術：**
    - Laravel 6
    - Vue 2.6
    - Github Actions
    - AWS（S3・EC2・Amazon CloudFront・Elemental MediaConvert・ECS・ALB・Cognito・Aurora）
  - **担当：**
    - サブ PM（スケジュール策定・お客様対応・運用ルール策定）
    - プログラマ（API 実装・フロントエンド実装・テスト作成）

- **プロジェクト（2）：** NoSQL でアンケート内容を保存・取得する API の作成
  - **プロジェクト詳細：**
    - web ページでアンケート内容を保存・取得できる機能の実装
  - **使用した技術：**
    - AWS APIGateway
    - AWS Lambda
    - AWS CloudFormation
    - Amazon DynamoDB
    - Python 3
  - **主な取り組み：**
    - AWS APIGateway と AWS Lambda をプロキシ統合で連携し、API で Lambda 関数を動作させる
    - Lambda 内で Python のコードを記述し、DynamoDB へクエリを送る実装
    - CloudFormation によって作成した Lambda のテスト環境によるユニットテスト

### 株式会社ディグナ (2021 年 1 月〜2021 年 10 月）

|          |                                                                                       |
| -------- | ------------------------------------------------------------------------------------- |
| 事業内容 | 中小企業の IT 支援・IT 導入補助金採択支援・Google Workspace と HubSpot 認定公式代理店 |
| 従業員数 | 23 名                                                                                 |
| 雇用形態 | 業務委託                                                                              |
| 職種     | 社内システムエンジニア                                                                |

- **プロジェクト（1）：** E ラーニング Web サービスのインフラ構築

  - **プロジェクト詳細：**
    - AWS を用いたネットワーク構成・サーバー・ドメイン設定等の構築
    - AWS の利用コスト管理
    - Moodle の初期設定（メール送受信・アカウント権限等）の構築（※Moodle = LAMP 環境で構築されたオープンソースのオンライン学習システム）
  - **使用した技術：**
    - LAMP 環境（Debian・Apache・MariaDB・PHP）
    - AWS（VPC・EC2・S3・ELB・Route53・RDS・SES）

- **プロジェクト（2）：** コールセンター従事社員に向けた Slack 通知機能の実装
  - **プロジェクト詳細：**
    - Amazon Connect と Lambda 関数を連動し、電話問い合わせフロー及び Slack 通知機能の設計を行う
    - 以下の 3 点を実装
      - 不在着信時に発信元の電話番号を Slack 上に自動通知する機能
      - 通話終了時に顧客との通話音声を文章化し Slack に自動通知する機能
      - オペレーター不在時に留守電としてメッセージの録音ができる機能
  - **使用した技術：**
    - Slack API
    - AWS（Amazon Connect・Lambda・Amazon Transcribe・S3・Cognite・AWS SDK）

### 株式会社 KICHIRI (2016 年 4 月〜2020 年 2 月）

|          |                                 |
| -------- | ------------------------------- |
| 事業内容 | 外食レストラン                  |
| 従業員数 | 2300 名                         |
| 雇用形態 | 正社員                          |
| 職種     | 店舗営業（2018 年に店長に昇格） |

## 業務外活動

- 就職活動時に作成した成果物を通して、Ruby on Rails を用いた DB 管理とログイン機能を実装したアプリを開発
  - リポジトリ： [apply_easily_app](https://github.com/hagiohagi/apply_easily_app)
- 大学の先輩が関わる新規事業にボランティアとして参加し、Wordpress によるコーポレートサイトを作成
- オンラインコミュニティ[「AWS CloudTech」](https://kws-cloud-tech.com/)に所属し、その中のプロジェクトである AWS 初学者向け書籍の商業出版に参画し、一部文章を執筆
- 友人の要望に応え、大学のゼミで使用する写真登録アプリを Laravel を用いて開発
  - リポジトリ： [shokujikanri_app](https://github.com/hagiohagi/shokujikanri_app)
  - 実装内容：
    - ムームードメインによるドメインの発行
    - ロリポップサーバーで Linux・MySQL のセットアップ
