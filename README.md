# Deep Learning Bacic 2023
 

本コードは、
Deep Learning基礎講座 2023の最終課題で提出したものとなります。

## 各ファイルの説明

### 事前準備
- 00_word_count.ipynb
    - 単語の出現頻度を把握

### 画像解析
- 01_CNN.ipynb
    - 5.1節の予測で利用
- 02_DINO_Transfer_Learning_AttentionMap.ipynb
    - 5.1節の予測および5.2節の可視化で利用

### 自然言語処理
- 03_BidirectionalLSTM.ipynb
    - 5.1節の予測で利用 

### 表形式データ解析
- 04_LGBM_DecisionTree_AllVariables.ipynb
    - 5.1節の予測および5.2節の可視化で利用 
- 05_LGBM_DecisionTree_ExcludingPsychVars.ipynb
    - 5.1節の予測および5.2節の可視化で利用
- 06_UGM.ipynb
    - 5.2節の可視化(表形式データ分析)で利用



## 実行時に修正が必要な箇所
Google Colabで動作させることを前提としたコードとなっています。
各ファイルGoogle ドライブをマウントした後に、ディレクトリを移動する箇所があるので、ご自身の環境に合わせて変更いただければと思います。

Colab Notebooksフォルダ直下に「DLB2023」ディレクトリを作成し、その中に「data」や「src」を格納する場合
- 修正前
    - %cd '/content/drive/MyDrive/Colab Notebooks/DLBasics2023_colab/submit/'
- 修正後(例)
    - %cd '/content/drive/MyDrive/Colab Notebooks/DLB2023/'


## 画像の準備
画像は容量の関係でGitHub上にアップロードしていないので、お手数ですが、下記からDLしていただきますようお願いします。(4GBあります)
> https://www.kaggle.com/datasets/crawford/cat-dataset


本コードで使用する画像は「CAT_00」内のJPEG画像のみとなります。

> /data/images/CAT_00/xxx.jpg

という形で格納ください。

なお、xxxxxxxx_xxx.jpg.catというファイルについては「CAT_00」配下にあってもなくても問題ないので、容量に問題がなければ「CAT_00」ごとGoogleドライブにアップロードしていただいても大丈夫です。
