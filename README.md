# karita-site

karita プロジェクト（karita アプリ、ブラウザ拡張「karita に送る」）の公開ドキュメント
（プライバシーポリシー・利用規約）をまとめた静的サイトです。`ptune-site` と同じ構成に
合わせています。

## 概要

- 対象: karita アプリ（Windows / Android / iOS）、ブラウザ拡張「karita に送る」（Chrome / Edge）
- 内容: プライバシーポリシー・利用規約、ブラウザー拡張の入れ方と連携確認ページ（`/extensions/`・`/extensions/check/`。karita アプリが直接開く URL なので、パスを変えない）
- ガイド構成: `docs/setup/`（端末別セットアップ）、`docs/guide/`（予約・貸出し・本棚など機能別の使い方）。予約だけは手順の順序が違うため `reserve-windows.md` / `reserve-smartphone.md` に分ける。2026-11 の再編前の URL は `mkdocs-redirects` で転送する（`mkdocs.yml` の `redirect_maps`）
- 技術スタック: MkDocs Material, mkdocs-redirects, GitHub Pages

## セットアップ手順

### 1. 必要ツールのインストール（初回のみ）

```bash
# Python3 がインストールされていることを前提
pip install mkdocs-material
```

**uv を使う場合**（動作確認済み。ローカル専用で、CI は上の `requirements.txt` を使う）:

```bash
uv venv
uv pip install -r requirements.txt
```

`pyproject.toml` / `uv.lock` はコミットしない。依存の正本は `requirements.txt`
（GitHub Actions もこちらを読む）の1本に保ち、`uv` はローカルの実行環境を作るためだけに
使う。

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
