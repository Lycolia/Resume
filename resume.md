## 概要

現在、Web 系の受託開発会社で開発業務を⾏っているプログラマです。  
直近では Laravel や React、Vue.js、Angular を使った Web 系の開発を行っております。

実装経験としては VB6 といったレガシーなものから、TypeScript や React といったモダンなもの、フロントエンドからバックエンド、オブジェクト指向や関数志向などまで、幅広い開発経験があり、おおよそ大抵の開発は卒なくできると思います。

また自動化や設計、技術選定、低レイヤーに対しても多少の知識や経験があります。

## 実務経験スキル

-   開発言語・FW

    -   TypeScript, JavaScript, Node.js, React.js
    -   Vue.js, Nuxt.js, Angular, jQuery, Jest
    -   PHP, Laravel, Python, C#.NET, VB.NET, VB6

-   開発環境

    -   Windows: NT4, XP, Vista, 7, 8, 8.1, 10
    -   Linux: Ubuntu, CentOS
    -   IDE: VSCode, VisualStudio, Eclipse
    -   CVS: Git, SVN

-   インフラ

    -   GitHub Actions, Apache, Nginx, Docker

-   コミュニケーション

    -   GitHub, GitLab, Slack, Redmine, Discord, Skype

-   その他
    -   SQL
        -   Oracle, SQLServer, MySQL, PostgresSQL, SQLite
    -   メタ言語
        -   HTML, CSS, 正規表現
    -   学習や趣味で触ったことがあるもの
        -   Jasmine, C 言語, Golang, mongodb

## 職務経歴

携わった案件が極めて多いため、直近のみピックアップしています。

### 大手音声コンテンツ配信サービスリプレース

<!-- prettier-ignore-start -->
```yaml
期間: 2020/02 - 現在
概要: |-
    フロント・バックエンドのモダナイズ
    バックエンドを Perl -> Go
    フロントエンドを jQuery -> React へ改修する内容
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    SE: 1人
    PG: 2人
    テスター: 1人
担当: |-
    * PG として技術選定から参画
      フロントサイドでの利用技術提案として
      既存のフロントが 1 枚の HTML に jQuery を埋め込んだ SPA でしたが、
      コンポーネント化されておらず、全体的な品質も良くはなかったため、
      その部分を改善するために React + TypeScript を提案し、採用されました
      採用理由としては静的解析による実装の整合性担保や、型推論による実装効率の向上があります
    
    * クライアントサイドの設計全般
      コンポーネントやデータ、エラーなど必要であろう全ての設計を行った
    * デザインカンプからの実装起こし
    * サーバーサイドとの設計調整

    * プロジェクト改善提案
    * コミュニケーションツールの改善提案
    * テストツールの改善提案
      サーバーサイドの手動テストが curl であり、セッション Cookie が操作できないとのことだったので POSTMAN を提案
      設定を組めば誰でもテストができる上、Cookie の書き換えも容易なため、よりブラウザに近い人力テストが行えるようになった
使用技術:
    - React 17, TypeScript, VSCode
    - nginx, CentOS 6.6, Docker, Git, GitHub, Windows 10
    - Google Chrome, iOS Safari, Android Google Chrome
```
<!-- prettier-ignore-end -->

### 派遣スタッフ管理システムリプレース

<!-- prettier-ignore-start -->
```yaml
期間: 2020/04 - 2020/11
概要: 派遣会社の人員が担当する派遣スタッフの勤怠や契約の管理を行う画面と、そのAPIのリプレース
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    PG: 8人
担当: |-
    PG として詳細設計、サーバーサイド、クライアントサイドの機能実装、結合テストを担当  
    また 設計不備の指摘や UI 改善、自動テスト、Linting の導入提案を行い、  
    UI 改善については幾つか採用されました。

    その他に言語未経験者やロースキルの方への技術サポートもしていました。
使用技術:
    - Nuxtjs 2.0.0, JavaScript, Laravel 5.6, PHP 7.1.3, SQL Server 2017
    - Apache, CentOS 7.7, Docker, Git, GitLab, Windows 10
    - Google Chrome, Edge, IE11, Safari
```
<!-- prettier-ignore-end -->

### 生産管理システムプロト作成

