# Liora

**会話から開発、制作、日々の作業まで。PCの中にひとつのAI環境を。**

[English](README.md) · [公式サイト](https://sainoweb.com/ja/products/liora) · [購入](https://sainoweb.com/ja/products/liora#liora-purchase) · [サポート](SUPPORT.md)

![Lioraのチャット画面](screenshots/capture-chat-dark.png)

Lioraは、SAINOが開発するWindows向けAI Hubです。ローカルAI、開発エージェント、音声、記憶、Web検索、制作フロー、PCツールを、ひとつのデスクトップ環境へまとめます。

Windowsソフトのインストール、AIモデルのダウンロード、ローカルAI環境の設定に慣れている方へおすすめします。基本利用ガイドとAI導入ガイドは付属しますが、個別のリモートインストールやPC環境固有の設定代行は含まれません。

## 主な機能

- 用途に応じてOllama、LM Studio、llama.cpp、Codex、Claude Codeを切り替え
- 会話、プロジェクト、長期記憶、ドキュメント検索、Web検索の引用を一か所で管理
- Work Modeでファイル、計画、タスク、Git、テスト、ターミナルを確認
- Creative Modeから対応する画像・動画・音楽生成環境へ接続
- 必要に応じて音声認識、音声合成、MCP、スキル、プラグイン、自動化を追加
- 会話、記憶、設定、ログをWindows上のLiora用ローカル領域へ保存
- 外部連携を個別診断し、問題時はセーフモードで起動

詳しくは[機能一覧](docs/features.md)をご覧ください。

## スクリーンショット

### チャットとローカルAI選択

![LioraのチャットとローカルAI選択](screenshots/capture-chat-dark.png)

### 音声会話

![Lioraの音声会話](screenshots/capture-voice-dark.png)

### Work Mode

![Liora Work Mode](screenshots/capture-work-dark.png)

### Creative Mode

![Liora Creative Mode](screenshots/capture-creative-menu-dark.png)

### 動画制作画面

![Lioraの動画制作画面](screenshots/capture-creative-video-dark.png)

## 提供について

LioraはWindows 10・11向けの商用プロプライエタリソフトウェアです。現在は一般公開インストーラーではなく、Limited Betaとして期限付きの非公開ダウンロードで提供しています。

- 日本国内：**29,800円（税込）**
- 海外：**199 USD**
- ライセンス：購入者1名が管理するWindows PCで利用
- 提供方法：決済確認後、期限付きの非公開ダウンロードURLと導入ガイドを個別提供
- ローカルAIモデル、クラウドアカウント、有料API、第三者サービスの料金は製品価格に含まれません

購入前に[SAINO公式製品ページ](https://sainoweb.com/ja/products/liora#liora-purchase)の要件、未署名インストーラーの注意、利用条件をご確認ください。決済リンクが表示されない期間はお問い合わせをご利用ください。インストーラーはこのリポジトリでは公開しません。

## こんな方におすすめです

- Windows 10または11を利用している
- ソフトウェアを自分でインストールできる
- OllamaやLM StudioなどのローカルAIを利用したい
- AIモデルのダウンロードや設定ができる
- 必要に応じてエラー内容や診断結果を確認できる

購入前に[動作環境](docs/system-requirements.md)をご確認ください。

## インストール時の重要なご案内

現在のインストーラーには**コード署名がありません**。Windows SmartScreenが「認識されないアプリ」と表示する場合があります。SAINOから案内されたファイル名とSHA-256を確認してから、実行するか判断してください。Microsoft DefenderやSmartScreenを全体的に無効化することは推奨しません。

現在の`1.3.0-beta.1` Limited Betaインストーラーで検証済みのSHA-256は次のとおりです。

```text
0C15D1AC2A5C81B6B671860C7F8069F21614641AE41F8758B7AAEA0A49FC0FD1
```

詳しくは[インストールと確認方法](docs/installation.md)をご覧ください。

## プライバシーと外部サービス

会話、記憶、設定、ログは、利用者がクラウドサービスや外部ツールを明示的に使用しない限り、Windows上のローカル領域へ保存されます。外部AI、検索サービス、MCPサーバー、CLI、生成環境には、それぞれのアカウント、データ取り扱い、料金条件が適用されます。

機密情報を扱う場合や強力なPC操作ツールを有効にする場合は、[プライバシーとセキュリティ](docs/privacy-and-security.md)をご確認ください。

## このリポジトリの範囲

このPublicリポジトリに含まれるのは、製品情報、スクリーンショット、利用者向けドキュメントだけです。Lioraのソースコード、インストーラー、内部プロンプト、内部アルゴリズム、ビルド設定、認証情報、開発履歴は含みません。

Lioraは商用プロプライエタリソフトウェアです。

Copyright © SAINO. All rights reserved.
