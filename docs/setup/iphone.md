# iPhone のセットアップ

**TestFlightで公開テスト中です。どなたでも参加できます。App Storeでの一般公開は準備中です。**

<div class="karita-flow" aria-label="iPhone セットアップの流れ">
<div><b>① インストールする</b><br>TestFlight から karita を入れる</div><span>↓</span>
<div><b>② karita を始める</b><br>Google にサインインし、図書館・常用館を登録する</div><span>↓</span>
<div><b>③ 共有メニューに karita を出す</b><br>Safari・Chrome の共有から本を送れるようにする</div>
</div>

## 1. TestFlight からインストールする {#testflight}

iOS 15以降のiPhoneで行います。

1. iPhoneに[TestFlight](https://apps.apple.com/jp/app/testflight/id899247664)をインストールします。
2. iPhoneで公開リンク <https://testflight.apple.com/join/BQGbGq5b> を開きます。
3. TestFlightの画面で［同意する］→［インストール］を押します。

- 新しい版は、TestFlightアプリから届きます。
- テスト版には使用期限があります。期限が近づいたら、TestFlightアプリから新しい版を入れてください。
- 「新規テスターを受け付けていません」と表示されたときは、募集を一時的に止めています。時間をおいてお試しください。

## 2. karita を始める {#start}

karitaを起動し、ご自身のGoogleアカウントでサインインします。

- **初めて使う場合**：［新しく始める］を選び、画面の案内に沿って図書館・常用館を登録します。
- **ほかの端末の記録を使う場合**：元の端末で同期を済ませ、同じGoogleアカウントで［合流する］を選びます。同期後、既存の記録が表示されることを確認してください。

端末追加のために初期化やバックアップ復元は行いません。[同期・バックアップ・復元](../guide/data.md)を参照してください。

## 3. 共有メニューに karita を出す {#share}

iPhoneにはブラウザー拡張がないため、**SafariまたはChromeの共有**からカーリルの本をkaritaへ送ります。karitaは最初、共有メニューの［その他］の中にあるため、よく使う項目へ追加します。

1. **【Safari・Chrome】** [カーリル](https://calil.jp/)で本を検索し、本の詳細ページを開きます。
2. 共有ボタンを押します。Safariは画面下部または［…］の中、Chromeはアドレスバー右端にあります。
3. アプリの列を右端まで送り、［その他］→［編集］を押します。
4. 「候補」のkaritaの［＋］を押し、「よく使う項目」に追加します。
5. 並べ替えのつまみで上に移動し、［完了］を押します。
6. 共有メニューのアプリの列からkaritaを押し、karitaの「予約」画面に本が届くことを確認します。

=== "Safari"

    ![Safariの共有メニューでkaritaを選ぶ画面例](../img/guide/ios-share-safari.png){ width="320" }

=== "Chrome"

    ![Chromeの共有メニューでkaritaを選ぶ画面例](../img/guide/ios-share-chrome.png){ width="320" }

画面例は、karitaを「よく使う項目」に追加した状態です。設定は端末ごとに一度行います。表示や並びはiOS・ブラウザーの版によって異なります。

## 次へ：本を予約する

[次へ：図書を予約する（Android・iPhone） →](../guide/reserve-smartphone.md)

## 操作を試して感想を送る {#feedback}

2週間ほど、実際の図書館の予約・貸出しの記録に使っていただけると助かります。

### 感想・要望はフォームから送る {#feedback-form}

使ってみた感想や、あったらよい機能は[karita テストのアンケート](https://docs.google.com/forms/d/e/1FAIpQLSc8eWl6bRgsW01X4ZjHz1cAIGV3uSGmEz0dZIQ6MBS0LDBTxQ/viewform)からお送りください。TestFlightから送れないときの不具合の報告にも使えます。

### 不具合は TestFlight からも送れる {#feedback-testflight}

画面の表示がおかしいときや、操作が進まないときに使います。端末・iOS・karitaの版が自動で添えられます。

1. その画面でスクリーンショットを撮ります。
2. 左下に出る小さな画像を押し、［共有］→［ベータ版のフィードバックを送信］を選びます。
3. 操作した手順と、表示されたメッセージを書いて送信します。

スクリーンショットを撮らずに送るときは、TestFlightアプリでkaritaを開き、［ベータ版のフィードバックを送信］を押します。karitaが突然終了したときに送信を確認する画面が出たら、そのまま送信してください。

メールアドレスを入力しない限り、送り主は開発者に匿名で表示されます。画像の個人情報（図書館の利用者番号など）は、送る前に隠してください。

ご質問は [furu3@getperf.net](mailto:furu3@getperf.net) へお問い合わせください。

[困ったとき](../guide/troubleshooting.md#book-handoff)
