## 概略

中学生の頃に自分のホームページを持ち、それから Web 関連を趣味としてきました。  
元々開発を始めた切欠は PHP で、何度も同じ HTML を書くのが大変というところから、  
そこを自動化出来ないかと言った所ではじめました。  
この辺りの関係で TCP/IP やネットワークの仕組みというのはある程度理解しています。  
また、プログラミングの基礎として C 言語を学んだ事もあり、  
他の言語や FW がどのような仕組みで動いているのかなどもある程度理解しています。

社会人になってからは SES を通して SIer で、Windows システムや Web システムの開発に従事してきました。  
一番良く取り組んだのは、やはり自動化で、実装コードの自動生成や、  
テストデータの自動生成を良くしており、開発メンバーにも布教していました。  
またプロジェクトの管理についても、破綻したプロジェクト管理に対して  
改善提案を挙げ、提案を採用していただくこともありました。

実務で必要な技術については、実務中は勿論、プライベートでも触り、  
特に公式のリファレンスを参考にし、何か作ってみるなどで理解を深めるようにしています。

経験的にはレガシーからモダン、サーバーサイドからフロントエンドまで幅広く経験しており  
その周りは卒なくこなせます。

最近では CI、タスクランナーや自動テストなどにも興味があり、  
趣味は勿論、実務でも提案し、使わせてもらうことがあります。

またチーム開発においては、  
しつこすぎる程のコミュニケーションを心がけるようにしています。

また、これからはエンジニアとしての実務経験を今より積み上げて自身の価値を向上していきたく、  
新しい技術や技術だけでなく経験のない分野での挑戦もさせて頂ける環境で活躍していければと考えております。

<div class="page-break"></div>

## スキルシート

<!-- prettier-ignore-start -->
```yaml
基本的に問題ない:
    - JavaScript
    - TypeScript
    - PHP
    - C#.NET
    - SQL
    - Git
    - SVN
    - 正規表現
    - Windows

調べながらなら可能:
    - Node.js
    - Vue.js
    - Angular
    - RxJS
    - Laravel
    - Python
    - HTML5/CSS2
    - Linux
    - Apache

触ってみた程度:
    - Jasmine
    - Firebase
    - nginx
    - GitHub Actions
    - Docker
    - Java
    - React
    - Jest
    - C言語
    - WordPress
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

## 業務経歴

### 派遣スタッフ管理システムリプレース

<!-- prettier-ignore-start -->
```yaml
期間: 2020/04 - 現在
概要: 派遣会社の人員が担当する派遣スタッフの勤怠や契約の管理を行う画面と、そのAPIのリプレース
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    PG: 8人
担当:
    PGとして詳細テスト、サーバーサイド、クライアントサイドの機能実装、結合テスト
    UI改善や自動テストやLintingなどの提案を行い、幾つか採用されました。
    またブランチ管理に関しては一部私の意見を反映させて頂きました。
使用技術:
    - Nuxtjs 2.0.0
    - JavaScript
    - Laravel 5.6
    - PHP 7.1.3
    - SQL Server 2017
    - Apache
    - CentOS 7.7
    - Docker
    - Git
    - GitLab
    - Windows 10
    - Google Chrome
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

### 生産管理システムプロト作成

<!-- prettier-ignore-start -->
```yaml
期間: 2020/03 - 2020/04
概要: 既存の生産管理で数値化されていない部分を集計し、可視化するためのシステムのプロト開発
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    PG: 1人
担当:
    PGとしてMQTT等の各種プロトコルを利用し、
    生産機器からデータを吸い上げ、DBに登録する内容の実装
    またそれらの技術調査を行いました。
使用技術:
    - C#.NET 2019
    - Windows Form
    - MQTT
    - GitHub
    - GitHub Actions
    - Windows 10
```
<!-- prettier-ignore-end -->

### 美容室向けのサブスクリプションサービス開発

