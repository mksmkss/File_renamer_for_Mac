# File_renamer
このrenamerを使えば、課題提出時に面倒な名前を変える手間を減らすことができます。

## ダウンロード

右のタブにあるReleasesから最新のものを選択しZIPファイルをダウンロードして解凍してください。

## 事前準備

1. デスクトップに「rename」など適当な名前のフォルダーを作ります。
2. mac標準のテキストエディタ等でprofile.txtを作成し、フォルダー内にfile_renameと共に入れます。<br>変更した際保存を忘れずにしてください。
**<span style="color:yellow">この時、名前はprofile.txtでないとエラーが起きます。</span>**
3. profile.txtを開き、名前と学籍番号を入れます。
この時、一行目は学籍番号、二行目には名前を入れます。
4. file_rename_macを右クリックまたは二本指でタップし、コンテキストメニューを開きます。「Option　Key」を押し「コピー」となっているところが「"file_rename_mac"のパス名をコピー」になったらクリックします。
5. ターミナルを開き、以下のコマンドを打ちこんで、「Enter Key」を押し実行します。<br>
`chmod u+x (ここに4でコピーしたパスをペースト）`<br>
unix実行ファイルとして認識されていれば成功です。

## 使い方

1. file_rename_macを開きます。
2. Fileから変更したいファイルを選択します。どんな拡張子のファイルでも使用可能です
3. Customeを選択し「Apply」します
4. Task nameには、「課題_1」や「力学課題」のようなものを入れてください。
5. 「Enter Key」または「Rename」を押すと実行され、選択したファイルの名前が「課題名_学籍番号_名前.(拡張子)」に変更されます。

## 注意点

unix実行ファイルですので、macでのみ実行可能です。
windowsの方は[こちら](https://github.com/mksmkss/File_renamer_for_Win)

## 作成者

mksmkss

## ライセンス

This file is released under the MIT License, see LICENSE.txt.

