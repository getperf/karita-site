# ブラウザー拡張「karita に送る」の入れ方

カーリルや図書館のサイトから、本の URL を同じ Windows 端末の karita へ送るための拡張です。
Windows セットアップの **手順4：ブラウザーとつなぐ** です。先に [手順1〜3：本体のインストール・初期設定](../guide/windows/setup.md)を済ませてください。
拡張の導入と連携確認が終わったら、[手順5：図書館を登録する](../guide/windows/libraries.md)へ進みます。

## 1. ストアから入れる

拡張を入れるブラウザーを先に起動してください。下の URL をコピーし、そのブラウザーのアドレスバーへ貼り付けて Enter キーを押します。
拡張はブラウザーごとにインストールします。ZIP の展開や開発者モードの設定は不要です。

=== "Edge"

    1. **Microsoft Edge** を起動します。
    2. 次の URL をコピーし、**Edge のアドレスバー**へ貼り付けて Enter キーを押します。

        ```text
        https://microsoftedge.microsoft.com/addons/detail/hihnlcmokajbhleeediopaoflkllmgaa
        ```

    3. 名前が **karita に送る**、提供元が **Getperf** であることを確認します。
    4. ページのインストールボタンを押し、表示されるアクセス内容を確認して追加します。

=== "Chrome"

    1. **Google Chrome** を起動します。
    2. 次の URL をコピーし、**Chrome のアドレスバー**へ貼り付けて Enter キーを押します。

        ```text
        https://chromewebstore.google.com/detail/apkcdfgkmojfmgenockhgddmjcjpbphp
        ```

    3. 名前が **karita に送る** であることを確認します。
    4. ［Chrome に追加］を押し、表示されるアクセス内容を確認して追加します。

=== "Firefox"

    Firefox 142 以降が対象です。

    1. **Mozilla Firefox** を起動します。
    2. 次の URL をコピーし、**Firefox のアドレスバー**へ貼り付けて Enter キーを押します。

        ```text
        https://addons.mozilla.org/ja/firefox/addon/karita-%E3%81%AB%E9%80%81%E3%82%8B/
        ```

    3. 名前が **karita に送る**、提供元が **Getperf** であることを確認します。
    4. ［Firefox へ追加］を押し、表示されるアクセス内容を確認して追加します。

## 2. ツールバーに出す（ピン留め）

入れた直後は、拡張のボタンがメニューの中に隠れている場合があります。

| ブラウザー | 操作 |
|---|---|
| Edge | ツールバーの **拡張機能**（パズルの形）→「karita に送る」をツールバーに表示する設定を選ぶ |
| Chrome | ツールバーの **拡張機能**（パズルの形）→「karita に送る」の **ピン** を押す |
| Firefox | ツールバーの **拡張機能**（パズルの形）→「karita に送る」の **歯車** →「ツールバーにピン留め」 |

ツールバーに karita のアイコンが出れば完了です。

## 3. 送って確かめる

karita のブラウザープラグインの案内から確認用ページを開くか、
[確認用ページ](check.md) を開いて、ページの案内どおりに送ってください。
外部アプリを開く確認が表示された場合は、karita を開く操作を許可します。
karita に **「つながりました」** と出れば完了です。

図書館のサイトで元のカーリル書籍を送る場合は、追加でカーリルの読み取り許可を求められることがあります。用途と操作は [確認用ページ](check.md) に記載しています。

## うまくいかないとき {#trouble}

[困ったとき：拡張を追加できない・送れない](../guide/troubleshooting.md#extensions)を確認してください。

## 次へ：図書館を登録する

連携確認が済んだら、karita の画面へ戻って［次へ］を押します。続けて、図書館と常用館を登録します。

[← 前へ：1〜3. インストール・初期設定](../guide/windows/setup.md)　[次へ：5. 図書館を登録する →](../guide/windows/libraries.md)
