# 案件② 営業支援社内サブシステム開発案件

[bio](../index.md) > [職務経歴](../business.md) > **個人事業主.案件②**

--------------------

Salesforceを利用した `営業支援用社内システム構築案件` における `補助システム` の開発。

## ■案件概要

メインシステム上に構築困難な機能を、Java／SpringBootのAPIサーバとして構築する計画があり。
サブシステム側の技術検証・機能設計・実装からリリースまでを実施した。

### （初期開発）

Salesforceの **パッケージ制約（いわゆるガバナ制限など）** に伴い、メインシステムの構築が難航。  
Salesforce／APEX上に構築しきれない機能を補助システムとして切り出し、単純なAPI機能として提供することになった。  

### （二次開発）

補助システム側の拡張性の高さから、パッケージ制約に関わらず難易度の高いカスタマイズ機能を提供するサブシステムとして昇格。  
メインシステムの改修要件の幾つかをサブシステム側で実現することになった。  

サブシステム改修例
- パッケージアドイン製品のバグ回避のため、請求機能の一部をサブシステムにて実装。
- 某国オフショアに出していた月末バッチ処理に品質問題があり、サブシステムにて実装。
- パッケージで利用していた帳票機能が改修要件を満たせず、サブシステムにて実装。

## ■技術属性

- `主要技術`
  - Java9／SpringBoot＋Thymeleaf＋Bootstrap＋jQuery
  - PostgreSQL
  - POI
  - OpenCSV
  - CAPTCHA, reCAPTCHA
  - CentOS／whitecloud
  - `developer api`
    - Salesforce API
    - Zuora API
    - LINE Works API／developer-console
    - GSuite API／developer-console
- `ツール類`
  - STS (spring tool suite)
  - VCS
    - git／Backlog
    - SourceTree
  - Slack
  - Backlog
  - PrimeDrive
- `その他`
  - A5SQL-mk2
  - ER-Master
