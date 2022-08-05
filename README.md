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

(1).まずデータを作成します。genbu/experience.pyのコードをエディタで開き，中にある変数"model_path"を任意の値に書き換えて，実行します。なお**必ずexperience.py及びmain.pyは同じディレクトリ内に置いてください。**

(2).main.pyを実行して，ちゃんと読み込めるか確認します。

これ以降の内容は気が向いたら書きます。

## 使用したデータについて
動作確認に用いたWord2Vec学習データは，日本語Wikipediaエンティティデータを使用して作成しました。  
このデータはCC BY-SA 4.0の元で公開されています。

GithubのURL: [WikiEntVec](https://github.com/singletongue/WikiEntVec)

## 推奨スペック
推奨スペックを満たさない環境を用いた場合，**最悪落ちます**。  

CPU: Intel Core i5 相当  
メモリ: 8GB 以上  
OS: Window10 以上

## ライセンスについて
コードはMITライセンスの元配布されます。


※「Python」はPython Software Foundationの登録商標です。
