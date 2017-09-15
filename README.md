# Node.js_bs-demo
Browser-Syncでブラウザ同期

## このサンプル制作時の環境
* Windows10 Pro、64bit、32GB

## 事前に用意するもの
* Node.js（本サンプル制作時はv8.4.0）

## 開発手順（win:cmd、mac:tarminal）
1. npm install （package.jsonにあるライブラリがインストールされる）
2. npm start （package.jsonのstartコマンドが実行される。終了は ctrl+C 。）

## npm installでインストールされるライブラリ
* browser-sync

## gulpで実行されること
* publicフォルダ内のindex.htmlがブラウザで開かれる
* browser-syncでLiveReload
* ローカルエリアや外部接続可能なURLが表示される

## 参考リンク
* [【CSS Nite】Browser-Syncについてライトニングトークしてきました【フォローアップ】 | EXP - クリエイティブな事をはじめた(い)全ての人達へ](http://wp-e.org/2014/12/18/5385/)
* [Browser-Syncの使い方 &#8211; A Memorandum](https://protean.cc/how-to-use-browser-sync)

## 知っておくと便利なnpmコマンド一覧
* `npm root -g` … グローバルのルート（node_modules）を調べる
* `npm root` … プロジェクトのルート（node_modules）を調べる
* `npm ls -g --depth=0` … グローバルにインストールされているパッケージを確認
* `npm ls --depth=0` … プロジェクトにインストールされているパッケージを確認
* `npm init -y` … package.jsonをプロジェクトに生成（オプション「-y」が全てyes回答のショートカット）
* `npm install xxxxx --save` … プロジェクトにパッケージをインストールし、情報を「package.json」に書き込む（dependencies）
* `npm i xxxxx -s` … 上記のショートカットキーバージョン
* `npm install xxxxx --save-dev` … プロジェクトにパッケージをインストールし、情報を「package.json」に書き込む（devDependencies-開発用）
* `npm i xxxxx -D` … 上記のショートカットキーバージョン
* `npm -v` … npmのバージョンを表示
* `npm run` … package.json - scriptに記載した一覧が見れる
* `npm show` … package.jsonを表示
* `npm remove -g xxxxx` … グローバルのパッケージをアンインストール
* `npm remove xxxxx` … プロジェクトのパッケージをアンインストール