<!-- prettier-ignore-start -->
```yaml
期間: 2020/03 - 2020/04
概要: 既存の生産管理で数値化されていない部分を集計し、可視化するためのシステムのプロト開発
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    PG: 1人
担当: |-
    PGとしてMQTT等の各種プロトコルを利用し、
    生産機器からデータを吸い上げ、DBに登録する内容の実装
    またそれらの技術調査を行いました。
使用技術:
    - C#.NET 8.0, Windows Form, MQTT, GitHub, GitHub Actions, Windows 10
```
<!-- prettier-ignore-end -->

### 美容室向けのサブスクリプションサービス開発

<!-- prettier-ignore-start -->
```yaml
期間: 2020/03
概要: |-
    iOSアプリを利用した美容室向けのサブスクリプションサービスの開発
    このプロジェクトは副業として個人で受託しました。（Twitter経由）
プロジェクトメンバー:
    PM: 1人
    PG: 1人
担当: |-
    PG として以下の API 機能のプロト開発について、要件定義～テストまでを行いました。
    * ユーザー登録・更新・削除、決済情報のStripe連携、各種アクションに対するメール送信
    * ユーザーが購読するサブスクリプションプランの選択
    * 美容室の予約
使用技術:
    - Laravel 6.0, PHP 7.2, Stripe, GitHub, AWS, Postman, VSCode, Windows 10
```
<!-- prettier-ignore-end -->

### 低レベル放射性廃棄物埋設管理システムマイグレーション

<!-- prettier-ignore-start -->
```yaml
期間: 2019/12 - 2020/02
概要: |-
    Windows NT4, VB6, Oracle 8, SPREAD 2.5で動作する既存システムを
    Windows10, VB.NET 16, Oracle 12c, SPREAD 12J向けにマイグレーション
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    PG: 8人
担当: |-
    PGとして項目数が数十程度のC/Sシステムの画面、帳票、サーバーの実装
    他にプロジェクト運営の改善提案も行いました。
使用技術:
    - Windows Form, VB 6.0, VB.NET 16, SPREAD 2.5, SPREAD 12J
    - ActiveReports 12J, Oracle 8, Oracle 12c, Git, Windows 10, Windows NT4
```
<!-- prettier-ignore-end -->

### 保険契約情報照会システムマイグレーション

<!-- prettier-ignore-start -->
```yaml
期間: 2019/09 - 2019/11
概要: IE6で動作する既存システムをIE10向けにマイグレーション
プロジェクトメンバー:
    PM: 2人
    PL: 2人
    SE: 4人
    PG: 9人
担当: |-
    PGとしてWebシステム画面のマイグレーションで実装とテストを担当
    その他にUI改善やプロジェクト運営の改善提案も行い
    プロジェクト運営については冗長な手続きの簡略化や、
    自動化可能な業務の自動化を行いました。
使用技術:
    - Windows 10, IE 10, C#.NET 6, ASP.NET 6, SQL Server 2016
    - IIS 10, Redmine
```
<!-- prettier-ignore-end -->

### IoT オーブンレンジ操作 API 開発

<!-- prettier-ignore-start -->
```yaml
期間: 2019/04 - 2019/08
概要: スマホからクラウド経由で操作できるオーブンレンジのAPI新規開発
プロジェクトメンバー:
    PM: 1人
    SE: 4人
    PG: 5人
担当: |-
    PGとして既存別システムのDBの内容を新規システムに流用できるようにデータ解析し、
    マイグレーションを行うためのツールの実装を担当
使用技術: -
    - Windows 10, Python 2.7.3, Jupyter Notebook, Open API 3.0
    - MySQL, Amazon Aurora, AWS, Slack, Azure DevOps, Redmine, Skype
```
<!-- prettier-ignore-end -->

### IoT 家電操作画面開発

<!-- prettier-ignore-start -->
```yaml
期間: 2018/02 - 2019/03
概要: |-
    Windowsを搭載した専用タッチパネル（デジタルサイネージのような外観）から
    クラウド経由でIoT対応家電を操作する画面、APIの開発
プロジェクトメンバー:
    PM: 1人
    SE: 2人
    PG: 2人
担当: |-
    PGとしてIoT家電を遠隔操作する為のWebアプリで画面の実装を担当
    クラウドシステムとのやり取りやOAuth認証機能の設計と実装も行いました
使用技術:
    - Windows 10, Ubuntu 18.04 LTS, TypeScript, Angular 5-7
    - Jasmine, nginx, ffmpeg, GStream, Firebase, Git
```
<!-- prettier-ignore-end -->
