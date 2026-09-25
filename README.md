# karita-site

karita プロジェクト（karita アプリ、ブラウザ拡張「karita に送る」）の公開ドキュメント
（プライバシーポリシー・利用規約）をまとめた静的サイトです。`ptune-site` と同じ構成に
合わせています。

## 概要

- 対象: karita アプリ（Windows / Android）、ブラウザ拡張「karita に送る」（Chrome / Edge）
- 内容: プライバシーポリシー・利用規約のみ（アプリ紹介・チュートリアルは範囲外）
- 技術スタック: MkDocs Material, GitHub Pages

## セットアップ手順

### 1. 必要ツールのインストール（初回のみ）

```bash
# Python3 がインストールされていることを前提
pip install mkdocs-material
```

### 2. ローカルでの動作確認

```bash
git clone https://github.com/getperf/karita-site.git
cd karita-site

mkdocs serve
# 他のアプリが8000ポートを使用している場合
mkdocs serve -a 127.0.0.1:8001
```

## デプロイ方法

```bash
./script/deploy.sh
```

GitHub Pages のカスタムドメインを `karita.getperf.net` に設定し、DNS 側で CNAME を
GitHub Pages 先へ向けること（`CNAME` ファイルはリポジトリに含めてある）。

## ライセンス

MIT
