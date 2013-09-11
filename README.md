# firefoxos-workshop-simple
## firefoxos,workshop
This document is made by [gitfab](http://gitfab.org)
---
# 開発環境のセットアップ
Firefox OS Simulator を利用するため、まずは Firefox のインストールを行ってください。後に、Firefox OS Simulator のインストールしてください。
---
#Firefox OS Simulator の起動
Firefox のメニューバー内 ツールから 

* Web 開発 > Firefox OS Simulator

を起動してください。
---
#実機のセットアップ
Simulator と実機をつなぐためのセットアップを行います。Setting アプリケーションを起動し、以下の設定項目にチェックを入れてください。

* Device Information > More Information > Developer > Remote debugging
* Device Information > More Information > Developer > Console enabled

---
# スケルトンのダウンロードと解凍
スケルトンをダウンロードしたのち、解凍してください。

---
# スケルトンのマニフェストを編集
解凍してできたディレクトリ内の manifest.webapp を編集します。好きなテキストエディタを起動し manifest.webapp を開き、自分のアプリ用に修正します。

マニフェストファイルの説明はこちらにあります。
[https://developer.mozilla.org/ja/docs/Web/Apps/Manifest](https://developer.mozilla.org/ja/docs/Web/Apps/Manifest)
---
