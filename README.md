# CSV Opener

日本語環境の MS Excel で CSVファイルを文字化けしないよう読み込むアプリケーション

## Setup

1. GitHubの [リリース一覧](https://github.com/Y-Saki26/CSVOpener/releases) から好きなバージョンのリリースを選択し，Assetsから"Source code (zip)"をダウンロードする．
2. Zipファイルを展開し，"CSVOpener.exe" をダブルクリックして起動
    + Windows Defender によって実行がブロックされることがあります．「詳細情報」をクリックし，アプリの内容を確認して「実行」を選択してください．
3. 開きたいCSVファイルを画面にドラッグアンドドロップ

また，ソースコードから直接実行もできます．
[プロデル](https://rdr.utopiat.net/) の実行環境を用意して "src/csv_opener.rdr" を読み込んで実行．同様に動作します．
プロデルでの実行は以下の環境で確認しています．

```
◆動作環境情報◆
プロデル 2.0.1191
Windows 11 Pro 64ビット
メモリ:15.6 GB
```

## 注意

+ 複数ファイルをまとめてドラッグアンドドロップするとそれぞれ新しいウィンドウで読み込まれます．
+ 大きなファイルの展開には時間がかかります．数kB程度以下のサイズを想定しています．
+ 元のCSVファイルとは別で起動するので適宜Excelファイルを保存してください．
