# GENBU
## 目的
GENBUはWord2Vecを用いた解析において，グラフを用いて視覚的に単語の関係を明示化するために作られました。

## 使用方法
GENBUはPythonで書かれており，その実行には元となるデータ及びPython本体，いくつかのモジュールの導入が必要になります。  
Pythonやモジュールの導入に関しては以下のURL先を参照してください。  

[Python のセットアップと利用――Python3.10.4ドキュメント](https://docs.python.org/ja/3/using/index.html)  
[Pythonモジュールのインストール――Python3.10.4ドキュメント](https://docs.python.org/ja/3/installing/index.html)  

以下に必要なモジュールと動作確認済みバージョンについて示します。
 
 
gensim v4.2.0  
matplotlib v3.4.0  
mecab-python3 v1.0.3  
networkx v2.5  
PySimpleGUI v4.60.3  

これ以降の内容は気が向いたら書きます。

## 使用したデータについて
動作確認に用いたWord2Vec学習データは，日本語Wikipediaエンティティデータを使用して作成しました。  
このデータはCC BY-SA 4.0の元で公開されています。

GithubのURL: [WikiEntVec](https://github.com/singletongue/WikiEntVec)


## ライセンスについて


「Python」はPython Software Foundationの登録商標です。
