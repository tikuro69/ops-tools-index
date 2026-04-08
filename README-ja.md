# Ops Tools Index

Linux、サーバ運用、トラブルシュート、自動化のための、小さく実用的なツールをまとめた索引です。

このリポジトリは、実務の中で作成したツールをすばやく参照するための個人用カタログであり、同時にポートフォリオの索引でもあります。

---

## 分類

- トラブルシュート / 初動調査
- メール / DNS
- ログ / 監視
- ネットワーク / ファイアウォール
- 設定確認 / 検証
- データ処理 / ユーティリティ
- Web / メモ

---

## トラブルシュート / 初動調査

### [initial_triage_tool](https://github.com/tikuro69/initial_triage_tool)
初動調査のために、基本的なシステム情報を収集するツールです。

- 種別: Python / CLI
- 用途: Linuxサーバが重い、不安定といった状況で最初の調査を行うとき

### [system_snapshot_tool](https://github.com/tikuro69/system_snapshot_tool)
Linuxサーバの状態をすばやく取得し、調査や記録に使えるスナップショットを作成します。

- 種別: Python / CLI
- 用途: 詳細調査に入る前に、現在のシステム状態を素早く記録したいとき

### [migration_prep_tool](https://github.com/tikuro69/migration_prep_tool)
移行、再構築、引き継ぎ作業に必要な情報を整理するためのツールです。

- 種別: Python / CLI
- 用途: サーバ移行や環境再構築の前に、必要な調査情報を整理したいとき

---

## メール / DNS

### [mail_header_probe](https://github.com/tikuro69/mail_header_probe)
メールヘッダを調べ、SPF、DKIM、DMARC などの認証結果を確認するツールです。

- 種別: Python / CLI
- 用途: 不審なメールやなりすましメールの調査をすばやく行いたいとき

### [domain-probe-tool](https://github.com/tikuro69/domain-probe-tool)
DNSレコードや基本的なドメイン設定を確認するツールです。

- 種別: Python / CLI
- 用途: 設定作業や障害対応時にDNS設定を確認したいとき

---

## ログ / 監視

### [log_parser_tool](https://github.com/tikuro69/log_parser_tool)
ログを解析し、頻出する項目を要約して確認できるツールです。

- 種別: Python / CLI
- 用途: 障害調査時にサーバログをすばやく見たいとき

### [cert_expiry_check](https://github.com/tikuro69/cert_expiry_check)
SSL/TLS証明書の有効期限を確認するツールです。

- 種別: Python / CLI
- 用途: 証明書期限切れによるサービス影響を未然に防ぎたいとき

---

## ネットワーク / ファイアウォール

### [iptables-rule-viewer](https://github.com/tikuro69/iptables-rule-viewer)
`iptables -L -n -v` の出力をブラウザで見やすく可視化するツールです。

- 種別: HTML / JavaScript
- 用途: サーバ運用中にファイアウォールルールを見やすく確認したいとき

---

## 設定確認 / 検証

### [nginx_apache_config_linter](https://github.com/tikuro69/nginx_apache_config_linter)
Nginx と Apache の設定ファイルをチェックするツールです。

- 種別: Python / CLI
- 用途: デプロイや移行の前に、単純な設定ミスを見つけたいとき

---

## データ処理 / ユーティリティ

### [csv_tool](https://github.com/tikuro69/csv_tool)
CSVデータを抽出、絞り込み、整形するツールです。

- 種別: Python / CLI
- 用途: 小規模な運用データ処理やCSV整理をすばやく行いたいとき

---

## Web / メモ

### [thought-bag](https://github.com/tikuro69/thought-bag)
小さなアイデアやメモを手軽に集めて整理するためのWebアプリです。

- 種別: Webアプリ
- 用途: ちょっとした考えやメモをひとまとめにしておきたいとき

---

## プロフィール

### [tikuro69](https://github.com/tikuro69/tikuro69)
GitHubプロフィール用のリポジトリです。

- 種別: Profile README
- 用途: 自分の経歴、スキル、主要プロジェクトの概要をまとめて見るため

---

## 補足

- これらのツールは、小さく、用途を絞った実用ツールとして作成しています。
- 多くは実際の運用上の必要性から生まれたものです。
- この索引は、ポートフォリオであると同時に、自分用の作業リファレンスとしても管理しています。
- 今後、新しいツールを追加するたびに更新していきます。

---

## 主な関心領域

- Linuxサーバ運用
- トラブルシュートと障害初動対応
- DNS / メール調査
- ログ解析
- 小規模な自動化ツール
- 実用的なCLIツール