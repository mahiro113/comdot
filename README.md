# comdot

# 概要
コムドットのメンバーのツイート内容を学習し、誰にツイートが一番近いか分類するモデル

# 目的
https://youtu.be/n9Pn0CGckyU
この動画に出てくるアカウントのツイート内容が似ているかを機械的に算出するため。

# 使い方

インストールしてないライブラリがあれば各々でインストールしてください。  
基本的に上からセルを実行するだけです。  
mecabのneologd辞書をインストールをしてない方は関数のpathの部分を消していただければ使えると思います。  
clean_yaci.csvとclean_comdot.csvは前処理後のデータです。  
ツイートデータを集めるのにはapiじゃなくhttps://www.allmytweets.net/connect/ を使いました。  
なので前処理の関数もそれに合わせて作ってます。  
他に調べたい人のツイートがあれば上のサイトから自分でcsvファイルなどにまとめて関数を実行するだけで終わりです。

# 環境
windows  
Anaconda　python 3.8  

# インストールするもの
基本的にpipかcondaで完結します。  
MeCabの準備だけ大変だと思います。
こちらを参考にしてみてください  
https://qiita.com/yukinoi/items/5dfc674c040f6d81a8a1  
https://qiita.com/yukinoi/items/6475285c00f90e802b4b

# csvファイルについて
- comdto.csv 処理前のコムドットのツイートデータ
- clean_comdot.csv 処理後のコムドットのツイートデータ
- yaci.csv 処理前の分類させるためのサンプルデータ
- clean_yaci.csv 処理後のサンプルデータ

## MITライセンス
Copyright (c) 2022年 mahiro
Released under the MIT license
https://opensource.org/licenses/mit-license.php
