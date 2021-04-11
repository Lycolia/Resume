## 概要

現在、SES を通して SIer で開発業務を⾏っているプログラマです。  
直近では Laravel や Vue.js、Angular を使った Web 系の開発を行っております。

具体的には主に二次受け以降の SIer で PG として実装作業を主にしております。

## 実務経験スキル

-   開発言語・FW

    -   JavaScript, Node.js, TypeScript, Vue.js, Nuxt.js, Angular, jQuery  
        PHP, Laravel, Python, C#.NET, VB.NET, VB6

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
        -   React, Jasmine, Jest, C 言語, Golang, mongodb

<div class="page-break"></div>

## 意識していること

普段から意識してやっている習慣などについてです。

### 使いづらい UI の改善提案

チームメンバーや可能であればエンドユーザーにもヒアリングし、  
使いづらい UI を使いやすくするための提案をしています。

これは使いづらいシステムは操作ミスが起こりやすかったり、  
そもそも使われなかったりするのではないかと考えていて、  
最終的にユーザーに価値を届けられないと考えているからです。

### 可読性を意識したコーディング

当たり前のことではありますが、リーダブルであるように変数や関数を命名し、  
コメントもその開発のレベルに合わせて書くようにしています。

また可能であれば Linter を導入し、不適切なコードを自動で修正するようにもしています。  
（勿論他者のコードには影響させないようにしています）

### セルフソースレビュー

Git であれば PUSH 前、SVN であればコミット前に自分でコードレビューを行い、  
既存のコードを壊していないか、誤ったコードを書いていないかを確認しています。  
（勿論 Git でもコミット前に最低限の確認はします。）

### 開発の効率化

UnitTest を書くとか、手動テストの一部を UI 自動化ツール で行うなど、  
人間が手でやると時間がかかる上、ミスが発生しやすいものについては、積極的に自動化しています。  
また、最近ではそれらの導入も提案しています。

またやや異なりますが、プロジェクト内のコミュニケーションについても  
管理ツールがないとか、そもそもプロジェクト管理が崩壊しているなどあれば  
それに対し、何をどのようにするとこのくらい改善しますといった形で  
提案をさせていただくことがあります。

### 技術のアウトプット

業務や趣味を通じて得た内容を Qiita や GitHub などにアウトプットするようにしています。  
これはアウトプットしていく中で自分の記憶に落とし込みやすいことや、  
新たな課題を見つけられることがあるからです。

## 経験のないこと

主に要件定義や基本設計、実装環境ありきでの開発を主として来たため、  
それらを行う事については経験がありません。

但し挑戦させて頂けるなら積極的に取り組みたいと考えています。  
過去にも案件ごとに今まで経験のない技術のキャッチアップなどはしてきたので、対応は可能と考えています。

<div class="page-break"></div>

## 職務経歴

携わった案件が極めて多いため、直近のみピックアップしています。

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
    PGとして以下のAPI機能のプロト開発について、要件定義～テストまでを行いました。
    ユーザー登録・更新・削除、決済情報のStripe連携、各種アクションに対するメール送信
    ユーザーが購読するサブスクリプションプランの選択
    美容室の予約
使用技術:
    - Laravel 6.0, PHP 7.2, Stripe, GitHub, AWS, Postman, VSCode, Windows 10
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

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

<div class="page-break"></div>

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

### 日本酒銘柄管理システム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2018/01 - 2018/01
概要: 日本酒の一升瓶を差し込むことで酒柄を読み取る装置の開発
プロジェクトメンバー:
    SE: 1人
    PG: 1人
担当: PGとして日本酒の銘柄の登録削除更新を行う画面の実装を担当
使用技術:
    - Windows 7, Vue.js 2.5.6, bootstrap 4, CoreUI 1.0.6, VSCode, Git
```
<!-- prettier-ignore-end -->

### デマンドレスポンスシステム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2017/10 - 2017/12
概要: 経済産業省と関西電力が推進するデマンドレスポンスの実証実験用システムの開発
プロジェクトメンバー:
    PG: 1人
担当: |-
    電力会社と電力制御事業者間でスケジュールに沿って
    電力制御電文の送受信を行うサーバーシステム・管理用のWeb画面の設計、実装、テストを担当
    こちらはエンドユーザーから要件をヒアリングし単独で開発しました
使用技術:
    - Windows 8.1, Ubuntu 14.04, C#.NET, VB.NET, ASP.NET, Quartz.NET
    - OpenADR, DB2, SQL Server 2017, Visual Studio, IIS, Git
```
<!-- prettier-ignore-end -->