<!-- prettier-ignore-start -->
```yaml
期間: 2020/03
概要:
    iOSアプリを利用した美容室向けのサブスクリプションサービスの開発
    このプロジェクトは副業として個人で受託しました。（Twitter経由）
プロジェクトメンバー:
    PM: 1人
    PG: 1人
担当:
    PGとして以下のAPI機能のプロト開発について、要件定義～テストまでを行いました。
    ユーザー登録・更新・削除、決済情報のStripe連携、各種アクションに対するメール送信
    ユーザーが購読するサブスクリプションプランの選択
    美容室の予約
使用技術:
    - Laravel 6.0
    - PHP 7.2
    - Stripe
    - GitHub
    - AWS
    - Postman
    - VSCode
    - Windows 10
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

### 低レベル放射性廃棄物埋設管理システムマイグレーション

<!-- prettier-ignore-start -->
```yaml
期間: 2019/12 - 2020/02
概要:
    Windows NT4, VB6, Oracle 8, SPREAD 2.5で動作する既存システムを
    Windows10, VB.NET 2019, Oracle 12c, SPREAD 12J向けにマイグレーション
プロジェクトメンバー:
    PM: 1人
    PL: 1人
    PG: 8人
担当:
    PGとして項目数が数十程度のC/Sシステムの画面、帳票、サーバーの実装
    他にプロジェクト運営の改善提案も行いました。
使用技術:
    - Windows Form
    - VB 6.0
    - VB.NET 2019
    - SPREAD 2.5
    - SPREAD 12J
    - ActiveReports 12J
    - Oracle 8
    - Oracle 12c
    - Git
    - Windows 10
    - Windows NT4
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
担当:
    PGとしてWebシステム画面のマイグレーションで実装とテストを担当
    他にプロジェクト運営の改善提案も行いました。
    主に冗長な手続きの簡略化や、自動化可能な業務の自動化を行いました。
使用技術:
    - Windows 10
    - IE 10
    - C#.NET 6
    - ASP.NET 6
    - SQL Server 2016
    - IIS 10
    - Redmine
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

### IoT オーブンレンジ操作 API 開発

<!-- prettier-ignore-start -->
```yaml
期間: 2019/04 - 2019/08
概要: スマホからクラウド経由で操作できるオーブンレンジのAPI新規開発
プロジェクトメンバー:
    PM: 1人
    SE: 4人
    PG: 5人
担当:
    PGとして既存別システムのDBの内容を新規システムに流用できるようにデータ解析し、
    マイグレーションを行うためのツールの実装を担当
使用技術:
    - Windows 10
    - Python 2.7.3
    - Jupyter Notebook
    - Open API 3.0
    - MySQL
    - Amazon Aurora
    - AWS
    - Slack
    - Azure DevOps
    - Redmine
    - Skype
```
<!-- prettier-ignore-end -->

### IoT 家電操作画面開発

<!-- prettier-ignore-start -->
```yaml
期間: 2018/02 - 2019/03
概要:
    Windowsを搭載した専用タッチパネル（デジタルサイネージのような外観）から
    クラウド経由でIoT対応家電を操作する画面、APIの開発
プロジェクトメンバー:
    PM: 1人
    SE: 2人
    PG: 2人
担当:
    PGとしてIoT家電を遠隔操作する為のWebアプリで画面の実装を担当
    クラウドシステムとのやり取りやOAuth認証機能の設計と実装も行いました
使用技術:
    - Windows 10
    - Ubuntu 18.04 LTS
    - TypeScript
    - Angular 5-7
    - HTML5
    - CSS3
    - Jasmine
    - nginx
    - ffmpeg
    - GStream
    - Firebase
    - Git
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

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
    - Windows 7
    - Vue.js 2.5.6
    - bootstrap 4
    - CoreUI 1.0.6
    - VSCode
    - Git
```
<!-- prettier-ignore-end -->

### デマンドレスポンスシステム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2017/10 - 2017/12
概要: 経済産業省と関西電力が推進するデマンドレスポンスの実証実験用システムの開発
プロジェクトメンバー:
    PG: 1人
担当:
    電力会社と電力制御事業者間でスケジュールに沿って
    電力制御電文の送受信を行うサーバーシステム・管理用のWeb画面の設計、実装、テストを担当
    こちらはエンドユーザーから要件をヒアリングし単独で開発しました
