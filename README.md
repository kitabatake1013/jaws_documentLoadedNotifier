# jaws_documentLoadedNotifier

Webページなどの読み込み完了時、クリック音を鳴らしてすぐに内容の読み上げが始まるようにするJAWSスクリプト

## 機能

* Webページなど、仮想バッファを使うアプリケーションにおいて、ドキュメントの読み込みが完了したらクリック音を再生
* 同時に、進行中の読み上げを強制的に停止し、すぐにページの内容を読み始めるようにする

## JAWSへの組み込み

1. `git clone`するなり、`Download ZIP`するなりして、このリポジトリの中身を取得する。
1. `script`ディレクトリの中身を、JAWSの個人設定フォルダにコピーする。
1. `default.jss`に以下を追記して保存・コンパイルする。
   ```
   use "documentLoadedNotifier.jsb"
   ```

## ライセンス

MITライセンスの条件に従い、自由に利用できる。

Copyright (c) 2023 Kazto Kitabatake
