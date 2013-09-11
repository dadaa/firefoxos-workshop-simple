# firefoxos-workshop-simple
## firefoxos,workshop
This document is made by [gitfab](http://gitfab.org)
---
# 開発環境のセットアップ
Firefox OS Simulator を利用するため、まずは Firefox のインストールを行ってください。後に、Firefox OS Simulator のインストールしてください。
---
#Firefox OS Simulator の起動
Firefox のメニューバー内 ツールから 

* Web 開発 &gt; Firefox OS Simulator

を起動してください。
---
#実機のセットアップ
Simulator と実機をつなぐためのセットアップを行います。Setting アプリケーションを起動し、以下の設定項目にチェックを入れてください。

* Device Information &gt; More Information &gt; Developer &gt; Remote debugging
* Device Information &gt; More Information &gt; Developer &gt; Console enabled

---
# スケルトンのダウンロードと解凍
スケルトンをダウンロードしたのち、解凍してください。

---
# スケルトンのマニフェストを編集
解凍してできたディレクトリ内の manifest.webapp を編集します。好きなテキストエディタを起動し manifest.webapp を開き、自分のアプリ用に修正します。

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


![screenshot-onebutton.png](https://raw.github.com/dadaa/firefoxos-workshop-simple/master/gitfab/resources/screenshot-onebutton.png)
---