使用技術:
    - Windows 8.1
    - Ubuntu 14.04
    - C#.NET
    - VB.NET
    - ASP.NET
    - Quartz.NET
    - OpenADR
    - DB2
    - SQL Server 2017
    - Visual Studio
    - IIS
    - Git
```
<!-- prettier-ignore-end -->

### 重機生産部品在庫管理システムリプレース

<!-- prettier-ignore-start -->
```yaml
期間: 2017/06 - 2017/09
プロジェクトメンバー: 6人
担当: ERPシステムの改修でサーバー部分の実装を担当
使用技術:
    - Windows XP
    - VB6.0
    - ENOVIA
    - Oracle
    - VSS
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

### 生産管理システム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2017/04 - 2017/05
プロジェクトメンバー: 8人
担当: C/Sシステムのクライアント画面の新規開発で実装を担当
使用技術:
    - Windows 7
    - C#.NET
    - Oracle
    - Visual Studio
    - SVN
    - Skype
```
<!-- prettier-ignore-end -->

### 製薬会社売上管理システムマイグレーション

<!-- prettier-ignore-start -->
```yaml
期間: 2017/01 - 2017/03
プロジェクトメンバー: 4人
担当: VB6で開発された画面をWeb画面にマイグレーションする内容で画面実装を担当
使用技術:
    - Windows 10
    - VB.NET
    - ASP.NET
    - HTML
    - jQuery
    - Access
    - Visual Studio
    - IIS
    - SVN
```
<!-- prettier-ignore-end -->

### 非鉄金属先物取引予測システムリプレース

<!-- prettier-ignore-start -->
```yaml
期間: 2016/07 - 2016/12
プロジェクトメンバー: 10人
担当: C/Sシステムのクライアント画面の新規開発で詳細設計、実装、単体テストを担当
使用技術:
    - Windows 7
    - VB.NET
    - SQL Server
    - Visual Studio
    - SVN
```
<!-- prettier-ignore-end -->

### 自動車生産部品在庫管理システム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2016/05 - 2016/06
プロジェクトメンバー: 10人
担当: C/Sシステムの新規開発でクライアント画面やバッチプログラムの実装を担当
使用技術:
    - Windows 7
    - C#.NET
    - バッチ（コマンドプロンプト）
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

### 在庫管理システム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2015/12 - 2016/02
プロジェクトメンバー: 6人
担当: クライアントシステムの画面、帳票の実装を担当
使用技術:
    - Windows 7
    - VB.NET
    - SPREAD
    - Oracle
    - Visual Studio
    - SVN
```
<!-- prettier-ignore-end -->

### 官公庁内部システム保守開発

<!-- prettier-ignore-start -->
```yaml
期間: 2014/04 - 2014/11
プロジェクトメンバー: 20人
担当: C/Sシステムの開発資源の構成管理を担当。上がってきたソースコードのマージ、ビルド、コミットなど
使用技術:
    - Windows 7
    - VB.NET
    - Java
    - Terasoluna
    - SVN
```
<!-- prettier-ignore-end -->

### テレビ会議アプリ開発

<!-- prettier-ignore-start -->
```yaml
期間: 2014/01 - 2014/03
プロジェクトメンバー: 5人
担当: Windows上で動作する画面アプリのシナリオ・ストレステストを担当
使用技術:
    - Windows Vista
    - Windows 7
    - Windows 8
    - UWSC
    - SQLite
```
<!-- prettier-ignore-end -->

### 生命保険契約照会 Web システム開発

<!-- prettier-ignore-start -->
```yaml
期間: 2013/11 - 2013/12
プロジェクトメンバー: 100人超
担当: IE上で動作するWebシステムの画面結合テストを担当
使用技術:
    - Windows 7
    - IE
    - Oracle
```
<!-- prettier-ignore-end -->

<div class="page-break"></div>

### 流通システムマイグレーション

<!-- prettier-ignore-start -->
```yaml
期間: 2013/09 - 2013/10
プロジェクトメンバー: 4人
担当: Windows上で動作するC/Sシステムの画面結合テストを担当
使用技術:
    - Windows 7
    - VB6.0
    - VB.NET
    - Oracle
```
<!-- prettier-ignore-end -->