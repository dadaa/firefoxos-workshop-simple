# firefoxos-workshop-simple
## firefoxos,workshop
This document is made by [gitfab](http://gitfab.org)
---
#サムネイル
![keon.JPG](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/keon.JPG)

---
# 開発環境のセットアップ
Firefox OS Simulator を利用するため、まずは Firefox のインストールを行ってください。後に [Firefox OS Simulator](https://addons.mozilla.org/ja/firefox/addon/firefox-os-simulator/) をインストールしてください。
---
#Firefox OS Simulator の起動
Firefox のメニューバー内 ツールから 

* Web 開発 &gt; Firefox OS Simulator

を起動してください。
---
# スケルトンのダウンロードと解凍
スケルトンをダウンロードしたのち、解凍してください。


[skeleton.zip](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/skeleton.zip)
---
# マニフェストを編集
解凍してできたディレクトリ内の manifest.webapp を編集します。テキストエディタで manifest.webapp を開き、自分のアプリ用に修正します。

マニフェストファイルの説明はこちらにあります。
[https://developer.mozilla.org/ja/docs/Web/Apps/Manifest](https://developer.mozilla.org/ja/docs/Web/Apps/Manifest)
---
# アプリをシミュレータに追加する
Simulator 上 Add Directory ボタンを押すと、ファイルチューザが開くので、先ほど修正した manifest.webapp を選択します。

![add-app.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/add-app.png)
---
# アプリを起動する
追加されたアプリにある Refresh ボタンを押すと、シミュレータが起動され、アプリも同時に起動する。

![boot-app.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/boot-app.png)
---
# 起動画面


![screenshot-app.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/screenshot-app.png)
---
# ボタンを追加してみましょうか。
index.html をテキストエディタで開き、button 要素を追加。クリックイベントをトリガーし、アラートを出してみましょう。



[add-button.html](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/add-button.html)
---
# スクリーンショット
以下はアラートのスクリーンショットです。

![screenshot-onebutton.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/screenshot-onebutton.png)
---
# 実機で起動してみましょう
* 実機のセットアップ
* USB での接続
* PUSH
* 確認
* やったね。
---
#実機のセットアップ
Simulator と実機をつなぐためのセットアップを行います。Setting アプリケーションを起動し、以下の設定項目にチェックを入れてください。

* Device Information &gt; More Information &gt; Developer &gt; Remote debugging
* Device Information &gt; More Information &gt; Developer &gt; Console enabled

---
# USB で接続
USB で実機と開発マシンを接続します。接続すると Simulator 上では、デバイスが接続されたことを示す Device Connected およびアプリ付近には、実機へのアップロードを促す Push ボタンが表示されています。

![connected.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/connected.png)

![push.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/push.png)
---
# 実機にアップロード
Push ボタンを押し、実機にアップロードします。

---
#実機で起動できていることを確認
![keon.JPG](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/keon.JPG)

---
# 実機におけるデバッグ
現状ではシミュレータによるリモートデバッグはしづらい状況にあります。

解決策として、以下のページにように [Android Developer Tools](http://developer.android.com/sdk/index.html) を介して、console.log などのデバッグ文を受け取ることが可能になります。

[https://github.com/dynamis/firefoxos/wiki/apps#how-to-install-adb](https://github.com/dynamis/firefoxos/wiki/apps#how-to-install-adb)

---
# おつかれさまでした！
---
