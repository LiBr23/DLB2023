# Deep Learning Bacic 2023
 


本コードは、
Deep Learning基礎講座 2023の最終課題で提出したものとなります。



## 実行時に修正が必要な箇所
Google Colabで動作させることを前提としたコードとなっています。
各ファイルGoogle ドライブをマウントした後に、ディレクトリを移動する箇所があるので、ご自身の環境に合わせて変更いただければと思います。

Colab Notebooksフォルダ直下に「DLB2023」ディレクトリを作成しその中に「data」や「src」を格納する場合
- 修正前
    - %cd '/content/drive/MyDrive/Colab Notebooks/DLBasics2023_colab/submit/'
- 修正後
    - %cd '/content/drive/MyDrive/Colab Notebooks/DLB2023/'


## 画像の準備
画像は容量の関係でGitHub上にアップロードしていないので、お手数ですが、下記からDLしていただきますようお願いします。

https://www.kaggle.com/datasets/crawford/cat-dataset


本コードで使用する画像は「CAT_00」内のJPEG画像のみとなります。
/data/images/CAT_00/xxx.jpg

という形で格納ください。

なお、xxxxxxxx_xxx.jpg.catというファイルについては「CAT_00」配下にあってもなくても問題ないので、容量に問題がなければ「CAT_00」ごとGoogleドライブにアップロードしていただいても大丈夫です。